# HAI Research Process

This document describes the research methodology for the HAI vault. Developed during Session 5 (Feb 2, 2026) after evaluating Gemini Deep Research, Claude Research, and Claude Code as complementary research tools.

This is a living document — update as the process evolves.

---

## The Core Loop

```
Question → Research Execution → Reading & Processing → New Questions
    ↑                                                        │
    └────────────────────────────────────────────────────────┘
```

Research is cyclical. Each cycle starts with a question and ends with new questions that feed the next cycle.

---

## Step 1: The Question

Before any tool runs, get clear on what you want to know. Write it down.

**Question types shape the research:**

- **Landscape question:** "What exists in this area? Who works on it? What are the major sub-areas?" → Produces overview maps. Appropriate at the start of a new topic or when entering unfamiliar territory.
- **Specific/analytical question:** "What does the research say about X? What are the competing positions? What evidence exists?" → Produces targeted analysis. Appropriate when you've identified a specific concept or debate to understand.
- **Phenomenological question:** "What is it like to be inside this? How does it feel? What is the lived experience?" → This is your natural lens. These questions often emerge during reading as reactions to material, not as planned research goals. They produce your strongest original thinking (Friction Discernment, Interaction Field, AI Whisperers all came from this kind of question). **Note:** Phenomenological questions can also be run through research tools — Gemini can search Reddit, YouTube, personal blogs, and forum discussions for first-person accounts of lived experience. "Find first-person accounts of what it's like to use AI as a creative collaborator — not expert analysis, not product reviews — lived experience reports."
- **Comparative question:** "How does X differ from Y? What are the trade-offs?" → Produces structured comparisons. Useful when you've identified two or more competing frameworks, approaches, or concepts.
- **Genealogical question:** "Where did this idea come from? What's its intellectual history?" → Traces origins and influence chains. Useful for understanding why a concept exists and what it's responding to.
- **Practical/design question:** "How would you actually build this? What are the concrete patterns?" → Produces actionable frameworks. Useful when moving from understanding to application.
- **Adversarial question:** "What's the strongest argument against X? Who disagrees and why?" → Tests your concepts. Useful for stress-testing ideas you're developing, especially before publishing.

This list will grow as new question types emerge in practice. **The question determines the tool, not the other way around.** Don't start with "let me run Gemini" — start with "what do I want to know?"

### Getting clear on the question

- Write the question in plain language
- Ask: Is this a landscape question, a specific question, or something I'll only discover through reading?
- Ask: What would a good answer look like? What format? What depth?
- Ask: What do I already know about this? What context does the research tool need?

---

## Step 2: Research Execution

### The Meta-Prompt Approach

For substantial research, use a reasoning model (Claude, Gemini chat, etc.) to write the research prompts rather than writing them directly. This ensures the prompts are structured for each tool's strengths.

**Meta-prompt template:**

```
The research goal is [RESEARCH GOAL].

Think about the research goal, what do you need to know about it.

We won't do the research inside this conversation, but elsewhere.
Here, we're going to write prompts for doing the research. And then
I'll return the research outputs here for analysis.

First, please deeply understand our research goal and think what
else we need to understand it.

Second, take the following how-tos into account:

[INSERT TOOL-SPECIFIC HOW-TOS]

Third, write the prompts to execute our research goal. Give me
just the prompts, and once I get back with the research outputs,
we'll continue.
```

### Tool Roles

#### Gemini Deep Research
**Strength:** Breadth. Finding sources. Landscape mapping. Identifying what exists.

**How it works:** Agentic loop — decomposes your query into sub-tasks, runs ~80 search queries, reads snippets from 100+ sources, synthesizes a report. Shows you a research plan you can edit before execution runs.

**Best for:** Landscape questions. "What exists in X area?" "Who is working on Y?" "What are the major frameworks for Z?"

**Limitations:**
- The Snippet Trap: often reads snippets, not full pages. "100 sources" may mean 100 snippets.
- Academic blindspot: can't access paywalled journals (JSTOR, ACM Digital Library, etc.)
- Hallucination of consensus: if 5 low-quality blogs say the same wrong thing, it treats that as verified
- Synthesis ceiling: good at aggregating, weaker at genuine analysis
- AI slop in writing style: confident prose that exceeds the confidence of the actual claims

**Prompting guidance:**
- State objective clearly and specifically
- Define scope: time frames, geographic regions, thematic focus
- Assign a role/perspective if helpful
- Specify output format: structured report with headings, tables, citations
- Break complex objectives into sub-questions
- Use negative constraints: "Do NOT use blogs. Only primary sources."
- Use conflict resolution framing: "You will find conflicting data. Do not average — explain the conflict."
- **Review and edit the research plan before execution** — this is your main steering point

#### Claude Research (claude.ai)
**Strength:** Structured analysis. Deeper on specific areas. Better source selection.

**How it works:** Agentic — conducts multiple searches that build on each other, determines what to investigate next, explores different angles automatically.

**Best for:** Specific/analytical questions. "What does the research say about X?" "Compare these frameworks." "What are the concrete design patterns for Y?"

**Limitations:**
- Same paywall blindspot as Gemini
- Can be less comprehensive in source coverage than Gemini
- Uses up conversation limits faster than normal chat

**Prompting guidance:**
- Be clear, direct, and specific
- Use XML-style tags (<context>, <task>, <requirements>) to organize prompt sections
- Break complex research into sequential sub-questions
- Specify exact output format
- Ask for confidence levels and areas of uncertainty
- Ask for competing hypotheses
- Include background context and constraints

**Access note:** Claude Research is a paid feature (Pro, Max, Team, Enterprise) on claude.ai. Requires web search to be enabled. Not available in Claude Code.

#### Claude Code (Terminal)
**Not a research tool.** Claude Code is the vault analyst and thinking partner.

**Strength:** Reading files, creating notes, analyzing research outputs, working through ideas, infrastructure.

**Role in the process:**
- Writes research prompts (meta-prompt step)
- Analyzes research outputs after you bring them back
- Identifies what's useful vs. filler in research outputs
- Creates concept notes from your observations
- Manages vault infrastructure (files, frontmatter, links, tags)
- Asks questions to push your thinking
- Does NOT synthesize or write original analysis for you

**Web capabilities:** Has WebSearch (shallow — returns snippets) and WebFetch (reads one URL at a time). Useful for quick lookups, not for deep research.

#### The Human
**The actual researcher.** Tools find material and organize it. You do the thinking.

**Your role:**
- Formulate the question (Step 1)
- Review and edit research plans before execution
- Read the outputs and react
- Capture observations in the session log
- Make the judgment calls: what matters, what connects, what's original
- Write the core insights for concept notes (even 2-3 sentences)

---

## Step 3: Reading & Processing

These often happen together — you read, react, and process in the same session.

### Reading
Read research outputs in Obsidian. This is where your actual work happens.

**During reading:**
- Dump questions and reactions in `1-Inbox/Reading notes.md` (ephemeral scratch — cleared after processing)
- Bring question batches to Claude Code in terminal for clarification
- **Original thinking and reactions go in the session log** under "Human Observations" — not in reading notes

**What to watch for while reading:**
- Where does the material trigger a reaction? (That's signal)
- Where does it feel flat or obvious? (That's not where your contribution is)
- Where do you disagree or feel something's missing? (That's potential original territory)
- What connects to things you already know from experience? (MatkexAI, Evoke, Guidance)

### Processing
Work through observations with Claude Code.

**Claude Code helps with:**
- Answering terminology questions plainly
- Flagging what's concept-worthy vs. just clarification
- Surfacing related notes already in the vault
- Asking questions to push your thinking further
- Building concept notes from your core insights (you write the insight, Claude handles infrastructure)

**What processing produces:**
- Clarifications (live in your head, cleared from reading notes)
- Concept notes (filed in `3-Concepts/`, created at end of reading session)
- New questions (feed back to Step 1 for next research cycle)
- Updated session log (permanent record of what happened)

---

## Step 4: New Questions

Processing always generates new questions. These go into three buckets:

1. **Immediate research questions** → Queue for next research cycle (Step 1)
2. **Questions that need sitting with** → Note in session log, revisit later
3. **Questions about the process itself** → Update this document

---

## Running Both Tools

For important topics, run both Gemini and Claude Research with prompts tailored to each tool's strengths:

- **Gemini first** when you need the landscape: what exists, who works on it, what are the categories
- **Claude second** when you need depth on something Gemini surfaced: what does the research actually say, what are the concrete patterns
- **Both in parallel** when the question is broad enough to benefit from two perspectives

After both outputs return, bring them to Claude Code for comparative analysis before reading in depth.

---

## Finding Paywalled Papers

Research tools (Gemini, Claude Research) can't access paywalled academic databases (JSTOR, ACM Digital Library, IEEE, etc.). But they can identify **titles, authors, abstracts, and DOIs** — which is enough to find access separately.

**Discovery workflow:**
1. Use Gemini/Claude Research to identify relevant papers (titles, authors, year, venue)
2. Check **Google Scholar** — often links to free PDF versions or author preprints
3. Check **Semantic Scholar** (semanticscholar.org) — free, good for finding related papers and citation graphs
4. Check **Connected Papers** (connectedpapers.com) — visual graph showing how papers relate to each other
5. Check **arXiv** — many authors post preprint versions before or after publication
6. Check the **author's personal website** — academics often host their own PDFs
7. ACM Digital Library sometimes has open-access versions of CHI proceedings
8. Once you have a title or DOI, Sci-Hub can find the full text (use at own risk/responsibility)

**Key principle:** Use research tools to identify *what* to read. Find access separately. Don't skip a paper just because the research tool couldn't read it — the most important papers in HAI are often behind ACM paywalls.

---

## Research Methodology Awareness

This process is self-designed, not formally trained. Known risks:
- Blind spots from not knowing what formal research methodology would catch
- Confirmation bias in question formulation
- Over-reliance on web-accessible sources (paywall blindspot)
- The synthesis tools aggregate but don't deeply analyze — their confidence can exceed their accuracy

Mitigations:
- Stay humble about what you don't know
- When a concept feels important, look for who disagrees with it
- Track confidence levels on concept notes
- Periodically ask: "What would a trained researcher do differently here?"
- Methodology research completed — see Qualitative Research Methods section below and [[SRC-Gemini-2026-Qualitative-Research-Frameworks-HAI]]

---

## Qualitative Research Methods

Based on the methodology research report ([[SRC-Gemini-2026-Qualitative-Research-Frameworks-HAI]]). This section provides reference material for choosing and executing qualitative research methods in HAI.

### Methods Most Relevant to This Research

Three methods align with the practitioner-researcher, first-person, design-oriented approach of this vault:

1. **Phenomenology** — studying the lived experience of interacting with AI. The human's natural lens. Core question: "What is it like to be inside this?"
2. **Autoethnography / Autobiographical Design** — the researcher's own experience as data. The vault logs and Guidance development process are already autoethnographic data. Core question: "How does my own identity and process shape this interaction?"
3. **Research Through Design (RtD)** — the act of designing generates knowledge. Guidance and product experiments are RtD if documented with research intent. Core question: "What if we designed X differently?"

These can be combined. The Guidance project is simultaneously autobiographical design (living with a self-built system) and RtD (the design process generates knowledge about human-AI interaction patterns).

### Methodological Selection Matrix

| Research Question Type | Method | Data Source | Validity Criterion | Output |
|---|---|---|---|---|
| "What is it like to experience X?" | Phenomenology | Interviews, first-person reflection | Resonance/Fidelity | Thematic description of essence |
| "How does my identity shape this?" | Autoethnography | Diaries, logs, self-observation | Reflexivity | Narrative arc, critical reflection |
| "What is the underlying process?" | Grounded Theory | Interviews, observation, documents | Saturation | Theoretical model or taxonomy |
| "How can we solve this ethically?" | Action Research / PD | Workshops, co-design | Impact/Democracy | Intervention + reflection |
| "What if we designed X differently?" | Research Through Design | Prototypes, design logs | Generativity | Annotated portfolio, Strong Concept |
| "What is this group's culture?" | Ethnography | Participant observation, field notes | Thick Description | Cultural monograph, vignettes |
| "What happened in this deployment?" | Case Study | Mixed methods | Triangulation | Lessons learned, failure analysis |

### Trustworthiness Criteria (Guba & Lincoln)

The validity framework for qualitative research. Rigor is not statistical significance — it's trustworthiness.

1. **Credibility** (internal validity)
   - *Triangulation:* Multiple data sources (e.g., logs + interviews + observation)
   - *Member checking:* Return findings to participants for verification
   - *Prolonged engagement:* Spend enough time to overcome novelty effects

2. **Transferability** (external validity)
   - *Thick description:* Enough context that others can judge applicability to their own situation
   - *Purposive sampling:* Select information-rich cases, not convenient ones

3. **Dependability** (reliability)
   - *Audit trail:* Log all methodological decisions and why they changed
   - *Codebooks:* If working in a team, establish inter-coder agreement

4. **Confirmability** (objectivity)
   - *Reflexivity:* State your biases explicitly. A practitioner studying their own product must disclose this and discuss mitigation.

### Common Pitfalls

- **The Generalizability Trap:** Apologizing for small sample sizes. Qualitative research aims for conceptual depth, not statistical significance.
- **Methodolatry:** Obsessing over correct method execution at the expense of genuine insight. Method is a scaffold, not a cage.
- **Quote Salad:** Pages of participant quotes with no analysis. Theoretical abstraction is required to move from journalism to research.
- **Anthropomorphism Bias:** Uncritically adopting user language ("The AI wanted to help me") without analyzing the projection. Distinguish system output from user attribution of intent.
