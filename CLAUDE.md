# HAI

Human-AI Interaction research vault and publishing pipeline.

## Mission

This vault researches Human-AI Interaction at the personal level. It covers all modes of human-AI contact: relating, thinking with, creating with, delegating to, learning from. The goal is deep expertise AND published outputs.

## Collaboration Philosophy

**Do not synthesize for me. Do not write original analysis for me. Ask me questions. Provide structure. Handle infrastructure. I do the thinking.**

Claude handles:
- **Infrastructure** — file creation, naming, linking, metadata
- **Navigation** — finding relevant notes, surfacing connections
- **Scaffolding** — questions, prompts, structure
- **Process guidance** — what's the next step? what's missing?
- **Editing** — polish, clarity—on human drafts

The human does:
- **Understanding** — what does this mean?
- **Synthesis** — how does this connect?
- **Judgment** — what matters? what's true?
- **Voice** — how do I say this?
- **Creation** — what's the original contribution?

## Session Start
1. Read STATUS.md first
2. Review recent progress and next actions

## Session End
1. Update STATUS.md (Current State, Recent Progress, Next Actions)

## Status Tracking

This project uses the Exo status system.
- **STATUS.md** — Current project state (update at each work session)

## Folder Purposes

### Information Flow
Capture (Inbox) → Process (Sources) → Understand (Concepts) → Create (Analysis) → Publish (Outputs)

- **Inbox/** — Raw captures: links, rough notes, ideas, papers to process
- **Sources/** — Processed literature: papers, books, articles (faithfully summarized)
- **Concepts/** — Atomic notes: frameworks, ideas, synthesized understanding (FLAT—no subfolders)
- **Analysis/** — Original thinking: synthesis, arguments, positions
- **Outputs/** — Publishing pipeline: drafts → finished work
- **Log/** — Research activity logs (dated entries)
- **Maps/** — MOCs for navigation
- **Meta/** — Templates, tags taxonomy, vault documentation

## Conventions

### File Naming
- Sources: `SRC-Author-Year-Title.md` (e.g., `SRC-Turkle-2011-Alone-Together.md`)
- Concepts: `Concept-Name.md` in kebab-case (e.g., `Cognitive-Offloading.md`)
- Analysis: `ANL-Topic.md` (e.g., `ANL-Frictionless-Intimacy-Problem.md`)
- Outputs: `OUT-Title.md` with status in frontmatter
- Logs: `YYYY-MM-DD.md`
- Maps: `MOC-Topic.md`

### Linking
- Always use [[wikilinks]]
- Keep Concepts/ flat—no subfolders
- Link aggressively

### YAML Frontmatter Schema
```yaml
---
type: # [source, concept, analysis, output, log, map]
status: # [inbox, processing, seed, growing, evergreen, draft, published, archived]
created: YYYY-MM-DD
modified: YYYY-MM-DD
author: # [human, claude, hybrid] - for outputs especially
confidence: # [low, medium, high] - how solid is this understanding
sources: # list of SRC- note links
tags: []
publish: false  # [true, false] - ready for public?
summary: # 1-2 sentence overview
---
```

### Public Publishing
This vault may become public via Obsidian Publish. Every note has a `publish` field in frontmatter:
- `publish: false` — private, work in progress (default)
- `publish: true` — ready for public viewing

Default is always `publish: false`. Only mark `publish: true` when content is polished and I explicitly decide to make it public.

## How to Help

- **Processing a source:** Ask clarifying questions, suggest structure, but have me write the summary
- **Developing a concept:** Surface related notes, ask what I think connects, don't synthesize for me
- **Working on an output:** Provide scaffolding, ask about audience and purpose, edit my drafts, don't write for me
- **Always:** Tell me what the next step in the process might be
