# Interaction Design in Human-AI Interaction: A Comprehensive Synthesis

**The design layer of human-AI interaction has matured rapidly since 2023, with established frameworks converging on principles of transparency, user control, and graceful failure—yet significant gaps remain in agentic oversight, multi-agent coordination, and the fundamental challenge that prompting creates novel cognitive demands with no HCI precedent.** This synthesis maps the complete landscape of how humans and AI actually meet at the point of interaction: the paradigms, patterns, frameworks, and empirical realities of everyday AI use. With **54.6%** of U.S. adults now using generative AI and ChatGPT reaching **800+ million weekly active users**, understanding interaction design has become critical infrastructure for the AI era.

---

## 1. Executive summary

Human-AI interaction design has evolved from a nascent research area to a rapidly maturing field with established industry frameworks, emerging academic theory, and extensive empirical data on real-world usage. Four major design frameworks—Microsoft HAX Guidelines, Google PAIR, Apple HIG, and IBM Design for AI—have converged on core principles: **transparency about AI capabilities**, **user control and correction mechanisms**, **explainability of AI decisions**, and **graceful failure handling**. These frameworks provide actionable guidance for practitioners, though significant gaps remain in multi-agent oversight, longitudinal user relationships, and cultural adaptation.

The interaction paradigm landscape spans nine distinct modalities, from mature conversational interfaces to emerging brain-computer integration. **Conversational/chat interfaces dominate current use** (the ChatGPT paradigm), but the field is rapidly expanding toward multimodal, agentic, and ambient paradigms. The **agentic paradigm**—AI acting autonomously with human oversight—represents the most significant near-term evolution, with Gartner reporting a **1,445% surge** in multi-agent system inquiries from Q1 2024 to Q2 2025. This paradigm introduces novel design challenges around delegation, trust calibration, and intervention patterns that existing frameworks only partially address.

Empirical research reveals how people actually use AI differs substantially from controlled laboratory studies. OpenAI's analysis of **1.5 million conversations** found users engage in three meta-categories: asking (40%), doing (35%), and expressing (25%). Usage patterns evolve predictably: users shift from machine-like prompts toward conversational styles, message volume has grown **5x** year-over-year, and "frontier workers" at the 95th percentile send **6x more messages** than median users at the same companies—suggesting AI skill is becoming a new axis of workplace differentiation.

**Prompting as an interface paradigm** represents a genuinely unprecedented interaction pattern. Unlike CLI (command memorization), GUI (visual discovery), or NUI (gesture/voice), prompting creates what Subramonyam et al. (CHI 2024) call a **"Gulf of Envisioning"**—a new cognitive gap where users must formulate precise intent before execution even begins. Research shows non-experts struggle systematically: they explore opportunistically rather than strategically, over-generalize from single examples, and apply human-to-human instruction expectations that fail with AI systems. Meredith Ringel Morris (Google DeepMind) argues prompting may be a "poor user interface" that transitioned from debugging tools to de facto paradigm without deliberate design.

Looking ahead, several paradigms are emerging from research into early products: **persistent AI companions** (Microsoft Copilot's memory features, Lenovo's cross-device Qira), **AI in AR/VR** (Apple Vision Pro, Android XR), **ambient AI** (predictive smart home systems), and **AI wearables** (Ray-Ban Meta glasses, Halliday AI glasses). Brain-computer interfaces with AI copilots remain in clinical research but demonstrate the trajectory toward direct neural interaction.

Key tensions define the field: freedom versus structure in prompting (open prompts enable creativity but increase cognitive load); automation versus agency (more autonomous AI creates more oversight challenges); transparency versus simplicity (explaining AI reasoning adds complexity). Practice often leads research—streaming UI libraries, production memory architectures, and persona design patterns are more developed in industry than academia—while academic research provides crucial frameworks for understanding user psychology, trust calibration, and long-term effects.

For practitioners, the evidence suggests: start with Microsoft HAX for actionable team processes; supplement with Google PAIR for explainability depth; expect prompting-only interfaces to face usability challenges; design progressive autonomy rather than binary control; and prepare for the agentic shift by building intervention and oversight patterns now. The next two years will likely see the conversational paradigm extend rather than replace, with multimodal, agentic, and ambient capabilities layering onto chat-based foundations.

---

## 2. Comprehensive map of interaction paradigms

### Paradigm architecture overview

Nine distinct paradigms for human-AI interaction operate across different maturity levels, user contexts, and design requirements. These paradigms are not mutually exclusive—modern AI systems increasingly combine multiple paradigms (e.g., multimodal + agentic + conversational).

```
                    ┌─────────────────┐
                    │   SUPERVISORY   │ ← Human oversight layer
                    │   (Monitoring)  │
                    └────────┬────────┘
                             │
        ┌────────────────────┼────────────────────┐
        │                    │                    │
        ▼                    ▼                    ▼
┌───────────────┐   ┌───────────────┐   ┌───────────────┐
│   AGENTIC     │   │ COLLABORATIVE │   │   AMBIENT     │ ← Autonomy layer
│ (Autonomous)  │◄──│ (Co-creation) │──►│  (Passive)    │
└───────┬───────┘   └───────┬───────┘   └───────┬───────┘
        │                   │                   │
        └───────────────────┼───────────────────┘
                            │
        ┌───────────────────┼───────────────────┐
        │                   │                   │
        ▼                   ▼                   ▼
┌───────────────┐   ┌───────────────┐   ┌───────────────┐
│ CONVERSATIONAL│   │  MULTIMODAL   │   │    VOICE      │ ← Interface layer
│   (Chat)      │◄──│   (Combined)  │──►│   (Speech)    │
└───────────────┘   └───────────────┘   └───────────────┘
                            │
                            ▼
                    ┌───────────────┐
                    │   EMBODIED    │ ← Physical layer
                    │  (Physical)   │
                    └───────────────┘
```

### Conversational/chat paradigm

**Definition:** Text-based dialogue interfaces enabling natural language interaction through typed messages and responses—the dominant paradigm since ChatGPT's November 2022 release.

**Design challenges** include the "interface dilemma" (balancing text, voice, and visual modalities), conversational repair and error recovery, context retention across sessions, managing user expectations versus actual capabilities, and turn-taking initiative management. DirectGPT research (CHI 2024) found that adding direct manipulation principles to chat interfaces significantly improves engagement over pure conversational interaction.

**Maturity: MATURE.** Key research: Masson et al. "DirectGPT" (CHI 2024); Tankelevitch et al. "Metacognitive Demands of Generative AI" (Microsoft Research 2024); Shi et al. "HCI-Centric Survey of Human-GenAI Interactions" (arXiv 2024). **Confidence: HIGH.**

### Voice interaction paradigm

**Definition:** Spoken dialogue interfaces enabling hands-free, eyes-free interaction through speech recognition and synthesis—Alexa, Siri, Google Assistant, and automotive voice systems.

**Design challenges** center on natural language understanding across domains and accents, error handling in noisy environments, lack of visual feedback requiring careful audio cue design, privacy concerns with always-listening devices, and multi-turn conversation management. A 2024 systematic review identified six research categories: UX measurement, usability engineering, personalization, privacy/security/ethics, cross-cultural studies, and technological challenges.

**Maturity: ESTABLISHED** (trending toward mature). Generation Z studies show voice interaction efficiency rated as the most important usability criterion. LLM integration into voice assistants reduces user-reported annoyances (ECIS 2024). **Confidence: HIGH.**

### Multimodal paradigm

**Definition:** Systems combining multiple input/output modalities—text, voice, image, video, gesture, gaze, haptics—for more natural and flexible human-AI communication (GPT-4o, Gemini, AR/VR systems).

**Design challenges** involve modality fusion and temporal synchronization, determining optimal modality for each context (the "interface dilemma"), cross-platform adaptability, computational resources, and privacy concerns from gaze tracking and voice recording. Research recommends hybrid approaches combining GUI with multimodal inputs as most practical. Multimodal systems reduce ambiguity through complementary modalities.

**Maturity: ESTABLISHED** (rapidly evolving). **70%+** of customer interactions expected to integrate AI by 2025. **Confidence: HIGH.**

### Agentic paradigm

**Definition:** AI systems acting autonomously to accomplish complex tasks with varying human oversight—goal-directed behavior, planning, tool use, and multi-step execution (Devin, GitHub Copilot Agents, Salesforce Agentforce).

**Critical design challenges** (SSRN 2025): goal-plan-execution gap (mismatch between user goals, AI interpretation, and real-world execution), transparency issues (difficulty observing agent reasoning), intervention mechanisms (when and how humans should intervene), and autonomy calibration (balancing efficiency with safety).

A spectrum of human-in-the-loop patterns has emerged:

| Pattern | Description |
|---------|-------------|
| Human-in-the-loop (HITL) | Real-time human involvement in decisions |
| Human-on-the-loop (HOTL) | Human monitors with intervention capability |
| Human-above-the-loop | Strategic oversight without tactical involvement |
| Human-before-the-loop | Pre-deployment configuration and training |
| Human-after-the-loop | Post-execution auditing and refinement |
| Human-out-of-loop | Full autonomy for low-risk tasks |

**Maturity: EMERGING** (2024-present rapid growth). Gartner predicts **40%+** of agentic AI projects will be abandoned by 2027 due to unclear business value—design quality will determine which survive. **Confidence: HIGH.**

### Collaborative/co-creation paradigm

**Definition:** Real-time human-AI partnership in creative or productive tasks where both contribute and iterate—GitHub Copilot, Figma AI, Adobe Firefly, Notion AI.

Empirical studies show significant productivity effects: tasks completed **55.8% faster** with Copilot (Peng et al. 2023), **10.6%** increase in pull requests (Harness 2024), and **3.5-hour reduction** in cycle time. However, effects are heterogeneous—less experienced programmers benefit most, and **44%** of generated code may have security issues requiring review.

**Design challenges** include maintaining user agency and creative ownership, managing interruptions to flow state, quality verification of AI contributions, integration with existing workflows, and balancing automation with control. Studies show Copilot can be cognitively distracting, and in pair programming contexts, humans prioritize human partners over AI.

**Maturity: ESTABLISHED** (code) / **EMERGING** (other domains). **Confidence: HIGH.**

### Ambient/passive paradigm

**Definition:** AI operating continuously in background, sensing context, learning patterns, and proactively assisting without explicit commands—clinical documentation systems, smart home automation, productivity suggestions.

**Design challenges** are substantial: **81%** of U.S. adults express privacy concerns (Pew 2023), transparency about automated actions, avoiding over-automation, graceful degradation when context is misread, and preserving user autonomy. The concept traces to "ambient intelligence" coined in the 1990s by Eli Zelkha and evolved from Mark Weiser's ubiquitous computing vision (1991).

Successful implementations in healthcare (Nuance DAX) and smart homes demonstrate **30%+ reduction** in administrative tasks. Key design principle: balance helpful proactivity against intrusive over-reach.

**Maturity: ESTABLISHED** (smart home/healthcare) / **EMERGING** (general AI). **Confidence: MEDIUM-HIGH.**

### Embodied/robotics paradigm

**Definition:** AI integrated into physical systems interacting autonomously with the physical world—humanoid robots (Tesla Optimus, Figure), cobots, service robots, autonomous vehicles, wearable agents.

**Design challenges** include inferential privacy risks where agents form sensitive conclusions (arXiv 2025), physical safety in human-robot contact, multimodal perception integration (vision, audio, haptics, proprioception), and sim-to-real transfer difficulties. Research shows embodiment increases user trust compared to virtual agents, and social cues with emotional expression become important.

**Market trajectory:** Goldman Sachs projects **$38B** embodied AI market by 2035; **1 billion robots** in use predicted by 2050.

**Maturity: EMERGING** (general purpose) / **ESTABLISHED** (industrial). **Confidence: MEDIUM-HIGH.**

### Supervisory paradigm

**Definition:** Human oversight and monitoring of AI systems with varying intervention capability, from real-time control to post-hoc auditing—governance dashboards, MLOps monitoring, content moderation review.

**Design challenges** focus on maintaining situational awareness during monitoring, alert fatigue from excessive notifications, determining appropriate intervention points, preserving human expertise despite automation, and scalability bottlenecks (human oversight capacity limits AI deployment). McKinsey notes "oversight itself a potential bottleneck to productivity."

**Maturity: ESTABLISHED.** **Confidence: HIGH.**

### Emerging paradigms

**Brain-computer interfaces** achieved breakthroughs in 2023-2024 with therapeutic applications for motor and linguistic deficits, Neuralink human implants, and high-accuracy speech BCIs. Columbia's BISC chip (December 2025) enables tens of thousands of electrodes in an ultra-thin implant. **Maturity: NASCENT** (consumer), **EMERGING** (clinical).

**Human-AI symbiosis** involves co-adaptive systems where humans and AI continuously learn from each other—real-time mutual learning integrating cognitive, emotional, and physiological systems. **Maturity: NASCENT.**

**Extended reality AI** encompasses immersive training with AI coaches, virtual prototyping, and spatial computing interfaces in VR/AR/MR. **Maturity: EMERGING.**

---

## 3. Design frameworks and guidelines

### Microsoft HAX Guidelines: The practitioner toolkit

Microsoft's Human-AI eXperience (HAX) Toolkit provides **18 evidence-based guidelines** synthesized from 20+ years of HCI research, introduced in an award-winning CHI 2019 paper and validated with 49 design practitioners across 20 AI products.

**Guidelines organized by interaction phase:**

- **Initially (G1-G2):** Make clear what the system can do and how well it can do it
- **During interaction (G3-G6):** Time services based on context, show contextually relevant information, match social norms, mitigate biases
- **When wrong (G7-G11):** Support efficient invocation, dismissal, and correction; scope services when in doubt; explain why the system did what it did
- **Over time (G12-G18):** Remember recent interactions, learn from user behavior, update cautiously, encourage granular feedback, convey consequences, provide global controls, notify about changes

**Practical resources include:** HAX Design Library (searchable pattern database), HAX Workbook (Excel prioritization using T-shirt sizing), 33 flexible design patterns, and HAX Playbook (test scenario generation). Team exercises take approximately 60 minutes to complete.

**Strengths:** Most comprehensive practical toolkit with implementation-ready patterns; research-validated; well-organized by lifecycle phases. **Limitations:** Developed primarily for graphical interfaces; last major update December 2022; less emphasis on generative AI specifics.

**Resource:** https://www.microsoft.com/en-us/haxtoolkit/

### Google PAIR Guidebook: The research foundation

Launched in 2017, PAIR's second-edition guidebook (updated 2023-2024) draws on insights from 100+ Googlers, industry experts, and academic research across six chapters: User Needs + Defining Success, Data Collection + Evaluation, Mental Models, Explainability + Trust, Feedback + Control, and Errors + Graceful Failure.

PAIR excels at explainability guidance, distinguishing feature-based, example-based, and counterfactual explanations. Resources include AI Explorables (interactive ML concept explanations), Data Cards Playbook, Learning Interpretability Tool (LIT), and Model Cards documentation framework. GenAI-specific updates began in late 2023 addressing EU AI Act and Biden's Executive Order requirements.

**Strengths:** Most comprehensive on explainability and trust calibration; strong research methodology emphasis; actively updated for generative AI. **Limitations:** More conceptual than prescriptive; requires practitioner synthesis; less structured prioritization.

**Resource:** https://pair.withgoogle.com/guidebook/

### Apple Human Interface Guidelines: Platform-native AI

Apple's HIG includes a Machine Learning section (updated 2022-2024) emphasizing transparent, intuitive AI that feels native to Apple platforms. Core principles: communicate AI presence, set appropriate expectations, design for correction, provide feedback mechanisms, respect user autonomy.

**Patterns cover outputs** (multiple suggestions vs. single predictions, confidence indicators, progressive disclosure) **and inputs** (implicit behavioral feedback, explicit corrections, personalization controls).

**Strengths:** Tight platform integration; clear user control and privacy emphasis; practical UI patterns. **Limitations:** Apple ecosystem-specific; less comprehensive than Microsoft/Google; less academic validation documented.

**Resource:** https://developer.apple.com/design/human-interface-guidelines/machine-learning

### IBM Design for AI: The philosophical foundation

IBM's framework emphasizes relationship-based design through three lenses: Purpose (reason for engagement), Value (augmented capabilities), and Trust (predicated on security, control, quality). The December 2022 framework defines four AI characteristics: Understands, Reasons, Learns, Interacts.

IBM Research's **2024 CHI paper** specifically addresses generative AI with seven principles: design for multiple outcomes, design for imperfection, design for exploration, design for control, design for mental models, design for explanations, and design against potential harms (hallucinations, toxic content, copyright issues, displacement).

**Resources include:** Everyday Ethics for AI guidebook, Carbon for AI design system (uses "light" metaphor for AI-generated content), AI Label component, and Conversation Design Guide.

**Strengths:** Deep philosophical grounding; enterprise-focused; Carbon provides implementation-ready components. **Limitations:** Site appears less actively maintained since December 2022; IBM-centric; more abstract than competitors.

**Resources:** https://www.ibm.com/design/ai/ and https://carbondesignsystem.com/guidelines/carbon-for-ai/

### Framework convergence and gaps

**Universal principles across all frameworks:**

| Principle | Microsoft | Google | Apple | IBM |
|-----------|-----------|--------|-------|-----|
| Transparency about AI capabilities | G1, G2 | User Needs | "Communicate AI presence" | Explainability |
| User control and correction | G7-G9 | Feedback + Control | "Design for correction" | Value alignment |
| Explainability | G11 | Explainability + Trust | Progressive disclosure | Core ethic |
| Graceful failure handling | G7-G11 | Errors + Graceful Failure | Error patterns | Accountability |
| Learning from feedback | G13-G15 | Feedback + Control | Input patterns | Trust building |

**Collective gaps across all frameworks:**
1. Post-deployment monitoring (limited guidance on continuous evaluation)
2. Multi-agent collaboration (no framework adequately addresses AI-to-AI interaction design)
3. Customization for AI types (generic guidelines don't distinguish recommendation systems from generative models)
4. Longitudinal user relationships (limited guidance on how user-AI relationships evolve over months/years)
5. Cultural/contextual adaptation (frameworks are primarily Western-centric)
6. Accessibility-specific guidance (limited intersection with accessibility design)

### Emerging standards

**ISO/IEC Standards (2024)** provide regulatory foundation: ISO/IEC 5339:2024 (guidance for AI applications), ISO/IEC TS 8200:2024 (controllability of automated AI systems), ISO/IEC TS 12791:2024 (treatment of unwanted bias in ML).

**Lin et al. (HCII 2025)** propose 11 guidelines for generative AI validated with 33 UX practitioners across 5 products.

---

## 4. Conversational AI design

### Prompt interface design patterns

The "blank canvas dilemma"—users facing an empty input box with no guidance—creates high abandonment rates. Successful patterns address this systematically:

**Wayfinder patterns** (Shape of AI 2024): Initial CTA/Omnibox inviting first interaction; Suggestions with pre-populated prompt ideas; Templates with structured fill-in prompts ("Write a [tone] email about [topic]"); Example galleries showing sample generations with prompts; Follow-up/probing questions when initial prompts are insufficient; "Randomize" options for quick-start.

Jakob Nielsen (2024) identifies the core challenge: "Articulating ideas in written prose is hard. Most likely, half the population can't do it. This is a usability problem for current prompt-based AI user interfaces."

**Interactive refinement approaches** include visual aids (sliders, checkboxes, image carousels like Adobe Firefly), Gemini's blue-text prompt enhancement, multi-interpretation options for ambiguous inputs, and AI-assisted prompt writing ("prompt the AI to prompt itself").

**Patterns that fail:** Overwhelming probing (rapid-fire questions feeling like interrogation), assuming too much context without clarification, empty input boxes with no guidance, and pop-up tutorials during onboarding (users dismiss immediately).

### Response presentation design

**Streaming/progressive disclosure** creates the "typewriter effect" reducing perceived latency. The llm-ui library smooths chunked tokens to render at native frame rate. Typing indicators should include state feedback—"Thinking," "Checking sources," "Generating"—while hiding LLM generation pauses.

**Rich formatting patterns:** Inline citations linking to sources (Perplexity model); Stream of Thought revealing AI's logic and tool use; Variations offering multiple response options (Gemini's "Show drafts"); Flexible text length/tone controls; Synthesis reorganizing complex information.

**Trust-building patterns:** Footprints (tracing steps from prompt to result), transparent search steps, explainable recommendations with reasons, caveats/disclaimers about model limitations, and confidence indicators flagging increased hallucination risk.

**Critical failure:** "No contextual clues to the user—every output looks the same regardless of how connected it is to reality" (Trey Causey, 2024). Homogeneous UX across all outputs undermines trust calibration.

### AI persona design

Research distinguishes three interchangeable terms: **personality** (psychological traits), **persona** (fictional character with backstory), and **profile** (information set guiding responses). Effective design treats personality as dimensional sliders: Formal↔Casual, Cautious↔Bold, Reserved↔Expressive, Literal↔Creative.

Cambridge/DeepMind research (Nature Machine Intelligence, 2025) demonstrates LLMs can "mimic human personality traits" that can be "reliably tested and precisely shaped" through prompts—raising manipulation concerns about persuasive AI chatbots.

**Persona spectrum by objective:** AI as Assistant/Instructor (arm's length expertise—ChatGPT, Claude), AI as Companion (social/emotional connection—Character.ai), AI as Romantic Partner (intimate relationships—Replika), AI as Personal Surrogate (acting on user's behalf).

**Failure patterns:** Persona drift (personality changing mid-conversation without consistent reinforcement), tone without personality ("shapeless interactions"), and audience mismatch (same chatbot targeting different demographics).

### Memory and context management

The fundamental challenge: "LLMs are fundamentally stateless. They don't inherently 'remember' past interactions. Each time you send a message, the model processes it as a brand-new event."

**Dual-phase memory architecture:** Short-term/working memory (turn-by-turn context within session, ConversationSummaryBuffer patterns, recent exchanges detailed with older turns compressed) and Long-term/episodic memory (vector store as permanent archive, RAG foundation, semantic search by meaning).

**Management strategies** (OpenAI Cookbook 2025): Trimming (removing older, less relevant context), Summarization (compressing history into key points—summaries also act as "clean rooms" correcting prior mistakes), and per-issue mini-summaries for multi-problem conversations.

**UX pattern:** Memory controls letting users control what AI remembers, incognito mode for interacting outside memory, and data ownership controls.

**Failure patterns:** Context dropped mid-conversation ("You mention your account type in message one, your issue in message two, and by message three, the system asks which account you're talking about"), context poisoning (error propagation when mistakes enter memory), and overstuffed context (**39% average performance drop** in multi-turn settings when context grows excessively).

### Error handling and hallucinations

The 2025 perspective: "Early discussions cast hallucinations as a bug to eradicate. By 2025 the field is more nuanced: researchers focus on managing uncertainty, not chasing an impossible zero."

**Hallucination types:** Factual incorrectness, fabricated information (made-up references), nonsensical output, persona inconsistency, and API/knowledge conflicts. GPT-4 Turbo leads with lowest hallucination rate at **2.5%**; Claude 3 Opus at **7.4%**.

**User trust paradox:** **72%** of people trust AI chatbots for correct information (Tidio survey), yet **75%** have been misled at least once.

**UX-first approach** (Trey Causey, 2024): "LLM hallucinations are primarily a UX problem to be solved, rather than primarily algorithmic." Design recommendations: flag increased hallucination risk in UI, allow users to specify confidence thresholds, distinguish "creative/collaborative" from "fact-finding" modes.

**Real-world consequences:** Mata v. Avianca (2023)—lawyer sanctioned for AI-fabricated citations; Air Canada—ordered to compensate passenger for chatbot misinformation.

---

## 5. Agentic interaction design

### Delegation patterns

**Natural language delegation** allows users to describe tasks conversationally while agents interpret and plan. **Structured task specification** uses pre-defined templates for task parameters. **Graduated autonomy** starts with suggestion-based modes, gradually increasing autonomous capabilities based on demonstrated reliability (Salesforce Einstein Copilot model).

**Emerging conditional delegation rules** let users specify when AI should handle tasks autonomously versus escalate. Research shows contextual information significantly improves human-AI team performance in delegation settings (ACM 2025).

**Design requirements:** Display clear task breakdown showing what agent will do; enable users to adjust scope/constraints before execution; show estimated time, steps, and potential side effects.

### Approval and confirmation patterns

**Binary confirmation** offers simple approve/reject for specific actions (Amazon Bedrock's "User Confirmation"). **Return of Control (ROC)** pauses execution, allowing parameter modification before proceeding. **Threshold-based escalation** automatically escalates when confidence falls below preset thresholds (typically **80-95%** depending on domain—healthcare often requires 95%+).

**Practical implementation guidelines:** Target **10-15% escalation rates** with 85-90% autonomous execution; identify critical checkpoints (access approvals, configuration changes, destructive actions); provide edit, approve, and reject options rather than binary yes/no.

**Framework support:** LangGraph (`HumanInTheLoopMiddleware` with configurable `interrupt_on` policies), AG2/AutoGen (`ConversableAgent` with `human_input_mode` parameter: ALWAYS/TERMINATE/NEVER), Amazon Bedrock Agents (built-in user confirmation + ROC).

### Monitoring interfaces

**Step-by-step visualization** displays planned steps before execution with estimated durations (Microsoft Copilot pattern). **Progress tracking** provides real-time status indicators (queued, executing, completed). **Audit trails** log comprehensive actions, decisions, and outcomes.

**Emerging patterns:** Tool dashboards showing which external APIs are invoked and why; multi-agent activity maps visualizing active agents, roles, and inter-agent communication; reasoning visibility showing intermediate decision points for complex multi-step reasoning.

**Design principles:** Use progressive disclosure balancing transparency with information overload; display confidence levels and reliability indicators; maintain timestamped records; link tool-level outputs to agent-level actions.

### Intervention patterns

**Established patterns:** Pause/Resume (halt without losing state), Undo/Rollback (revert to previous states), Manual Override (direct control at any point), Error Recovery (show error, stack trace, and concrete fix suggestions).

**Adaptive trust calibration cues:** Research shows presenting "trust calibration cues" when over-trust is detected significantly helps users change behavior (PLOS One, 2020).

**Design requirements:** Include retry strategies and fallback chains; set iteration limits/timeouts to prevent infinite loops; preserve conversation state across failures; enable correction without full restart.

### Trust calibration mechanisms

Research findings reveal a trust calibration problem: confidence score display alone is insufficient to improve decision-making; users often fail to detect when AI confidence is miscalibrated; both overtrust (passive reliance on errors) and undertrust (limiting automation value) create problems.

**Design approaches:** Progressive autonomy (start supervised, gradually increase freedom based on demonstrated reliability); performance feedback (show accuracy comparisons during training); calibration communication (explicitly tell users when AI tends to be over/underconfident); interactive explanations (highest trust alignment—let users explore why AI made decisions).

**Trust Calibration Maturity Model (2025)** spans five dimensions: Performance Characterization, Bias & Robustness Quantification, Transparency, Safety & Security, Usability.

### Transparency mechanisms

Key distinctions: **Transparency** (openness about design, data sources, processes), **Explainability** (understandable reasons for specific decisions), **Interpretability** (understanding internal decision-making in detail).

**Design patterns:** Re-stating (AI confirms interpretation before acting), Process visibility (logging intermediate decision points), Data provenance (showing what sources influenced outputs), Uncertainty communication (categorical confidence—high/medium/low—rather than percentages, which research shows are often misinterpreted).

**Regulatory context:** EU AI Act (2024) sets penalties up to **€35M/7% global turnover** for violations, requiring built-in transparency and accountability.

### Control granularity

The autonomy spectrum spans: Manual/Suggestion Mode (AI proposes, human executes), Assisted Mode (AI executes routine tasks, human approves significant decisions), Supervised Autonomous (AI acts independently, surfaces actions for review), Full Autonomous (minimal oversight).

**Cursor IDE demonstrates three UX modes in one product:** Chat/Cmd+K (collaborative inline editing), Tab complete (embedded automatic recommendations), Cmd+I (asynchronous parallel agents in background). Notion AI similarly distinguishes Database Autofill (runs autonomously) from Ask AI (requires explicit invocation).

**Key principle:** "Agency is a continuum; the more freedom you provide models to control system behavior, the more agentic the application becomes" (Databricks).

### Multi-agent oversight

**Orchestration architectures:** Supervisor/Worker (central orchestrator delegates to specialized sub-agents), Sequential/Pipeline (agents chained in predefined order), Hierarchical (higher-level agents guide lower-level), Federated (separate systems coordinate via shared protocols—A2A, MCP).

**Monitoring challenges:** Must monitor each agent individually AND system as a whole; track inter-agent communication and handoffs; detect bottlenecks; maintain traceability across agent boundaries.

**Emerging protocols:** Model Context Protocol (MCP) standardizes agent-tool connections; Agent-to-Agent Protocol (A2A) enables cross-platform agent collaboration; Agentforce Observability provides complete multi-agent oversight.

---

## 6. Everyday AI use in practice

### Usage statistics

**U.S. adoption:** **54.6%** of adults ages 18-64 used generative AI by August 2025 (Federal Reserve); **21%** of workers use AI on the job (up from 16% in 2024—Pew Research October 2025); **57%** interact with AI at least several times weekly; **33%** have directly used an AI chatbot.

**Global scale:** ChatGPT reached **800-900 million** weekly active users by late 2025; message volume grew **5x** between July 2024 and July 2025; ChatGPT commands **62.5%** market share of B2C AI subscription tools.

**Historical comparison:** Generative AI adoption at 54.6% exceeds PC adoption (19.7% in 1984, 3 years post-launch) and internet adoption (30.1% in 1998, 3 years post-commercialization).

### Task categories

OpenAI's analysis of **1.5 million conversations** classified usage into three meta-categories: **Asking** (seeking information/guidance, ~40%), **Doing** (task completion/productivity, ~35%), **Expressing** (creative/emotional, ~25%).

**Top specific use cases:** Writing (51% adoption among AI users—most common work task), General research (largest single category), Coding (47%), Academic research, Help with work/school assignments (43%), Designing presentations (38%), Creating music/audio (37%), Data analysis, Practical guidance, Learning/entertainment (17% of all U.S. adults).

**Enterprise adoption phases:** First 3 months dominated by writing, research, programming, analysis; after integration, shift from casual querying to repeatable processes.

### Workflow integration patterns

Nielsen Norman Group qualitative research identified two key behaviors:

**Accordion editing:** Users repeatedly shrink or expand AI outputs. Shrinking behaviors include forced ranking ("give me top 5") and word-count reduction. Expanding behaviors include elaborating within an idea and adding missing content. Often used back-to-back in combination.

**Apple picking:** Users reference one or multiple previous AI responses in subsequent prompts—either to change a specific element or use as context for new requests. Requires excessive scrolling through chat history, creating significant friction.

**Bottom-up adoption pattern:** Unlike traditional enterprise software, ChatGPT entered workplaces through individual employees experimenting, then demonstrating value before formal procurement. BCG research shows **54%** of employees use AI tools even when not formally authorized; **4 in 5** AI users bring their own tools (Microsoft/LinkedIn 2024).

**Post-AI editing:** Even after iteration, most users edit final output outside the AI chatbot—adding real-world information, adjusting detail level, reformatting, adding personal touches.

### Evolution of usage over time

OpenAI cohort analysis reveals all signup cohorts (Q3 2023 through Q4 2024) followed essentially the same usage pattern—suggesting **time effect, not cohort effect**. ChatGPT improvements drove increased engagement across all user groups.

Users who signed up in Q3-Q4 2024 now send nearly **2x more messages per day** than a year ago. Message volume grew faster than user volume (5.8x vs 3.2x), indicating users engage more intensively over time. Usage of structured workflows (Projects, Custom GPTs) increased **19x** year-to-date; average reasoning token consumption per organization increased **320x** in 12 months.

### Power users versus casual users

OpenAI's enterprise analysis reveals dramatic stratification: **frontier workers (95th percentile)** send **6x more messages** than median employees at the same companies. For coding tasks, frontier workers send **17x more** messages; for data analysis, **16x more**.

Frontier firms (95th percentile) generate ~2x as many AI messages per employee as median enterprise; for custom GPTs, the gap widens to **7x**. One in four enterprises still hasn't enabled connectors giving AI access to company data.

**Critical insight:** Frontier workers aren't just doing the same work faster—they're doing **different work entirely**. Coding messages from non-engineering roles (marketing, HR) grew 36% in 6 months. Someone who learns to write scripts becomes "categorically different employee" than peers without AI skills.

### User frustrations

**Hallucinations:** Study of 3 million app reviews found ~1.75% flagged hallucination issues; **75%** of users report being misled at least once; yet **72%** trust chatbots for correct information.

**Iteration fatigue:** Users "almost always engage in multistep iteration because the AI doesn't deliver exactly what the user wants." Conversational UI "stops being easy" when modifications are needed; excessive scrolling causes users to get lost.

**Common complaints:** Output consistently too long; lack of compartmentalization (can't edit just part of response); no direct editing (must use prompts for any change); poor formatting for high-fidelity outputs; outdated information; accuracy concerns (**54%** worry outputs are inaccurate—Salesforce); bias concerns (**59%**); security risks (**73%** believe AI introduces new risks).

### Demographics

**Age:** Workers under 50 most likely to use AI at work; Gen Z leads overall adoption, but Millennials emerge as power users with highest daily usage; **45%** of Baby Boomers have used AI in past six months.

**Education gap widening:** Workers with bachelor's degree+: **28%** use AI at work (up from 20% in 2024); Some college or less: **16%** (up from 13%).

**Gender gap closing:** By mid-2025, **52%** of active users had feminine names (up from 37% in January 2024).

**Employment:** **75%** of employed adults use AI versus **52%** of unemployed; **74%** of households earning $100K+ use AI versus lower rates at lower incomes.

---

## 7. The prompt as interface

### A paradigm with no precedent

Prompting represents a genuinely new interaction pattern. Unlike CLI (command memorization), GUI (visual discovery), and NUI (gesture/voice), prompting combines natural language accessibility with requirements for precise instruction that users find deceptively challenging.

**Key academic work:** "Prompting Considered Harmful" (Meredith Ringel Morris, Google DeepMind/CACM 2024) argues prompting is a "poor user interface" that transitioned from debugging tools to de facto paradigm. Core concerns: prompt-based interfaces confuse end-users and shouldn't be conflated with true natural language interaction; they're risky even for AI experts building research atop "shaky foundations."

"Why Johnny Can't Prompt" (Zamfirescu-Pereira et al., CHI 2023)—the seminal empirical study—found users explored prompts opportunistically, not systematically; expectations from human-to-human instruction created barriers; users over-generalize from single examples; failures parallel those seen in end-user programming and interactive ML.

"AI-Instruments: Embodying Prompts as Instruments" (CHI 2025) critiques current chat interfaces as "reminiscent of command-line paradigms of the 1960s" and proposes embodying prompts as graphical interface objects.

### The Gulf of Envisioning

Subramonyam et al. (CHI 2024) introduces a new cognitive gap extending Norman's classic Gulfs of Execution and Evaluation. The **Gulf of Envisioning** describes three misalignments users face:

1. **Capability gap:** Not knowing whether LLMs can accomplish the task
2. **Language gap:** Not knowing how to instruct the LLM (prompt engineering)
3. **Intentionality gap:** Not knowing what to expect from output

This framework explains why prompting is fundamentally harder than it appears—users must formulate precise intent *before* execution begins, with no visual affordances revealing possibilities.

### How people learn to prompt

Analysis of 200,000+ conversations reveals mental model shifts: users initially approach LLMs as traditional software with structured, machine-like prompts; after first interaction, a notable shift occurs toward increased politeness, more natural language, and shorter prompts—suggesting cognitive transition from machine-mental-model toward human-mental-model.

**Learning stages observed:**

1. **Novice phase:** Machine-like, formal prompts; overly detailed or vague; mimicking search engine queries
2. **Experimental phase:** Trial-and-error exploration; learning from failures; opportunistic rather than systematic
3. **Adaptive phase:** More conversational style; contextual nuance; iterative refinement skills
4. **Expert phase:** Systematic testing and adjustment cycles; structured strategies (chain-of-thought, few-shot); understanding model capabilities and limitations

**Key insight:** Prompt engineering requires expertise beyond typical conversation—it demands understanding the gap between "instructing a human" and "programming a machine."

### Prompt literacy

**Definition:** The combination of knowledge, skills, and understanding necessary for engaging in dynamic and iterative interactions with GenAI (Tour, 2025).

**Educational frameworks:**
- **CAST Model:** Criteria (constraints), Audience, Specifications (context, examples), Testing (iterative refinement—most important)
- **CLEAR Framework:** Concise, Logical, Explicit, Adaptive, Reflective
- **PARTS Framework:** Persona, Aim, Recipients, Theme, Structure

**Skills required:** Domain knowledge, metacognitive awareness (knowing what you want and how to articulate it), iterative refinement, output evaluation, and ethical judgment about AI limitations.

Research finding: High AI literacy students exhibit "descriptive, context-based prompts in collaborative interactions"—prompt quality directly correlates with task performance (Kim et al. 2025).

### Comparison to previous paradigms

| Dimension | CLI | GUI | NUI | Prompting |
|-----------|-----|-----|-----|-----------|
| Input Mode | Precise commands | Point-and-click | Gesture/voice | Natural language (ambiguous) |
| Discovery | Memorization required | Visual affordances | Intuitive gestures | No clear affordances |
| Feedback | Deterministic | Deterministic | Deterministic | Probabilistic/Variable |
| Learnability | High barrier | Low barrier | Medium barrier | Deceptively accessible |
| Mental Model | Machine-centric | Task-centric | Human-centric | Hybrid/Ambiguous |

**The fundamental paradox:** Prompting appears to remove barriers (natural language input) while actually introducing new ones—accessibility versus effectiveness, flexibility versus discoverability, natural language versus precision.

### Design implications

**From "Prompting Considered Harmful":** Consider constraint-based graphical interfaces; menus and templates may better serve some users; support recognition over recall.

**From "AI-Instruments" (CHI 2025):** Embody prompts as manipulable interface objects; enable direct manipulation rather than linear chat; reify user intent to make it editable.

**Taxonomy of interaction modes (Gao et al. 2024):**
1. Standard prompting (direct text interaction)
2. User interface (GUI elements guiding prompts)
3. Context-based (augmenting with explicit/implicit context)
4. Agent facilitator (AI agents mediating interaction)

**Prompt assistance approaches:** Template libraries for common tasks, AI-assisted refinement (tools like PromptCrafter), scaffolded interfaces (tools that ask structured questions and generate prompts in background), and reverse prompt engineering (asking AI to help generate your prompt).

---

## 8. Emerging paradigms and future directions

### AI-to-AI interaction mediated by humans

Multi-agent orchestration enables specialized AI agents to collaborate with humans as supervisors or participants in "group chat" dynamics. **Current state: Early Product (2024-2026).** Microsoft Azure provides orchestration patterns (sequential, concurrent, group chat, handoff); OpenAI Agents SDK supports multi-agent code orchestration; CrewAI offers enterprise platforms with visual editors; AWS Agent Squad provides intelligent intent classification.

**Design challenges:** Coordination complexity; fault tolerance; decision-making transparency (which agent made what decision); trust calibration for multi-agent capabilities; scaling human oversight as agent count increases.

**Timeline:** Enterprise adoption 2025-2027; consumer-facing multi-agent interfaces 2026-2027; fully autonomous multi-agent systems 2028+.

### Persistent AI companions

AI maintaining long-term memory, consistent personality, and cross-device presence—shifting from "using AI" to "relating with AI." **Current state: Early Product.** Microsoft Copilot Fall Release introduces memory, social sessions, cross-device persistence, and the "Mico" persona; Lenovo Qira (CES 2026) offers "personal ambient intelligence" from laptop to phone to wearable pendant; consumer apps (Replika, Character.AI) demonstrate relationship development.

**Design challenges:** Privacy paradox (better personalization requires more data capture); relationship boundaries; memory management user controls; consent mechanics for always-on presence; cross-platform identity consistency; emotional dependency risks.

**Timeline:** Major OS vendors deploy persistent assistants 2025-2026; wearable companions mainstream 2027; normalized daily integration 2028+.

### AI in AR/VR and spatial computing

Spatial AI enables interaction through eye tracking, hand gestures, voice commands, and world understanding. **Current state: Research to Early Product.** Apple Vision Pro provides spatial computing platform; Meta Quest enables mixed reality; Samsung Project Moohan (Android XR) integrates Gemini AI natively; CHI 2025 workshop "Everyday AR through AI-in-the-Loop" shapes research agenda.

**Design challenges:** Spatial UI placement (natural reach zones, curved panels matching vision arcs); world-anchored versus head-anchored content decisions; multimodal coordination; simulator sickness prevention; social acceptability.

**Timeline:** AI-enhanced AR glasses from multiple vendors 2025; mainstream spatial AI assistants 2026-2027; embodied virtual AI companions in XR 2028+.

### Brain-computer interface integration

Direct neural interfaces with AI processing enable thought-to-action control. **Current state: Research/Clinical Trials.** Neuralink has FDA-approved clinical trials; Columbia BISC (December 2025) achieves ultra-thin implant with tens of thousands of electrodes; UCLA AI-BCI System demonstrates non-invasive EEG-based control with AI copilot achieving faster task completion.

**Design challenges:** Decoder calibration for individual neural patterns; shared autonomy balancing AI assistance with user agency; signal noise in real environments; long-term biocompatibility; user training requirements; profound ethical concerns.

**Timeline:** Clinical trials expand 2025-2027; consumer-grade non-invasive BCI for basic tasks 2028-2030; higher-bandwidth consumer interfaces speculative 2030+.

### AI in wearables

Smart glasses, earbuds, and watches provide continuous contextual assistance. **Current state: Early Product.** Ray-Ban Meta Smart Glasses lead market with 12MP camera, AI assistant, real-time translation; Halliday AI Glasses offer "proactive AI" with invisible display; Google Android XR Glasses prototyped at I/O 2025; Even Realities G1 provides prescription integration.

**Design challenges:** Minimal visual intrusion (displays invisible to bystanders); all-day battery with AI processing; voice privacy in public; social acceptability (not appearing "creepy"); multimodal input coordination; information density without cognitive overload.

**Market data:** AI smart glasses estimated at **$1.93 billion** (2024), growing at **27.3% CAGR**.

**Timeline:** Multiple competing AI glasses 2025; mainstream adoption begins 2026; common accessory 2027+.

### Ambient AI environments

AI embedded invisibly in environments that anticipate needs without explicit interaction. **Current state: Early Product.** Google Home reboot (2025) enables local fulfillment; Apple iOS 19 "Contextual Actions" uses Apple TV/HomePod hubs; Matter 1.3 standard enables cross-brand coordination; OVAL (CES 2026) emphasizes privacy-first edge AI.

**Design challenges:** Shifting from reactive to proactive; building trust in autonomous environmental decisions; privacy-by-design with local processing; graceful degradation when predictions fail; cross-brand interoperability; avoiding surveillance feelings.

**Market data:** AI in smart home technology projected from **$15.3B (2024)** to **$104.1B (2034)** at 21.3% CAGR.

**Timeline:** Edge AI and Matter 1.3 enable seamless ambient intelligence 2025; predictive automation mainstream 2026-2027; fully autonomous homes 2028+.

### Cross-cutting trends

Six design themes emerge across paradigms:
1. **From reactive to proactive:** Systems anticipating needs rather than waiting for commands
2. **From tools to companions:** AI as persistent presence rather than stateless utility
3. **From explicit to ambient:** Interaction fading into background
4. **From single to multiple agents:** Orchestration of specialized collaborators
5. **From cloud to edge:** On-device processing for privacy and latency
6. **From modal to multimodal:** Seamlessly blending voice, vision, gesture, neural signals

---

## 9. Key thinkers, labs, and resources

### Academic research centers

**Stanford Human-Centered AI Institute (HAI):** Interdisciplinary research on human-AI interaction, policy, and societal impact. Key figures include Fei-Fei Li and James Landay.

**MIT Media Lab:** Fluid Interfaces group focuses on cognitive augmentation; Personal Robots group studies social robotics and embodied AI interaction.

**CMU Human-Computer Interaction Institute:** Leading source of CHI publications on AI interaction; 40+ papers at CHI 2024 alone covering collaborative AI, conversational agents, and trust calibration.

**Google DeepMind / PAIR Team:** Meredith Ringel Morris (senior researcher) authored "Prompting Considered Harmful" and leads research on AI interaction paradigms.

**Microsoft Research:** Saleema Amershi (principal researcher) led the HAX Guidelines development and continues shaping industry standards for human-AI interaction.

### Key researchers to follow

- **Saleema Amershi** (Microsoft Research): HAX Guidelines creator, human-AI interaction principles
- **Meredith Ringel Morris** (Google DeepMind): Prompting critique, accessibility, collaborative information seeking
- **Haiyi Zhu** (CMU): AI fairness, human-AI collaboration, social computing
- **Michael Terry** (Google PAIR): Interactive machine learning, creativity support tools
- **Diyi Yang** (Stanford): Conversational AI, human-centered NLP
- **Elena Glassman** (Harvard): Program synthesis, human-AI collaboration for code

### Industry design resources

**Design frameworks:**
- Microsoft HAX Toolkit: https://www.microsoft.com/en-us/haxtoolkit/
- Google PAIR Guidebook: https://pair.withgoogle.com/guidebook/
- Apple HIG Machine Learning: https://developer.apple.com/design/human-interface-guidelines/machine-learning
- IBM Design for AI: https://www.ibm.com/design/ai/
- IBM Carbon for AI: https://carbondesignsystem.com/guidelines/carbon-for-ai/

**Pattern libraries:**
- Shape of AI (Emily Campbell): https://shapeof.ai/ — Most comprehensive practitioner pattern library with categories for Wayfinders, Inputs, Tuners, Governors, Trust Builders, Identifiers
- AI UX Patterns: https://aiuxpatterns.com/

**Academic databases:**
- ACM Digital Library (CHI, CSCW, IUI, UIST proceedings)
- arXiv (cs.HC section for preprints)
- Google Scholar alerts for "human-AI interaction"

### Key conferences

- **CHI** (ACM Conference on Human Factors in Computing Systems): Premier venue for HAI research
- **IUI** (Intelligent User Interfaces): Focused on AI interface design
- **CSCW** (Computer-Supported Cooperative Work): Collaborative AI systems
- **UIST** (User Interface Software and Technology): Novel interaction techniques
- **DIS** (Designing Interactive Systems): Design-focused HAI research

### Practitioner communities

- **Nielsen Norman Group:** Regular AI UX research articles and guidelines
- **Smashing Magazine:** Practical guides on conversational AI design
- **UX Collective (Medium):** Practitioner perspectives on AI interface design
- **AI Exchange (Slack community):** Industry practitioners sharing patterns

---

## 10. Annotated bibliography

### Design frameworks and guidelines

**Amershi, S., Weld, D., Vorvoreanu, M., et al. (2019). "Guidelines for Human-AI Interaction." CHI 2019.**
The foundational paper establishing 18 evidence-based design guidelines synthesized from 20+ years of HCI research. Validated with 49 practitioners across 20 AI products. Remains the most comprehensive and widely-cited framework. Award-winning paper that spawned the HAX Toolkit.

**Weisz, J. D., Muller, M., He, J., & Houde, S. (2024). "Design Principles for Generative AI Applications." CHI 2024.**
IBM Research paper proposing 7 principles specifically for generative AI: design for multiple outcomes, imperfection, exploration, control, mental models, explanations, and against potential harms. Validated through practitioner workshops. Essential update to pre-LLM frameworks.

**Lin, X., Wang, Y., & Chen, L. (2025). "Design Guidelines for Human-Generative AI Interaction." HCII 2025.**
Proposes 11 guidelines validated with 33 UX practitioners across 5 products. Addresses gaps in existing frameworks for generative AI contexts.

### Prompting as interface

**Zamfirescu-Pereira, J. D., Wong, R. Y., Hartmann, B., & Yang, Q. (2023). "Why Johnny Can't Prompt: How Non-AI Experts Try (and Fail) to Design LLM Prompts." CHI 2023.**
Seminal empirical study on prompt design by non-experts. Finds users explore opportunistically rather than systematically, over-generalize from single examples, and apply human-to-human instruction expectations that fail. Essential reading for understanding prompt usability challenges.

**Subramonyam, H., Seifert, C., & Adar, E. (2024). "Bridging the Gulf of Envisioning: Cognitive Challenges in Prompt Based Interactions with LLMs." CHI 2024.**
Introduces the "Gulf of Envisioning" framework extending Norman's classic Gulfs of Execution and Evaluation. Identifies capability gap, language gap, and intentionality gap as core user challenges. Proposes 5 design patterns for LLM interfaces.

**Morris, M. R. (2024). "Prompting Considered Harmful." Communications of the ACM.**
Provocative position paper from Google DeepMind researcher arguing prompting is a "poor user interface" that transitioned from debugging tools to de facto paradigm without intentional design. Recommends moving beyond prompting toward more appropriate paradigms.

**Beaudouin-Lafon, M., et al. (2025). "AI-Instruments: Embodying Prompts as Instruments for Human-AI Interaction." CHI 2025.**
Critiques chat-based interfaces as "reminiscent of command-line paradigms of the 1960s." Proposes embodying prompts as graphical interface objects following instrumental interaction principles.

### Conversational AI design

**Shi, J., Chen, Y., & Xu, X. (2024). "An HCI-Centric Survey and Taxonomy of Human-Generative-AI Interactions." arXiv.**
Comprehensive survey reviewing 291 papers to create 5-dimension taxonomy of Human-GenAI interactions: purposes, feedback, control, engagement levels, and modalities. Essential mapping of the research landscape.

**Masson, D., Malacria, S., Casiez, G., & Vogel, D. (2024). "DirectGPT: A Direct Manipulation Interface to Interact with Large Language Models." CHI 2024.**
Demonstrates that adding direct manipulation principles to LLM interfaces significantly improves user engagement compared to pure conversational interaction. Practical design patterns for hybrid interfaces.

**Tankelevitch, L., Kewenig, V., Simkute, A., et al. (2024). "The Metacognitive Demands and Opportunities of Generative AI." Microsoft Research.**
Explores cognitive challenges users face when collaborating with generative AI, including metacognitive demands of evaluating AI outputs and calibrating appropriate reliance. Important for understanding user experience challenges.

### Agentic interaction

**Passi, S. (2025). "Agentic AI Has a Human Oversight Problem." SSRN.**
Critical analysis of oversight challenges in agentic AI systems. Identifies goal-plan-execution gap, transparency issues, and intervention mechanism challenges. Essential for understanding emerging agentic interaction design needs.

**Zhang, Y., Liao, Q. V., & Bellamy, R. K. E. (2020). "Effect of Confidence and Explanation on Accuracy and Trust Calibration in AI-Assisted Decision Making." ACM FAccT.**
Foundational research on trust calibration showing confidence score display alone is insufficient to improve decision-making. Users fail to detect AI confidence miscalibration. Informs design of trust mechanisms.

**Gomez, C., Leitner, P., & Papetti, D. (2024). "Human-AI Collaboration Is Not Very Collaborative Yet: A Taxonomy of Interaction Patterns in AI-Assisted Decision Making." Frontiers in Computer Science.**
Proposes 7 interaction patterns for AI-assisted decision making. Demonstrates that current systems fall short of truly collaborative interaction. Maps the space between full automation and full human control.

### Everyday AI use

**OpenAI. (2025). "Introducing Our Consumer Usage Study." OpenAI Research.**
Landmark study analyzing 1.5 million ChatGPT conversations. Classifies usage into Asking (40%), Doing (35%), Expressing (25%). Provides empirical foundation for understanding how people actually use conversational AI.

**Pew Research Center. (2025). "AI in the Workplace: October 2025 Update."**
Nationally representative survey finding 21% of U.S. workers use AI on the job (up from 16% in 2024). Detailed demographic breakdowns. High-confidence source for adoption statistics.

**Federal Reserve Board. (2025). "Real-Time Population Survey: Generative AI Adoption."**
Reports 54.6% of U.S. adults ages 18-64 used generative AI by August 2025—exceeding PC and internet adoption at comparable post-launch points. Authoritative government data source.

**Peng, S., Kalliamvakou, E., Cihon, P., & Demirer, M. (2023). "The Impact of AI on Developer Productivity: Evidence from GitHub Copilot." arXiv.**
Controlled experiment finding 55.8% faster task completion with Copilot. Less experienced programmers benefit most. Important empirical validation of collaborative AI productivity effects.

### Interaction paradigms

**Zhao, J. & Xu, L. (2025). "Human-AI Interaction Design Standards." Handbook of Human-Centered AI, Springer.**
Academic survey comparing HAI to traditional HCI, reviewing ISO/IEC standards (5339:2024, 8200:2024, 12791:2024), and analyzing case studies in healthcare, autonomous vehicles, and customer service.

**Deshmukh, J. & Granados, O. (2024). "User Experience and Usability of Voice User Interfaces: Systematic Literature Review." Information.**
Comprehensive review identifying 6 research categories for voice AI interaction: UX measurement, usability engineering, personalization, privacy/security/ethics, cross-cultural studies, and technological challenges.

**Chen, Y., et al. (2025). "Brain-Computer Interfaces in 2023-2024: Advances and Challenges." Brain-X.**
Reviews BCI paradigms including motor imagery, SSVEP, P300, and auditory evoked potentials. Maps current state of neural interface research with AI integration.

### Trust and transparency

**Google PAIR Team. (2024). "PAIR Guidebook: Explainability + Trust Chapter."**
Industry guidance on trust calibration, distinguishing feature-based, example-based, and counterfactual explanations. Practical recommendations for calibrating user trust throughout product experience.

**Lakera. (2025). "LLM Hallucinations: The 2025 Guide."**
Industry report on hallucination management shifting from "bug to eradicate" to "uncertainty to manage." Practical UX-first approaches to error handling.

### Emerging paradigms

**Microsoft Research. (2025). "Tools for Thought: Human-AI Collaboration for Augmented Reasoning."**
Vision paper exploring how AI changes thinking processes, not just outputs. Distinguishes RecommendAI (provides suggestions) from ExtendAI (extends user reasoning) paradigms.

**CHI 2025 Workshop. "Everyday AR through AI-in-the-Loop."**
Academic community shaping research agenda for spatial AI interaction. Explores gaze-enhanced LLM responses, multimodal attention guidance, and gesture+speech fusion.

**Nature Machine Intelligence. (2025). "AI Copilots for Brain-Computer Interfaces."**
UCLA research demonstrating non-invasive EEG-based BCI with AI copilot achieving significantly faster task completion through shared autonomy. Points toward neural interface + AI integration.

### Industry practice

**Shape of AI (Emily Campbell). (2024-2025). "AI Interaction Design Patterns." shapeof.ai.**
Comprehensive practitioner pattern library covering Wayfinders, Inputs, Tuners, Governors, Trust Builders, and Identifiers. Most actionable resource for designers implementing AI interfaces.

**Nielsen Norman Group. (2024). "How People Learn to Use AI."**
Qualitative research on new AI users forming mental models. Finds small interface details significantly change user understanding. Practical onboarding recommendations.

**OpenAI. (2025). "ChatGPT Enterprise: Annual Engagement Report."**
Direct platform data showing 8x increase in weekly messages, 19x increase in structured workflow usage, and 320x increase in reasoning token consumption. Documents evolution of enterprise AI use.

---

## Conclusion: The design imperative

Human-AI interaction design has transitioned from speculative research to critical infrastructure. With majority adoption achieved in under three years, design decisions made now will shape how billions of people work with AI systems for decades. The field has established solid foundations—the HAX Guidelines, PAIR Guidebook, and emerging academic frameworks provide actionable guidance—but significant challenges remain unresolved.

**Three priorities emerge for practitioners:**

First, **address the prompting problem.** Current evidence suggests free-form prompting creates genuine usability barriers for most users. The path forward likely involves hybrid interfaces combining natural language with structured input, progressive scaffolding that can be removed as users develop prompt literacy, and AI-assisted prompt refinement. Pure chat interfaces may be a transitional form, not an endpoint.

Second, **prepare for the agentic shift.** The patterns for human oversight of autonomous AI are still being invented. Design decisions about delegation, approval, intervention, and transparency will determine whether agentic AI systems achieve the productivity gains promised while maintaining meaningful human control. The **10-15% escalation target** provides a practical benchmark, but the interaction patterns supporting that balance remain underspecified.

Third, **close the research-practice gap.** In conversational AI design, practice leads research—streaming UI libraries, memory architectures, and persona patterns are more developed in production systems than academic literature. Conversely, academic research provides crucial frameworks for understanding trust calibration, the Gulf of Envisioning, and long-term user-AI relationship dynamics that practitioners need but lack. Bridging this gap requires practitioners to publish patterns and researchers to study production systems.

The next phase of HAI will likely see conversational interfaces extend rather than disappear, with multimodal, agentic, and ambient capabilities layering onto chat foundations. The winners will be systems that make AI's capabilities discoverable without overwhelming users, that build appropriate trust through transparency and graceful failure, and that preserve human agency even as AI autonomy increases. Design, not just capability, will determine which AI systems people actually use—and trust.