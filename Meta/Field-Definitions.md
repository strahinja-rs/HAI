# Frontmatter Field Definitions

Precise definitions for every YAML frontmatter field used in this vault. Referenced from CLAUDE.md.

---

## `type`

**What it means:** The kind of note. Determines which folder it lives in and which templates/fields apply.

**Values:** `source`, `concept`, `analysis`, `output`, `log`, `map`

**When to update:** Set once at creation. Never changes.

---

## `status`

**What it means:** Where this note is in its lifecycle. Tracks *development stage*, not certainty.

**Values:** `inbox`, `processing`, `seed`, `growing`, `evergreen`, `draft`, `published`, `archived`

**Per-note-type progressions:**

| Note type | Progression | Trigger for advancement |
|-----------|------------|------------------------|
| **Source** | `inbox` → `processing` → `evergreen` | inbox = captured, not read. processing = reading/discussing. evergreen = fully read and processed. |
| **Concept** | `seed` → `growing` → `evergreen` | seed = core insight captured. growing = survived retrieval, being developed. evergreen = settled understanding, stable. |
| **Analysis** | `draft` → `published` | draft = in progress. published = finished and public-ready. |
| **Output** | `draft` → `published` | Same as analysis. |
| **Any type** | → `archived` | No longer active/relevant but kept for reference. |

**When to update:**
- **Sources:** When you finish reading/processing, move to `evergreen`.
- **Concepts:** Based on retrieval exercise results. Clear extended recall = evidence for seed → growing. Multiple successful retrievals + developed connections = growing → evergreen.
- **Analysis/Outputs:** When the human decides it's done or published.

**What does NOT trigger a status update:**
- A discussion that changes your certainty about the content (that's `confidence`)
- Adding connections or links (unless it's part of a deliberate development push)

---

## `confidence`

**What it means:** How epistemically solid the *content* is. Tracks *certainty*, not development stage.

**Values:** `low`, `medium`, `high`

**Per-note-type meaning:**

| Note type | What confidence measures |
|-----------|------------------------|
| **Source** | How trustworthy/reliable the source is. Peer-reviewed paper = high. AI research report = medium. Blog post = low. |
| **Concept** | How sure you are the claim is true/useful. A speculative but interesting idea = low. A well-grounded insight = high. |
| **Analysis** | How solid the argument is. |
| **Output** | How confident you are in the piece's quality and accuracy. |

**When to update:**
- When a discussion, reading, or experience shifts your certainty about the content — in either direction.
- Can go up (new evidence supports it) or down (new evidence challenges it).

**What does NOT trigger a confidence update:**
- Retrieval exercises (those affect `status`)
- Adding connections or structure

**Key distinction:** `status` and `confidence` are independent. A concept can be:
- High-confidence seed — you're sure of the insight, just haven't developed it yet
- Low-confidence evergreen — well-developed exploration of something inherently uncertain
- Low-confidence seed — speculative, early, might not hold up

---

## `created`

**What it means:** The date this note was created.

**Format:** `YYYY-MM-DD`

**When to update:** Set once at creation. Never changes.

---

## `modified`

**What it means:** The date of the last substantive edit to this note.

**Format:** `YYYY-MM-DD`

**When to update:** Whenever any of the following change:
- Content (sections, text, claims)
- `status`
- `confidence`

**What does NOT count as a substantive edit:** Typo fixes, formatting changes.

---

## `author`

**What it means:** Who created the content of this note.

**Values:** `human`, `claude`, `hybrid`

- `human` — human wrote or summarized the content
- `claude` — Claude generated it (infrastructure, scaffolding)
- `hybrid` — collaborative (human thinking, Claude structure)

**Per-note-type guidance:**
- **Concepts:** Always `human`. The insight is the human's even if Claude built the note structure.
- **Sources:** `human` if the human wrote the summary. `claude` if Claude generated it (e.g., Gemini reports stored as-is). `hybrid` if both contributed.
- **Analysis/Outputs:** Depends on who actually wrote it. Most relevant field for these types.

**When to update:** Set at creation. Can change if authorship changes (e.g., human rewrites a Claude-generated summary).

---

## `sources`

**What it means:** List of `[[SRC-...]]` links that this note draws from.

**Format:** YAML list of wikilinks

**Per-note-type guidance:**
- **Concepts (original):** Empty, or lists sources that *inspired* the thinking. The `original` tag handles the distinction.
- **Concepts (literature):** Links to the SRC- notes where the concept was found.
- **Analysis/Outputs:** Sources cited or referenced.
- **Sources:** Usually empty (a source doesn't source itself). Can link to related sources.

**When to update:** When new sources inform the note's content.

---

## `tags`

**What it means:** Categorization tags from `Meta/TAGS.md`.

**Format:** YAML list

**When to update:** At creation, or when the note's scope changes. Do not invent new tags without discussing first.

---

## `publish`

**What it means:** Is this note ready for public viewing?

**Values:** `true`, `false`

**Default:** Always `false`.

**When to update:** Only when the human explicitly decides to make it public. Claude never sets this to `true` independently.

---

## `summary`

**What it means:** 1-2 sentence overview of the note's content.

**When to update:** At creation. Updated if the note's core claim or scope changes significantly.
