---
type: source
status: evergreen
created: 2026-02-02
modified: 2026-02-02
author: human
confidence: medium
sources: []
publish: false
tags: [type/source, domain/methodology]
summary: Gemini Deep Research landscape map of qualitative and practice-based research methodologies for HAI practitioners. Covers phenomenology, autoethnography, grounded theory, RtD, ethnography, action research. Includes decision framework and venue guide.
---

# The Practitioner's Epistemology: Qualitative Frameworks for Human-AI Interaction

## Metadata
- **Authors:** Gemini Deep Research (prompted by human)
- **Year:** 2026
- **Type:** AI research report
- **Link:** Local (generated via Gemini Deep Research)

## Key Findings
- Six primary qualitative methods mapped to HAI: phenomenology, autoethnography, grounded theory, Research Through Design, ethnography, action research
- Trustworthiness (Guba & Lincoln) as the validity framework for qualitative HAI research: credibility, transferability, dependability, confirmability
- Methodological selection matrix matching question types to methods
- Non-academic researchers regularly publish at CHI, DIS, EPIC, CSCW — the boundary is porous
- Enactivism as emerging theoretical foundation for HAI phenomenology
- Micro-phenomenology (Vermersch's explicitation interview) as method for studying HAI micro-moments

## Key Concepts
- Enactivism / participatory sense-making
- Micro-phenomenology (explicitation interview)
- Somaesthetics (embodied interaction design)
- Third Wave HCI (meaning-making, emotion, values)
- Research Through Design (annotated portfolios, strong concepts)
- Autobiographical design (sample of one, first-person research)
- Trustworthiness criteria (credibility, transferability, dependability, confirmability)
- Methodolatry (method-worship at expense of insight)

## Relevance to HAI
- Directly answers the methodology question: what research methods fit a practitioner-researcher doing phenomenological inquiry into HAI?
- Confirms phenomenology + autoethnography + RtD as the natural method cluster for first-person, design-oriented HAI research
- Identifies venues where non-academic work is welcomed (CHI Case Studies, alt.CHI, DIS, EPIC)
- Enactivism provides theoretical grounding for [[Interaction-Field]]
- Autobiographical design (Section 3.2) maps directly to the Guidance development process

## Questions/Critiques
- Report is breadth-oriented (Gemini's strength) — no single method covered in enough depth to actually execute it
- Some sources are likely snippet-level (the Gemini snippet trap identified in Session 5)
- The "AI coding controversy" section (4.2) takes a conservative position — the collaborative extension mode may be more productive
- How much of the source list is padding vs. genuinely worth reading?

## Connections
- Related: [[Friction-Discernment]], [[Interaction-Field]], [[Intent-Expression-Atrophy]], [[Mechanistic-Interpretability]], [[User-Interpretability]], [[Warm-Transparency]]
- Thinkers surfaced: Varela/Thompson/Rosch (enactivism), Merleau-Ponty (phenomenology), Dourish (embodied interaction), Bødker (Third Wave HCI), Vermersch (micro-phenomenology), Charmaz (constructivist GT), Koskinen (RtD), Guba & Lincoln (trustworthiness)
- Venues: CHI, DIS, EPIC, CSCW, IUI, alt.CHI

---

## Full Report

## **1\. The Qualitative Turn in Algorithmic Experience**

The discipline of Human-Computer Interaction (HCI) is currently navigating a seismic epistemological shift, precipitated by the widespread deployment of probabilistic, generative, and agentic Artificial Intelligence (AI) systems. For decades, the dominant paradigm in HCI—and by extension, in industrial User Experience (UX) research—has been rooted in engineering and cognitive psychology. This tradition prioritized efficiency, error reduction, time-on-task, and statistically significant improvements in usability. However, the emergence of Human-AI Interaction (HAI) as a distinct field has exposed the limitations of purely quantitative metrics. When an interaction involves a non-deterministic agent capable of "hallucination," creative collaboration, or emotional mimicry, an F1 score or a System Usability Scale (SUS) rating fails to capture the profound nuances of the encounter.

For the non-academic practitioner—whether an independent researcher, a design strategist in a boutique studio, or a UX lead in a non-tech enterprise—this shift presents a crisis of method. Traditional A/B testing cannot answer "wicked problems" regarding trust calibration, the erosion of human agency, or the phenomenological "uncanny valley" experienced during prolonged engagement with Large Language Models (LLMs). To understand these phenomena, the field must embrace "thick data"—rich, contextual, and deeply interpretive qualitative evidence that maps the messy reality of human-algorithm assemblages.

This report provides an exhaustive mapping of qualitative and practice-based research methodologies tailored specifically for the HAI practitioner. It moves beyond textbook definitions to offer a decision framework rooted in the practical realities of industry constraints and the high rigor required by top-tier venues like the ACM Conference on Human Factors in Computing Systems (CHI). We argue that for the practitioner, rigor is not about mimicking the sterile conditions of a laboratory, but about "trustworthiness"—the disciplined documentation of how knowledge is constructed in the wild. As AI systems become less like tools and more like partners, methodologies that privilege first-person experience (Phenomenology), iterative making (Research Through Design), and social context (Ethnography) are moving from the margins to the center of the HAI discourse.

---

**2\. Phenomenology: The Lived Experience of the "Black Box"**

Phenomenology is perhaps the most philosophically demanding yet increasingly vital methodology for HAI. It rejects the Cartesian dualism of mind and body, focusing instead on *lived experience* as the primary source of knowledge. In the context of HAI, phenomenology offers a counter-narrative to the "black box" problem. While engineers explain AI through weights, biases, and transformer architectures, phenomenologists explain AI through the texture of the user's encounter.

### **2.1 The "Enactive" Turn and Participatory Sense-Making**

Recent scholarship in HAI has embraced "enactivism," a post-cognitivist perspective arguing that cognition arises through dynamic interaction between an acting organism and its environment.1 In this view, an AI system is not merely processing information; it is a participant in a "participatory sense-making" process. When a user interacts with a Large Language Model (LLM), they are not just retrieving data; they are *enacting* a dialogue where meaning is co-constructed.

A phenomenological study in this tradition might investigate the "felt sense" of agency when an AI suggests a sentence completion. Does the user feel enhanced, extended, or replaced? The analysis would focus on the "micro-dynamics" of this interaction—the subtle shifts in intention and attention that occur when the machine "speaks" back. This approach challenges the information-processing paradigm, which models agents as input-output systems, instead viewing them as autonomous agents enacting their own cognitive domains.1

### **2.2 Micro-Phenomenology: Granularity of Experience**

A rising sub-discipline, micro-phenomenology, uses specific interview techniques to help participants describe brief moments of experience with high granularity.2 This is crucial for studying "glitch" moments in HAI—the split second of confusion when a voice assistant misunderstands a command, or the visceral reaction to a deepfake.

The method, derived from Pierre Vermersch's "explicitation interview," requires the researcher to guide the participant into a state of "evocation," re-living the specific moment rather than theorizing about it. For a practitioner, this means moving beyond general questions like "How did you find the experience?" to specific prompts like, "When the chatbot gave that wrong answer, what was the very first thing you noticed? Was it a thought, a feeling, or a bodily sensation?" This level of detail reveals the pre-reflective structures of trust and distrust that quantitative surveys miss.4

### **2.3 Somaesthetics and Embodied Interaction**

Phenomenology in HCI has strongly influenced "somaesthetics"—the study of the living body as a site of sensory appreciation and creative self-fashioning.6 As AI moves into wearables, health monitors, and ambient computing, the interaction becomes bodily. Research here explores how AI-mediated biofeedback changes a user's relationship with their own physiology.

For example, does an AI-driven stress monitor alienate a user from their own feelings of anxiety, replacing internal sensation with an external score? Somaesthetic design aims to use technology to *heighten* bodily awareness rather than outsource it. Practitioners can use "embodied sketching" or "moving and making strange" techniques to design AI systems that support, rather than suppress, somatic engagement.7 This connects deeply with "Third Wave HCI," which prioritizes meaning-making, emotion, and values over simple efficiency.8

### **2.4 Reception in the Quantitative HCI Community**

Phenomenology faces significant friction in the quantitative-heavy HCI community.9 It is often critiqued for being "subjective," "anecdotal," or non-generalizable. Reviewers accustomed to statistical significance may struggle to evaluate a study based on a sample of three participants, even if the analysis is profound.

However, the tide is turning. The "New Paradigms" discussion 1 and workshops at major conferences like INTERACT 9 highlight that standard metrics are meaningless for evaluating "being-with" technology. To gain legitimacy, practitioner-researchers must:

1. **Operationalize Rigor:** Explicitly describe the *method of analysis* (e.g., the "epoché" or bracketing of assumptions). Show the "receipts" of the reduction process.
2. **Bridge with Mixed Methods:** Use phenomenology to explain the *why* behind a quantitative pattern. "Our logs showed high abandonment at step 3\. Our phenomenological interviews revealed this was due to a sudden feeling of 'surveillance' triggered by the wording."
3. **Focus on Implications:** Connect the lived experience back to design. A purely philosophical essay may be rejected; a phenomenological study that results in "Design Implications for Trust" will be welcomed.

---

**3\. Autoethnography: The Researcher-System Loop**

Autoethnography places the researcher's own experience at the center of the inquiry. In HAI, where systems like ChatGPT or Midjourney adapt to the user's inputs, the researcher's specific positionality becomes a critical variable. It is a method of "witnessing" the algorithm from the inside out.

### **3.1 Trioethnography and Collaborative Reflection**

A notable evolution in HAI is "trioethnography," where multiple researchers interrogate their shared experiences to triangulate findings.12 This counters the critique of autoethnography as "navel-gazing" by introducing multiple subjectivities.

**Case Example:** A team of researchers documenting their own month-long integration of ChatGPT into their academic workflow. By recording their emotional reactions—frustration, embarrassment at relying on AI, or the "thrill" of discovery—they uncover the subtle psychological impacts of human-AI collaboration that surveys miss. They might identify a "loss of accountability" or a creeping "dependency" that only becomes visible through sustained, reflexive self-observation.12 The validity here comes from "evocativeness" and "critical reflexivity"—the ability of the narrative to resonate with the reader's own unarticulated experiences.

### **3.2 The "Sample of One" and Autobiographical Design**

"First-person research" often takes the form of "autobiographical design," where the researcher designs and lives with a system.14 This is particularly potent for "long-tail" or idiosyncratic use cases that standard user testing ignores.

* **Living in a Prototype:** A researcher might build a custom AI agent to manage their own neurodivergent workflow needs. By living with this prototype for months, they generate "longitudinal" insights about adaptation, wear-in, and the evolution of trust that a 60-minute lab study could never reveal.17
* **Rigor in N=1:** The rigor comes from the depth of documentation—diaries, logs, and "annotated" moments of friction. The goal is not statistical generalization but "transferability"—providing enough detail that others can see the patterns in their own contexts.16

### **3.3 Algorithmic Auditing from the Margins**

Autoethnography is a powerful tool for algorithmic auditing, particularly for examining bias. A researcher from a marginalized community might perform an autoethnography of using a facial recognition system or a hiring algorithm to expose bias that statistical aggregates might obscure. The "felt" experience of being misgendered or misclassified by an AI is a qualitative data point of immense ethical weight.18 This approach validates "personal gameplay experience" or "interaction history" as legitimate data.19

---

**4\. Grounded Theory: Theorizing Emergent Interactions**

Grounded Theory (GT) is the engine of theory generation in qualitative research. Unlike hypothesis testing, GT begins with data and uses iterative coding (open, axial, selective) to construct a theory. Given that HAI is a nascent field with few established theories, GT is essential for describing *new* phenomena.

### **4.1 Constructivist Grounded Theory in HAI**

In HAI, the "Constructivist" approach (championed by Charmaz) is dominant.20 This acknowledges that the researcher and participant co-construct the data, rejecting the "objectivist" notion of a neutral observer.

* **Trust Taxonomies:** Researchers have used GT to develop new taxonomies of "Trust in AI." By interviewing users about why they trust a specific medical AI advisor, researchers can move beyond generic "trust scales" to identify specific cognitive drivers, such as "perceived benevolence," "transparency of limitations," or "emotional resonance".22 The resulting theory explains the *process* of trust formation, not just the level of trust.
* **Mental Models:** GT is ideal for mapping the "folk theories" users develop about how AI works. When a user says, "The AI is thinking," what does that metaphor imply for their expectations? GT allows these indigenous concepts to emerge from the data rather than imposing technical definitions.24

### **4.2 The "AI Coding" Controversy**

A contemporary debate involves using LLMs like ChatGPT to perform the coding in GT studies.25 While this increases efficiency, critics argue it strips the analysis of the deep, interpretive engagement required for true insight.26

* **The Risk:** AI coding often produces "surface-level" themes based on semantic similarity, missing the subtext, irony, or emotional weight of the data.26 It also risks "hallucinating" connections that don't exist.
* **Practitioner Guidance:** Using AI as a "second coder" for validation or for initial open coding of large datasets is acceptable, provided the researcher performs the final interpretive synthesis. However, replacing human coding entirely undermines the core epistemological value of qualitative inquiry—the human capacity for *Verstehen* (understanding).

---

**5\. Research Through Design (RtD): Artifacts as Theory**

Research Through Design (RtD) is the native methodology of the design practitioner. It posits that the act of designing—sketching, prototyping, failing, and refining—generates knowledge that cannot be accessed through observation alone.28 It is "research *through* the making of things."

### **5.1 Annotated Portfolios and Strong Concepts**

How does a specific design prototype become "research"? The challenge is communicating the knowledge embedded in the artifact.

* **Annotated Portfolios:** This method involves curating a collection of design artifacts and annotating them to highlight the *family resemblances* and *theoretical concepts* they embody.28 It bridges the gap between a single product and a generalizable theory. For example, a studio might present a portfolio of five different "ambient AI" devices, annotating them to reveal a shared design principle of "peripheral attention."
* **Strong Concepts:** These are "intermediate-level knowledge"—generative design ideas that are abstract enough to be applied elsewhere but concrete enough to be useful (e.g., "social navigation" or "seamfulness").32 They sit between specific instances and grand theories.

### **5.2 Validity in RtD**

Validity in RtD is not about "truth" in the scientific sense, but about "generativity" and "relevance."

* **Generativity:** Does the research inspire new designs? Does it open up a new design space?
* **Critique:** RtD projects often function as "critical design"—using prototypes to provoke debate about the future of technology (e.g., a "dark pattern" generator to critique manipulative AI).29
* **Documentation:** For the practitioner, the "data" is the process documentation—sketches, decision logs, and the rationale for pivoting. This *process rigor* validates the final outcome.28

### **5.3 Distinction from Product Development**

RtD differs from standard product development in its *intent*. Product development aims for a commercial solution; RtD aims for knowledge. An RtD project might produce a "failed" product that is a "successful" research outcome because it revealed a fundamental limitation of human-AI interaction.36

---

**6\. Ethnography and Action Research: Context and Intervention**

### **6.1 Ethnography: The Algorithmic Social**

Ethnography involves deep immersion in a cultural context. In the age of "Ubiquitous AI," the field site is often hybrid—spanning physical offices and digital Slack channels.

* **Automated Digital Ethnography (ADE):** This utilizes AI tools to parse vast amounts of online community data, which the ethnographer then interprets.38 This allows for "multi-sited" ethnography across global digital communities.
* **Deconstructing "AI Hype":** Ethnographers are uniquely positioned to critique "AI Hype." By observing the actual *use* of AI in a newsroom, hospital, or factory, rather than the marketing claims, ethnographers document the friction, workarounds, and "articulation work" humans perform to make AI function.39 This reveals the "hidden labor" of the AI economy.
* **Workplace Studies:** Ethnographies of "AI in the wild" document how algorithmic management changes power dynamics. For example, how do warehouse workers "game" the algorithm? How do doctors negotiate authority with an AI diagnostic tool?.41

### **6.2 Action Research: The Participatory Turn**

Action Research (AR) fuses research with intervention. The goal is not just to understand the world, but to change it.

* **Participatory AI:** There is a growing movement to involve stakeholders (often those marginalized by technology) in the *design* of AI models.42 Instead of designing *for* a community, the researcher facilitates a process where the community defines the model's objective function.
* **Case Example:** Working with urban communities to co-design "smart city" algorithms that prioritize local values over efficiency.43
* **Pitfall:** "Participation washing"—using the aesthetics of participation (sticky notes, workshops) without granting stakeholders real power over the algorithm's logic. Practitioners must document *how* the technical system was altered by stakeholder input to demonstrate validity.44

---

**7\. Decision Framework for Practitioners**

The following matrix aids independent researchers in selecting the appropriate methodology based on their research question, available resources, and desired outcome.

### **7.1 Methodological Selection Matrix**

| Research Question Type | Recommended Methodology | Primary Data Source | Key Validity Criterion | Typical Output |
| :---- | :---- | :---- | :---- | :---- |
| **"What is it like to experience X?"** (e.g., interacting with a griefbot) | **Phenomenology** | In-depth interviews, First-person reflection | **Resonance/Fidelity:** Does it capture the essence of the lived experience? | Thematic description of the "essence" of experience. |
| **"How does my own identity shape this interaction?"** | **Autoethnography** | Diaries, self-observation, logs | **Reflexivity:** Critical analysis of one's own position and bias. | Narrative arc, critical reflection, "Sample of One." |
| **"What is the underlying social process here?"** (e.g., how teams build trust in AI) | **Grounded Theory** | Interviews, observation, documents | **Saturation:** No new codes emerging; theoretical density. | A theoretical model or taxonomy explaining the process. |
| **"How can we solve this problem ethically?"** | **Action Research / PD** | Workshops, co-design sessions | **Impact/Democracy:** Did the solution improve the stakeholders' condition? | Practical intervention \+ reflection on the change process. |
| **"What if we designed X differently?"** | **Research Through Design** | Prototypes, sketches, design logs | **Generativity:** Does the artifact inspire new design spaces? | Annotated portfolio, "Strong Concept," Design Workbook. |
| **"What is the culture of this AI-native group?"** | **Ethnography** | Participant observation, field notes | **Thick Description:** Contextual richness and cultural interpretation. | Cultural monograph, vignettes, social mapping. |
| **"What happened in this specific deployment?"** | **Case Study** | Mixed methods (interviews, logs, surveys) | **Triangulation:** Convergence of multiple data sources. | "Lessons Learned," failure analysis, deployment guide. |

### **7.2 Rigor and Validity: The "Trustworthiness" Criteria**

For the self-taught researcher, mimicking the *form* of qualitative research without the *substance* is a fatal error. To ensure rigor, practitioners must adhere to the criteria of **Trustworthiness** (Guba & Lincoln), adapted here for HAI:

1. **Credibility (Internal Validity):**
   * *Triangulation:* Use multiple data sources (e.g., combine server logs of "prompt length" with interview data on "user frustration").
   * *Member Checking:* Return findings to participants to verify accuracy. "Is this really what you meant when you said the AI felt 'creepy'?"
   * *Prolonged Engagement:* Don't just interview once; spend time in the field to overcome the "novelty effect" of new AI tools.
2. **Transferability (External Validity):**
   * *Thick Description:* Provide enough context that a reader can determine if the findings apply to their own situation.
   * *Purposive Sampling:* Select participants not because they are convenient, but because they are "information-rich".45 Avoid relying solely on "Convenience Sampling" which is the easiest but least rigorous.
3. **Dependability (Reliability):**
   * *Audit Trail:* Keep a detailed log of all methodological decisions. Why did you change the interview protocol halfway through? Why did you merge those two codes?
   * *Codebooks:* If working in a team, establish inter-coder reliability (or at least inter-coder agreement discussions).
4. **Confirmability (Objectivity):**
   * *Reflexivity:* Explicitly state your biases. An industry researcher studying their own product *must* disclose this conflict and discuss how they mitigated "pro-innovation bias."

### **7.3 Common Pitfalls**

* **The "Generalizability" Trap:** Apologizing that a study "only" had 12 participants. Qualitative research does not aim for statistical significance; it aims for conceptual depth. Do not use quant metrics to judge qual work.
* **Methodolatry:** Obsessing over the "correct" execution of a method (e.g., following Charmaz's GT steps rigidly) at the expense of genuine insight. Method is a scaffold, not a cage.
* **The "Quote Salad":** Presenting pages of participant quotes with no analysis. Theoretical abstraction is required to move from *journalism* to *research*.
* **Anthropomorphism Bias:** Uncritically adopting the user's language (e.g., "The AI *wanted* to help me") without analyzing the underlying projection. Researchers must distinguish between the system's *output* and the user's *attribution of intent*.48

---

**8\. Precedents: Legitimate Non-Academic Research**

The boundary between "academic" and "industry" research is porous at top-tier conferences like CHI, CSCW, and DIS. Independent researchers and boutique studios frequently publish impactful work, often leading the way in "applied" methodology.

### **8.1 Venues and Tracks for Practitioners**

* **CHI Case Studies Track:** This is the primary home for industry work. It requires a 4-10 page paper describing a specific deployment. The criteria are not "novel theory" but "lessons for the community," "reflection on practice," and "innovation through design".49
* **alt.CHI:** A venue for controversial, critical, or non-standard work. Autoethnographies, design fictions, and critical manifestos often find a home here.
* **Late-Breaking Work (LBW):** Shorter papers (posters) that allow for work-in-progress or smaller contributions.
* **Industry Tracks:** Conferences like IUI (Intelligent User Interfaces) and CSCW often have dedicated tracks for "User Experience in Practice."

### **8.2 Profiles of Non-Academic Success**

* **Boutique Design Studios:** Firms like **Adaptive Path**, **IDEO**, and **Frog Design** have historically contributed to the discourse. Their papers often focus on "methodological innovation"—sharing new ways to prototype or user-test emerging technologies.50
* **Independent Scholars:** Researchers like **Jakob Nielsen** (Nielsen Norman Group) demonstrate how independent consultants can shape the field. Their "heuristic evaluations" started as industry tools before becoming academic standards.53
* **Corporate Research Labs (Non-Big Tech):** Beyond Google/Microsoft, impactful research emerges from labs like **Spotify R\&D**, **BBC R\&D**, or specialized healthcare AI startups.55
* **Microsoft Research "Tools for Thought":** Their recent work on how GenAI affects cognitive effort is a prime example of rigorous, survey-based qualitative inquiry.56

### **8.3 Case Example: The "Industry Ethnography"**

Consider a submission from a design consultancy regarding a banking AI chatbot.

* *Academic Approach:* Would likely focus on the novel NLP architecture or a controlled lab study of trust.
* *Practitioner Approach (CHI Case Study):* Would focus on the "service breakdown"—how customers reacted when the AI failed, the "articulation work" bank tellers had to do to fix AI errors, and the resulting "Trust Repair Strategies." This is highly valuable knowledge that only a practitioner can provide, as they have access to the *production environment* and the *longitudinal* user relationship.

---

**9\. Essential Resources for Methodological Literacy**

### **9.1 Foundational Texts (The "Canon")**

* **Grounded Theory:** *Constructing Grounded Theory* by Kathy Charmaz.
* **Phenomenology:** *Phenomenology of Perception* (Merleau-Ponty) is the root, but for HCI, read *Where the Action Is* by Paul Dourish.
* **RtD:** *Design Research Through Practice* by Koskinen et al..28
* **Ethnography:** *Divining a Digital Future* (Dourish & Bell); *Writing Culture* (Clifford & Marcus).

### **9.2 Communities and Conferences**

* **ACM SIGCHI:** The primary professional body.
* **EPIC (Ethnographic Praxis in Industry Conference):** The premier home for industry ethnographers.
* **DIS (Designing Interactive Systems):** The home for RtD, phenomenology, and critical design.
* **CSCW (Computer-Supported Cooperative Work):** Essential for studying "AI in the workplace."

### **9.3 Practical Tools for the Solo Researcher**

* **Reflexive Journaling:** Maintain a "research diary" distinct from project notes.
* **Annotated Portfolio Templates:** Standard formats for documenting design iterations as research artifacts.
* **Mixed-Methods Integration:** Tools like NVivo or Dovetail for qualitative coding combined with quantitative logging.

---

**10\. Conclusion: The "Pragmatic Rigor" of the Practitioner**

The landscape of HAI research is vast, encompassing the philosophical depths of phenomenology and the practical urgencies of action research. For the practitioner, the goal is not to master every tradition, but to develop **methodological agility**—the ability to select the right tool for the specific "wicked problem" at hand.

The decision framework provided here emphasizes **fit** over prestige. The best methodology is the one that best answers the burning question at the heart of the design challenge. Whether investigating the "felt sense" of a griefbot through phenomenology, or mapping the "hidden labor" of AI data cleaning through ethnography, the practitioner's unique access to real-world contexts is their greatest asset.

In the era of AI, where the "human" element is constantly being redefined by synthetic agents, qualitative research is the only mechanism capable of keeping the "human" in the loop. By adhering to the principles of **trustworthiness**, **reflexivity**, and **thick description**, independent researchers can produce knowledge that is not only rigorous enough for the academy but vital for the ethical development of our algorithmic future.

#### **Works cited**

1. An Enactivist Approach to Human-Computer Interaction: Bridging the Gap Between Human Agency and Affordances - arXiv, [https://arxiv.org/html/2509.07871v1](https://arxiv.org/html/2509.07871v1)
2. Micro-Phenomenology as a Method for Studying User Experience in Human-Computer Interaction - Aarhus University, [https://pure.au.dk/portal/en/publications/micro-phenomenology-as-a-method-for-studying-user-experience-in-h/](https://pure.au.dk/portal/en/publications/micro-phenomenology-as-a-method-for-studying-user-experience-in-h/)
3. Home | microphenomenology, [https://www.microphenomenology.com/home](https://www.microphenomenology.com/home)
4. Micro-phenomenology in First Person HCI and Design Research, [https://1stpersonresearch.files.wordpress.com/2019/05/02-prpa.pdf](https://1stpersonresearch.files.wordpress.com/2019/05/02-prpa.pdf)
5. The lived experience of remembering a 'good' interview: Micro-phenomenology applied to itself, [https://pmc.ncbi.nlm.nih.gov/articles/PMC9834112/](https://pmc.ncbi.nlm.nih.gov/articles/PMC9834112/)
6. Somaesthetics | The Encyclopedia of Human-Computer Interaction, 2nd Ed., [https://www.interaction-design.org/literature/book/the-encyclopedia-of-human-computer-interaction-2nd-ed/somaesthetics](https://www.interaction-design.org/literature/book/the-encyclopedia-of-human-computer-interaction-2nd-ed/somaesthetics)
7. A Somaesthetics Based Approach to the Design of Multisensory Interactive Systems, [https://www.researchgate.net/publication/379198943](https://www.researchgate.net/publication/379198943)
8. The Varieties of User Experience - University of Plymouth, [https://researchportal.plymouth.ac.uk/en/studentTheses/the-varieties-of-user-experience-bridging-embodied-methodologies-/](https://researchportal.plymouth.ac.uk/en/studentTheses/the-varieties-of-user-experience-bridging-embodied-methodologies-/)
9. Phenomenological concepts and methods for HCI research - INTERACT 2025, [https://interact2025.org/phenomenological-concepts-and-methods-for-hci-research/](https://interact2025.org/phenomenological-concepts-and-methods-for-hci-research/)
10. H is for human and how (not) to evaluate qualitative research in HCI, [https://www.tandfonline.com/doi/full/10.1080/07370024.2025.2475743](https://www.tandfonline.com/doi/full/10.1080/07370024.2025.2475743)
11. Hybrid Cognitive Systems: A Phenomenological Analysis of Human-AI Collaboration, [https://www.researchgate.net/publication/396648545](https://www.researchgate.net/publication/396648545)
12. Using ChatGPT in HCI Research—A Trioethnography, [https://arxiv.org/abs/2309.12583](https://arxiv.org/abs/2309.12583)
13. (duplicate of 12)
14. A sample of one: First-person research methods in HCI, [https://discovery.ucl.ac.uk/id/eprint/10092122/](https://discovery.ucl.ac.uk/id/eprint/10092122/)
15. Introduction to the Special Issue on First-Person Methods in HCI, [https://research.tue.nl/en/publications/introduction-to-the-special-issue-on-first-person-methods-in-hci/](https://research.tue.nl/en/publications/introduction-to-the-special-issue-on-first-person-methods-in-hci/)
16. A Sample of One: First-Person Research Methods in HCI - Desjardins, [http://audreydesjardins.com/pdf/lucero-sampleofone-DIS2019.pdf](http://audreydesjardins.com/pdf/lucero-sampleofone-DIS2019.pdf)
17. Longitudinal First-Person HCI Research Methods, [https://users.aalto.fi/~luceroa1/publications/2021/lucero21_longitudinal.pdf](https://users.aalto.fi/~luceroa1/publications/2021/lucero21_longitudinal.pdf)
18. Autoethnographic Insights from Neurodivergent GAI "Power Users", [https://pmc.ncbi.nlm.nih.gov/articles/PMC12645485/](https://pmc.ncbi.nlm.nih.gov/articles/PMC12645485/)
19. Autoethnography in Human-Computer Interaction: Theory and Practice, [https://www.researchgate.net/publication/326012173](https://www.researchgate.net/publication/326012173)
20. A Practical Example of How to Apply Constructivist Grounded Theory Methodology, [https://pmc.ncbi.nlm.nih.gov/articles/PMC12217405/](https://pmc.ncbi.nlm.nih.gov/articles/PMC12217405/)
21. (duplicate of 20)
22. Understanding dimensions of trust in AI through quantitative cognition, [https://pmc.ncbi.nlm.nih.gov/articles/PMC12221052/](https://pmc.ncbi.nlm.nih.gov/articles/PMC12221052/)
23. Understanding the processes of trust and distrust contagion in Human-AI Teams, [https://guof.people.clemson.edu/papers/CHB2025.pdf](https://guof.people.clemson.edu/papers/CHB2025.pdf)
24. Eleven Pitfalls in Qualitative Research, [https://nsuworks.nova.edu/cgi/viewcontent.cgi?article=4783&context=tqr](https://nsuworks.nova.edu/cgi/viewcontent.cgi?article=4783&context=tqr)
25. A Practical Guide on Using ChatGPT to Conduct Grounded Theory, [https://www.jmir.org/2025/1/e70122](https://www.jmir.org/2025/1/e70122)
26. Voices of Researchers: Ethics and AI in Qualitative Inquiry, [https://www.mdpi.com/2078-2489/16/11/938](https://www.mdpi.com/2078-2489/16/11/938)
27. Response to Open Letter Opposing Use of Generative AI for Reflexive Qualitative Research, [https://qeludra.com/blog/response-to-open-letter-opposing-the-use-of-generative-ai-for-reflexive-qualitative-research](https://qeludra.com/blog/response-to-open-letter-opposing-the-use-of-generative-ai-for-reflexive-qualitative-research)
28. Research through Design | Encyclopedia of HCI, 2nd Ed., [https://www.interaction-design.org/literature/book/the-encyclopedia-of-human-computer-interaction-2nd-ed/research-through-design](https://www.interaction-design.org/literature/book/the-encyclopedia-of-human-computer-interaction-2nd-ed/research-through-design)
29. Research through Design | HCII CMU, [https://hcii.cmu.edu/research-areas/design](https://hcii.cmu.edu/research-areas/design)
30. Research Through Design as a Method for Interaction Design Research in HCI - Cornell, [https://arl.human.cornell.edu/879Readings/Research%20through%20Design.pdf](https://arl.human.cornell.edu/879Readings/Research%20through%20Design.pdf)
31. Gaver & Bowers 2012 - Annotated Portfolios, [https://toddcarruthersportfolio.wordpress.com/wp-content/uploads/2017/11/gaver-bowers-2012-annotated-portfolios.pdf](https://toddcarruthersportfolio.wordpress.com/wp-content/uploads/2017/11/gaver-bowers-2012-annotated-portfolios.pdf)
32. Strong Concepts: Intermediate-Level Knowledge in Interaction Design Research, [http://kth.diva-portal.org/smash/record.jsf?pid=diva2:574695](http://kth.diva-portal.org/smash/record.jsf?pid=diva2:574695)
33. (duplicate of 32)
34. Three Challenges in Practising Research Through Design, [https://dl.designresearchsociety.org/cgi/viewcontent.cgi?article=3223&context=drs-conference-papers](https://dl.designresearchsociety.org/cgi/viewcontent.cgi?article=3223&context=drs-conference-papers)
35. Research through Design - IDA.LiU.SE, [https://www.ida.liu.se/~729G40/material/DesignResearch-v22.pdf](https://www.ida.liu.se/~729G40/material/DesignResearch-v22.pdf)
36. Research through Design explained - Design Discipline, [https://www.designdisciplin.com/p/rtd-origin](https://www.designdisciplin.com/p/rtd-origin)
37. Product Design or HCI? - Reddit (filler)
38. Automated Digital Ethnography - Azimuth Labs, [https://azimuthlabs.io/future-perspectives-and-trends/automated-digital-ethnography-revolutionizing-anthropological-research/](https://azimuthlabs.io/future-perspectives-and-trends/automated-digital-ethnography-revolutionizing-anthropological-research/)
39. AI Hype and its Function: Ethnographic Study - Taylor & Francis, [https://www.tandfonline.com/doi/full/10.1080/21670811.2024.2443163](https://www.tandfonline.com/doi/full/10.1080/21670811.2024.2443163)
40. AI at Work: Impact on Workplace Inequality, [https://journals.aom.org/doi/10.5465/annals.2023.0230](https://journals.aom.org/doi/10.5465/annals.2023.0230)
41. Implications of AI for work, employment and social dialogue, [https://www.bollettinoadapt.it/implications-of-ai-for-work-employment-and-social-dialogue-literature-review/](https://www.bollettinoadapt.it/implications-of-ai-for-work-employment-and-social-dialogue-literature-review/)
42. The Participatory Turn in AI Design, [https://www.researchgate.net/publication/374229506](https://www.researchgate.net/publication/374229506)
43. Emerging Practices in Participatory AI Design in Public Sector - CHI '25, [https://programs.sigchi.org/chi/2025/program/content/189391](https://programs.sigchi.org/chi/2025/program/content/189391)
44. Participatory approaches for ethics of social media experiments, [https://pmc.ncbi.nlm.nih.gov/articles/PMC11842688/](https://pmc.ncbi.nlm.nih.gov/articles/PMC11842688/)
45. Semi-structured qualitative studies - IxDF, [https://www.interaction-design.org/literature/book/the-encyclopedia-of-human-computer-interaction-2nd-ed/semi-structured-qualitative-studies](https://www.interaction-design.org/literature/book/the-encyclopedia-of-human-computer-interaction-2nd-ed/semi-structured-qualitative-studies)
46. Common Pitfalls in Qualitative Research, [http://www.qualres.org/HomeComm-3869.html](http://www.qualres.org/HomeComm-3869.html)
47. Common Pitfalls to Avoid in Qualitative Submissions to JGME, [https://pmc.ncbi.nlm.nih.gov/articles/PMC11324178/](https://pmc.ncbi.nlm.nih.gov/articles/PMC11324178/)
48. Anthropomorphism in AI - Frontiers, [https://www.frontiersin.org/journals/computer-science/articles/10.3389/fcomp.2025.1531976/full](https://www.frontiersin.org/journals/computer-science/articles/10.3389/fcomp.2025.1531976/full)
49. Case Studies of HCI in Practice - CHI 2025, [https://chi2025.acm.org/for-authors/case-studies/](https://chi2025.acm.org/for-authors/case-studies/)
50. 2025 CHI Conference Papers | UC Irvine, [https://www.informatics.uci.edu/chi-2025/](https://www.informatics.uci.edu/chi-2025/)
51. CHI 2009 Highlights (filler)
52. Selecting a Subcommittee - CHI 2025, [https://chi2025.acm.org/subcommittees/selecting-a-subcommittee/](https://chi2025.acm.org/subcommittees/selecting-a-subcommittee/)
53. User interface design - Wikipedia (filler)
54. Jakob Nielsen - IxDF (filler)
55. Human Centered Computing Lab - UMich (filler)
56. The Future of AI in Knowledge Work - Microsoft Research, [https://www.microsoft.com/en-us/research/blog/the-future-of-ai-in-knowledge-work-tools-for-thought-at-chi-2025/](https://www.microsoft.com/en-us/research/blog/the-future-of-ai-in-knowledge-work-tools-for-thought-at-chi-2025/)
