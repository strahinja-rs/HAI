# **MAPPING THE FIELD OF HUMAN-AI INTERACTION (2020–2026): PARADIGMS, PRACTICES, AND THE AGENTIC TURN**

## **Executive Summary**

The discipline of Human-AI Interaction (HAI) has undergone a radical ontological and structural transformation between 2020 and January 2026\. Once a specialized sub-domain of Human-Computer Interaction (HCI) focused largely on the usability of recommender systems and the interpretability of machine learning models, HAI has emerged as a distinct, high-velocity field with its own taxonomy, methodological crises, and design paradigms. This report provides an exhaustive mapping of this landscape, synthesizing data from academic literature, industrial white papers, and global conference proceedings to characterize the state of the field at the onset of 2026\.

The period in question can be stratified into three distinct epochs. The early phase (2020–2022) was dominated by the "Explainability Imperative," driven by the need to calibrate trust in diagnostic and classification systems. The middle phase (2023–2024), triggered by the public release of ChatGPT and subsequent Large Language Models (LLMs), defined the "Generative Inflection," where the primary interaction mode shifted to natural language prompting and the central research question became the management of non-deterministic outputs. The current phase (2025–2026) is characterized as the "Agentic Turn." In this era, the locus of research has moved beyond direct interaction with a model to the orchestration of semi-autonomous agents capable of planning, tool use, and multi-step execution.

Our analysis reveals several critical shifts that define the 2026 landscape:

1. **The Dissolution of Direct Manipulation:** The forty-year dominance of "Direct Manipulation" (the click-and-drag paradigm of the GUI) is eroding. It is being replaced by "Intent Specification," where users declare goals rather than procedures. This has necessitated the creation of new interaction typologies, such as "Generative UI" and "Ambient Intelligence," to bridge the gap between vague human intent and precise machine execution.1  
2. **The Rise of Agentic Architectures:** By 2026, "Agentic AI" has become the central focus of both academic and industrial labs. The challenge has shifted from designing a single interface to designing ecosystems of agents (e.g., "Swarm Intelligence" and "Orchestrator" patterns). This has introduced novel design challenges regarding "adjustable autonomy," where the user must dynamically negotiate the level of control they retain over a system.3  
3. **The Reproducibility Crisis and Methodological Innovation:** The inherent stochasticity of Generative AI has rendered traditional HCI evaluation metrics (like static benchmark accuracy) insufficient. A "reproducibility crisis" has forced the field to adopt "Interactive Evaluations" and "AI-mediated Ethnography," where AI agents themselves are used to simulate users or conduct qualitative interviews at scale.5  
4. **Institutional Bifurcation and Convergence:** A complex dynamic exists between academic institutions, which focus on theoretical frameworks and ethics (e.g., MIT's "Atlas of Human-AI Interaction"), and corporate labs (e.g., Anthropic, Google DeepMind), which effectively control the substrate of the field—the models themselves. This has led to a reliance on "grey literature" (preprints and blogs) as primary scientific currency.7

This report details these shifts across nine sections, offering a comprehensive guide for researchers, practitioners, and policymakers navigating the complex socio-technical reality of Human-AI Interaction in 2026\.

## ---

**1\. Field Structure: Relationship to HCI, Sub-areas, and Taxonomy**

The structural identity of Human-AI Interaction has solidified by 2026, establishing it as a discipline that, while rooted in Human-Computer Interaction, possesses a distinct set of axioms regarding agency, error, and collaboration. The boundary between HCI and HAI is no longer defined merely by the presence of an algorithm, but by the nature of the interaction loop itself.

### **1.1 From HCI to HAI: A Divergence of Agency**

Historically, HCI was predicated on the assumption of a passive machine and an active user. The computer was a tool; the human was the operator. HAI, as crystallized in the literature of 2024–2026, posits a relationship of "distributed agency." Crompton (2021) and subsequent definitional works in 2025 describe HAI as a bidirectional process where "the human agent (re-)acts on the output of the AI, and the AI (re-)acts on the output of the human agent".1 This recursivity distinguishes HAI from traditional automation. In automation, the human sets a parameter and leaves; in HAI, the human and the system engage in a continuous dialectic of hypothesis, output, critique, and refinement.

The transition from HCI to HAI is also marked by a shift in the "materiality" of the design object. In HCI, designers crafted static pathways (menus, buttons). In HAI, designers craft "interaction policies" and "alignment functions." The 2025 definition of **Human-AI Collaboration** emphasizes complementary skills: the human provides intuition, context, and ethical judgment, while the AI provides computational power, pattern recognition, and scale.1 This partnership model is not merely aspirational but operational; systems are now evaluated on their ability to augment human reasoning rather than just replace specific tasks.

### **1.2 Taxonomy of Interaction Domains**

By 2026, the sprawling literature of the early 2020s has organized into a coherent taxonomy, comprising four primary quadrants of research and practice.

#### **1.2.1 AI-Assisted Decision Making (The Analytic Quadrant)**

This sub-area focuses on high-stakes domains such as healthcare, finance, and criminal justice. Research here is dominated by the study of "human-AI teaming" and the risks of over-reliance. A major systematic review in 2025 of 105 articles in this domain identified a critical gap: while systems are proficient at displaying recommendations (e.g., "80% risk of fraud"), they lack "true interactivity." The field is moving toward "contestability" mechanisms, where users can query the specific rationale of a decision and force the AI to consider alternative hypotheses.10 The goal is to move from "simplistic collaboration paradigms" to "dialectical decision support".10

#### **1.2.2 Co-Creativity and Generative Flow (The Creative Quadrant)**

With the ubiquity of generative models, a distinct sub-field has emerged around the psychology and mechanics of co-creation. This area explores the "double diamond" process of design—discovery, definition, development, delivery—and maps where AI augments each phase. Research in 2025 explicitly links "generative AI anthropomorphism" to user emotional attachment, finding that while social presence can enhance creativity, it can also trigger "identity threats" if the AI is perceived as usurping the human's creative ownership.12

#### **1.2.3 Agentic Delegation and Supervision (The Management Quadrant)**

The most rapidly expanding area in 2026 is the study of **Agentic Interaction**. This domain investigates the user experience of delegation. It asks: How does a human effectively supervise a fleet of autonomous agents? Research here has moved beyond "human-in-the-loop" (where the human actively participates) to "human-on-the-loop" (supervisory control) and "human-out-of-the-loop" (audit-based verification). Key theoretical contributions in 2025 focus on "adjustable autonomy," designing systems that allow users to dynamically throttle the agent's independence based on the stakes of the task.14

#### **1.2.4 Social and Embodied Interaction (The Relational Quadrant)**

This area intersects with robotics and virtual reality. It examines how physical or virtual embodiment alters the perception of intelligence. Studies from 2025 indicate that "embodied AI peers" in VR learning environments foster significantly higher engagement and "social presence" than voice-only agents, suggesting that the spatialization of AI is a critical component of interaction design.16

### **1.3 Structural Hierarchy of the Field**

The field's knowledge structure in 2026 can be visualized as a layered stack, with research occurring at different levels of abstraction:

| Layer              | Research Focus     | Key Questions (2025-2026)                                                                                    |
| :----------------- | :----------------- | :----------------------------------------------------------------------------------------------------------- |
| **Meta-Science**   | Field Mapping      | How do we synthesize thousands of papers to find causal links? (e.g., The *Atlas of Human-AI Interaction*) 7 |
| **Sociotechnical** | Systems & Society  | How does "Agentic AI" impact labor markets and university education? 6                                       |
| **Interactional**  | Modes & Interfaces | Is the Chat interface a bottleneck? How do we design "Cognitive Forcing Functions"? 17                       |
| **Algorithmic**    | Capabilities       | How do we align latent model goals with explicit human instructions? 2                                       |

This taxonomy reveals that HAI is no longer just about the "screen"; it is about the "system." The field has expanded to encompass the sociotechnical implications of these systems, integrating insights from sociology, law, and cognitive science into the core technical definition of interaction.12

## ---

**2\. Institutional Landscape: Key Conferences, Journals, and Labs**

The geography of HAI research in 2026 is defined by a tension between established academic prestige and the raw velocity of industrial R\&D. While universities provide the theoretical backbone and ethical frameworks, corporate labs often control the frontier models required for empirical experimentation. This has led to a complex ecosystem where collaboration and competition coexist.

### **2.1 The Conference Circuit: Venues of Record**

The Association for Computing Machinery (ACM) remains the primary host for HAI research, though the center of gravity is shifting.

* **CHI (Conference on Human Factors in Computing Systems):** CHI remains the undisputed flagship. The 2025 conference in Yokohama and the upcoming 2026 events focus heavily on "AI \+ HCI" methodologies. Key themes include AI tools for critical thinking, education, and the design of "smoother user interfaces" that integrate generative capabilities. CHI serves as the rigorous gatekeeper for user studies, demanding high standards of empirical validity.19  
* **IUI (Intelligent User Interfaces):** Once a niche venue, IUI has become the technical heart of the field. It bridges the gap between pure machine learning research and human-centered design, serving as the primary venue for papers on "adaptive interfaces" and "algorithmic transparency".1  
* **HHAI (Hybrid Human-Artificial Intelligence):** This newer venue, with its 2025 conference in Pisa, Italy, represents a uniquely European perspective. It emphasizes "human-centered AI" rooted in cognitive science, philosophy, and complex systems, offering a counterweight to the engineering-centric view of US conferences.21  
* **HCI International (HCII):** This massive umbrella conference now hosts a dedicated sub-conference, **AI-HCI**, which focuses on the operational aspects of trust, cybersecurity, and cross-cultural design in AI systems.22  
* **Generative AI and HCI Workshops (GenAICHI):** Since 2022, this workshop series has been the "avant-garde" of the field, defining the research agenda for generative systems. By 2025, it has matured into a primary venue for discussing "co-creative patterns" and the ethical implications of synthetic media.24

### **2.2 Corporate Research Labs: The Engines of Deployment**

Corporate labs in 2026 are not merely developing technology; they are defining the modes of interaction through their product deployments.

* **Google (DeepMind & PAIR):** Google DeepMind continues to lead in foundational capabilities. Their 2025 breakthroughs include "AI co-scientists" (multi-agent systems for hypothesis generation) and "Gemini Robotics" (embodied agents). The **People \+ AI Research (PAIR)** team is influential in defining design standards, releasing updated editions of the *PAIR Guidebook* in 2025 to address agentic behaviors and "mental model" alignment.8  
* **Microsoft Research (MSR):** MSR maintains a massive footprint, particularly through its "New Future of Work" initiative. They leverage their integration with OpenAI to study HAI at an enterprise scale. Their 2025 research focuses on "Societal AI," "tools for thought," and the specific mechanics of "human-AI collaboration" in productivity software.28  
* **Anthropic:** A key differentiator for Anthropic in 2025–2026 is its focus on "Constitution AI" and "Interaction Harms." Unlike labs focused purely on capability, Anthropic's research teams (including sociologists like Saffron Huang) publish influential papers on the *societal* impact of interaction designs, such as the risks of "anthropomorphic seduction" and the economic taxonomy of AI tasks.2  
* **IBM Research:** Continues to focus on "Generative AI for HCI," particularly in the context of coding assistants and "code style transfer," emphasizing trust and transparency in professional workflows.24

### **2.3 Academic Power Centers**

Universities have pivoted to address the "black box" nature of corporate models by focusing on user behavior and societal impact.

* **MIT Media Lab:** Under the "Advancing Humans with AI (AHA)" program, led by Pattie Maes and Hiroshi Ishii, MIT focuses on "human flourishing" and "cyborg psychology." A major contribution in 2025 was the launch of the **"Atlas of Human-AI Interaction,"** a meta-science platform that uses LLMs to map the causal findings of thousands of HCI papers.7  
* **Stanford HAI (Human-Centered AI):** Remains the nexus for policy and interdisciplinary study. Their **AI Index Report 2025** provides the definitive metrics on global AI adoption, shifting the conversation from "what models can do" to "how people are actually using them".34  
* **Carnegie Mellon University (HCII):** The Human-Computer Interaction Institute at CMU, with researchers like Ken Holstein, focuses on "Augmenting Intelligence" and the practical design of AI products. Their "Dig Lab" is central to studying algorithmic fairness and worker well-being in the face of automation.35

### **2.4 The "Grey Literature" Ecosystem**

A notable feature of the 2026 landscape is the dominance of non-traditional publishing. Due to the speed of AI development, peer review is often too slow. Key insights frequently appear in **arXiv preprints** and **industry white papers** months before conference presentation. The field has adapted to treat these sources with high seriousness, and "living papers" (updated versions on arXiv) are standard citations.36

## ---

**3\. Modes of Interaction: A 2026 Typology**

The simplistic dichotomy of "tool vs. agent" has evolved into a rich spectrum of interaction modes by 2026\. The field has moved beyond the "Chat" interface to explore Ambient, Agentic, and Embodied paradigms.

### **3.1 The "Chat" Paradigm and the Crisis of the GUI**

While the "Chat" interface (Conversational UI) popularized Generative AI, research in 2025 reveals a "Chat vs. GUI" tension.

* **The Critique of Chat:** Critics argue that pure chat interfaces create a "gulf of evaluation." They force users to operate via *recall* (remembering what to ask) rather than *recognition* (seeing available options), imposing a high cognitive load. They act as a narrow "straw" for complex information, lacking the affordances of visual manipulation.17  
* **Generative UI (GUI 2.0):** The industry response is the rise of **Generative UI**—systems that generate graphical widgets (buttons, sliders, maps, dashboards) on the fly within a chat stream. This blends the flexibility of natural language with the efficiency of direct manipulation. For example, a user might ask for a "travel itinerary," and instead of text, the AI generates an interactive map and a timeline slider. This hybrid mode is becoming the standard for complex tasks.1

### **3.2 Agentic Interaction: Delegation Patterns**

As discussed further in Section 5, agentic interaction involves delegating high-level goals. The typology here, defined by Anthropic and others in 2025, includes:

* **Directive:** The user explicitly commands every step (traditional scripting).  
* **Feedback Loop:** The user and AI engage in iterative dialogue to refine a task.  
* **Task Iteration:** The AI performs a draft; the user refines it.  
* **Delegation:** The AI executes autonomously; the user reviews logs. This is the "frontier" mode of 2026\.31

### **3.3 Ambient AI: The Invisible Interface**

A major trend in 2025-2026 is **Ambient AI**, particularly in healthcare and enterprise environments.

* **Definition:** Ambient systems operate continuously in the background, processing contextual signals (audio, screen activity, location) to trigger actions without explicit commands. They shift the user interactions from "invocation" to "supervision".40  
* **Case Study: Ambient Clinical Documentation:** By 2025, nearly two-thirds of US hospitals using the Epic EHR system had adopted ambient AI tools. These tools listen to patient-doctor consultations and draft clinical notes automatically. The interaction dynamic here is unique: users (doctors) are "pulling" for this technology, reversing the traditional dynamic where IT "pushes" changes. The primary interaction is not *writing* the note, but *editing* the draft. This "ambient" mode reduces burnout but introduces new risks of "automation complacency," where doctors may sign off on notes without thorough review.41  
* **Design Challenge:** The core design challenge is "intrusiveness vs. utility." How does the system signal it has acted without breaking the user's flow? New paradigms involve subtle "ambient indicators" rather than pop-up notifications.44

### **3.4 Embodied and Multimodal Interaction**

The integration of vision, voice, and spatial awareness has led to **Multimodal Intelligence** becoming the default expectation.

* **Embodied AI:** In VR and robotics, agents are gaining physical or virtual bodies. Research at NCSU (2025) demonstrates that "embodied" AI peers in VR learning environments foster greater engagement than voice-only agents. The physical presence of the AI (even as an avatar) triggers social cognition mechanisms in the human brain, aiding in collaborative tasks like programming.16  
* **Multimodal Reasoning:** Users now expect to show the AI an image and ask questions about it, or to have the AI "see" their screen. This requires new interaction patterns for "joint attention"—mechanisms for the user and AI to confirm they are looking at the same part of an image or document.45

## ---

**4\. The LLM Inflection Point: From Prompting to Interaction Design**

The release of ChatGPT marked an inflection point, but by 2026, the field has matured from "prompt engineering" (a technical hack) to "prompt science" and "interaction design."

### **4.1 The Evolution of Prompting**

In 2023-2024, "prompt engineering" was hailed as a critical new skill. By 2026, research suggests a bifurcation:

* **System-Level Prompting:** Complex prompting strategies (e.g., Chain-of-Thought, Tree-of-Thoughts) have moved "under the hood." They are now handled by the system architecture, hidden from the end-user.  
* **Interaction-Augmented Instructions (IAI):** For the end-user, raw prompting is being replaced by IAI. These systems use graphical wrappers and structured inputs to guide users in constructing complex queries, reducing the "blank page" paralysis. Research shows that "heuristic prompts" and "ensemble prompts" (combining multiple strategies) significantly outperform simple queries in clinical and specialized domains.46

### **4.2 Prompt Literacy and Mental Models**

Despite better tools, "Prompt Literacy" remains a significant barrier. Research from 2025 indicates that users often lack accurate mental models of how LLMs process information, leading to "superstitious prompting" or failure to fact-check.

* **The Educational Gap:** Universities are now treating prompt literacy as a core competency, distinct from coding. It involves critical evaluation of outputs and understanding the probabilistic nature of the "stochastic parrot."  
* **User Strategies:** Studies of students reveal specific prompting behaviors, such as "Single Copy & Paste" (lazy prompting) vs. "Single Reformulated Prompting" (iterative refinement). Educational interventions are now designed to move users from the former to the latter, teaching them to treat the AI as a dialogue partner rather than an oracle.49

### **4.3 The "Cognitive Forcing" Counter-Movement**

A critical development in 2025 is the introduction of **Cognitive Forcing Functions (CFFs)** in HAI design. To combat over-reliance on smooth, authoritative-sounding LLM outputs, designers are intentionally introducing friction.

* **Mechanism:** These functions force the user to pause and engage "System 2" thinking (analytical) rather than "System 1" (automatic).  
* **Application:** For example, an AI might blur a generated summary until the user answers a comprehension question, or explicitly highlight low-confidence segments to provoke verification. This represents a radical departure from the "frictionless" design ethos of the 2010s. Research confirms that CFFs significantly reduce "overtrust" and hallucination acceptance rates.18

## ---

**5\. Agentic AI: The 2026 Research Landscape**

If 2023 was the year of the Chatbot, 2026 is the year of the Agent. **Agentic AI**—systems capable of independent planning, tool use, and execution—has moved from experimental demos to enterprise deployment, fundamentally altering the nature of HAI.

### **5.1 Defining the Agentic Shift**

Gartner and McKinsey identify Agentic AI as the top strategic trend for 2026\. Unlike passive models that wait for a prompt, agents "perceive, reason, act, and learn." They are capable of executing "long-horizon" tasks (e.g., "Plan a travel itinerary and book the tickets") without continuous human hand-holding. By 2026, 40% of enterprise applications include task-specific agents, up from less than 5% in 2024\.3

### **5.2 Architectural Design Patterns**

A robust set of architectural patterns has emerged to manage agent behavior, moving interaction design into the realm of systems engineering:

* **The Orchestrator Pattern:** A central "brain" agent analyzes a user's high-level request, breaks it down into sub-tasks, and delegates them to specialized "worker" agents. The HAI challenge here is visibility: users need to see the "org chart" of agents to trust the process.57  
* **ReAct (Reason and Act):** A pattern where the agent explicitly generates a reasoning trace ("I need to check the stock price") before executing an action. This text trace serves as the primary "explainability" interface for the user, allowing them to audit the agent's logic before execution.58  
* **Swarm Intelligence:** Multiple agents collaborating on a problem, mimicking biological swarms. This is particularly relevant in robotics, as seen in the "social mobile manipulation" challenges at CVPR 2025\. The interaction challenge is "group control"—how does a single human guide a swarm?.4  
* **Review and Critique:** A pattern where one agent generates a plan and another agent (or the human) critiques it. This "adversarial" interaction improves reliability and provides a natural insertion point for human oversight.58  
* **Human-in-the-Loop (HITL) vs. Human-on-the-Loop (HOTL):** Design patterns now explicitly code for authorization levels. High-stakes actions (transferring funds) trigger a HITL requirement, while low-stakes actions (scheduling a meeting) operate HOTL (notification only).14

### **5.3 Design Challenges and Risks**

The transition to agentic AI introduces severe UX and ethical challenges:

* **The Control-Autonomy Paradox:** Users desire the convenience of autonomy but fear the loss of control. Research focuses on **"adjustable autonomy,"** allowing users to dial up or down the agent's independence based on trust and context. A user might set an agent to "Autopilot" for scheduling but "Co-pilot" for email writing.14  
* **Observability and Transparency:** How do you visualize the thought process of an agent that runs for hours? "Process logs" and "reasoning traces" are becoming standard UI elements, but they risk overwhelming the user. The design goal is "glanceable observability".59  
* **Labor Displacement and Anxiety:** The rise of the "Agentic University" and "AI Employees" is creating significant workforce anxiety. 55% of professionals express fear of displacement, even as they acknowledge efficiency gains. This "shadow system" of agents requires organizational change management as much as interface design.6

## ---

**6\. Transition from HCI to HAI: New Methods and Frameworks**

The methods that served HCI for decades (e.g., usability testing with 5 users, static benchmark tasks) are failing under the weight of generative, non-deterministic systems. The field is undergoing a methodological revolution to address the "Reproducibility Crisis."

### **6.1 The Reproducibility Crisis**

The stochastic nature of LLMs means that the same prompt often yields different results, making traditional "replication" of user studies nearly impossible. A 2023–2025 wave of meta-analysis has highlighted a looming crisis in HCI caused by reliance on closed, shifting models like GPT-4. When the model changes behind the API, the research findings become obsolete.5

### **6.2 New Evaluation Frameworks**

To address this, the field is adopting new frameworks:

* **Interactive Evaluations:** Instead of static benchmarks (e.g., "Did the model answer correctly?"), researchers use dynamic scenarios to measure "interaction harms." These evaluations trace how model behaviors influence human users over time, capturing subtle effects like social manipulation or cognitive over-reliance that single-turn benchmarks miss.2  
* **Wizard of Oz (WoZ) 2.0 with LLMs:** The classic WoZ technique (where a human pretends to be a computer) is being updated. We now have **"LLM Wizards,"** where an LLM simulates the system component to test prototype interactions at scale. Conversely, **"Synthetic Users"** (LLMs acting as users) are being used to stress-test designs before human trials. This allows for massive, scalable "pre-piloting" of interaction designs.61  
* **Meta-Science and Knowledge Graphs:** Projects like MIT's **"Atlas of Human-AI Interaction"** represent a new methodological approach. By using AI to extract findings from thousands of papers and connect them in a causal graph, researchers can identify "structural holes" in the literature that human review would miss. This moves the field from isolated studies to a connected "knowledge network".7

### **6.3 Algorithmic Ethnography**

Qualitative methods are also adapting. The **"Anthropic Interviewer"** system, deployed in 2025, conducted 1,250 qualitative interviews with professionals about their AI usage. This scale of qualitative data collection—impossible for human researchers—represents a new frontier: *AI-mediated ethnography*. It allows researchers to capture the "long tail" of user experiences and identify emergent behaviors that small-scale studies miss.6

## ---

**7\. The Practitioner Landscape: Teams, Guidelines, and Tools**

The professional practice of "AI Design" has formalized. It is no longer a niche for "technical designers" but a core requirement for all UX professionals.

### **7.1 Guidelines and Standards**

The "Wild West" era is ending. Major tech firms and standards bodies have updated their guidelines to address agentic and generative behaviors.

* **Microsoft HAX (Human-AI eXperience):** The HAX guidelines remain the industry standard. The 2025 updates focus on "ambiguity" and "correction"—teaching designers how to build interfaces that allow users to fix AI mistakes easily. They emphasize that *error is inevitable* in generative systems, so the interface must support efficient "repair".29  
* **Google PAIR:** The 2025 edition of the PAIR Guidebook emphasizes "mental models" and "explainability," specifically for non-deterministic outputs. It provides patterns for "onboarding" users to new agentic capabilities.27  
* **Nielsen Norman Group:** Continues to advocate for "User Control" as the prime directive, warning against "magical" interfaces that hide system status. Their 2025 recommendations focus on "Error Recovery" and giving users the ability to override AI decisions.64

### **7.2 The New Toolchain: Generative Prototyping**

The toolchain for designers has been revolutionized. Static prototyping tools are being augmented or replaced by **AI-native prototyping environments**.

* **Generative Prototyping:** Tools like **v0.app**, **Bolt.new**, and **Figma Make** allow designers to generate fully functional, code-backed prototypes from text prompts. This collapses the "design-to-code" latency, enabling "live prototyping" during user testing. A designer can now iterate on a high-fidelity prototype *during* a user session, responding to feedback in real-time.62  
* **AI Design Sprints:** A new methodology tailored for AI products. Unlike traditional design sprints, these include specific phases for "Data Auditing" (understanding what the model *can* know) and "Confusion Matrix Analysis" (anticipating where it will fail). This ensures that design concepts are grounded in technical reality, preventing "innovation theater".66

## ---

**8\. Key Debates and Controversies**

As the technology matures, ideological fissures have deepened regarding the nature of the human-AI relationship.

### **8.1 Anthropomorphism: Tool or Partner?**

This remains the most heated debate in the field.

* **The Pro-Anthropomorphism Argument:** Proponents argue that social cues (empathy, voice, personality) are necessary for trust and engagement, especially in healthcare and education. Research shows that "highly anthropomorphic avatars" can significantly increase perceived empathy and improve user satisfaction in service contexts.13  
* **The Anti-Anthropomorphism Argument:** Critics warn of "anthropomorphic seduction" and "identity threat." They argue that making AI sound human tricks users into overestimating its competence, leading to dangerous over-reliance. They advocate for "transparent machine-ness," where the system explicitly signals its artificial nature to prevent the formation of "parasocial relationships".69

### **8.2 The "Death of the GUI"**

A provocative debate in 2025 is the predicted obsolescence of the Graphical User Interface.

* **The Argument:** With perfect intent understanding (via LLMs), menus and buttons become redundant friction. "The GUI walked into my office in '84 and never left, until now".71  
* **The Counter-Argument:** Visual interfaces provide *affordances* (clues on what is possible) that blank chat boxes lack. The consensus emerging in 2026 is a hybrid: **Dynamic GUIs** or **Generative UI**, where the AI generates temporary graphical controls relevant to the current context. We are not seeing the *death* of the GUI, but its *fluidity*.1

### **8.3 Control vs. Autonomy (The Alignment Problem as UX)**

As agents become more capable, the "alignment problem" moves from philosophy to UX. How do we ensure an autonomous agent doesn't "optimize" a task in a way that harms the user? (e.g., booking the cheapest flight but with a 12-hour layover). The debate centers on the granularity of control: should users approve *every* step, or just the final outcome? Research suggests that **"Negotiated Control"**—where the agent pauses to ask clarifying questions only when confidence is low—is the optimal path.12

## ---

**9\. Key Thinkers and Influencers**

The field is driven by a mix of veteran HCI scholars and new AI-native researchers.

* **Pattie Maes & Hiroshi Ishii (MIT Media Lab):** Leading the "Cyborg Psychology" and "Advancing Humans with AI" initiatives. Their work focuses on augmentation rather than replacement, and they are pioneering the use of meta-science tools like the "Atlas".32  
* **Ben Shneiderman (Univ. of Maryland):** His framework of "Human-Centered AI" (high automation \+ high control) continues to be the theoretical bedrock for critics of "autonomous" systems. He argues for systems that are "reliable, safe, and trustworthy" through user control.12  
* **Fei-Fei Li (Stanford/World Labs):** A central figure in "Spatial Intelligence" and the visual aspects of HAI. Her new venture, World Labs, is pushing the boundaries of how AI perceives and interacts with the 3D world.73  
* **Microsoft Research FATE/HCI Groups:** Researchers like **Q. Vera Liao** (Explainable AI) and others leading the HAX and "New Future of Work" initiatives are defining the industrial standards for productivity AI.28  
* **The Anthropic Societal Impacts Team:** Researchers like **Saffron Huang** are pioneering "Interaction Harms" research, bridging the gap between safety engineering and sociology. Their work on "Constitution AI" is central to the ethics of agentic systems.2  
* **The GenAICHI Organizers:** The team behind the Generative AI and HCI workshops (CHI 2022-2025) has effectively defined the research agenda for the generative era, fostering a community that bridges the technical and the creative.25

## ---

**10\. Annotated Bibliography**

This section highlights seminal works and reports that define the 2020-2026 period.

**1\. "Human-AI Interaction Field Definition & Taxonomy" (Crompton et al., 2021; Updated 2025\)**

* *Significance:* Provides the foundational definition of HAI as a bidirectional, collaborative process. The 2025 updates introduce a crucial taxonomy of "interaction patterns" (e.g., simplistic collaboration vs. true interactivity) that serves as a critique of current tools.1

**2\. "AI Index Report 2025" (Stanford HAI)**

* *Significance:* The definitive statistical record of the field. The 2025 edition is vital for understanding the "societal scale" of HAI, tracking metrics on public sentiment, corporate adoption, and the explosion of patenting in human-centered AI technologies.34

**3\. "Towards Interactive Evaluations for Interaction Harms" (Huang et al., 2025\)**

* *Significance:* A methodological turning point. This paper argues that static benchmarks are insufficient for HAI and proposes "interactive evaluations" to capture harms that only emerge during sustained usage.2

**4\. "Microsoft Human-AI Interaction Design Guidelines (HAX)" (Amershi et al., 2019; Updated 2025\)**

* *Significance:* The industry standard for UX practitioners. The 2025 updates address the specific challenges of Generative AI, adding guidelines for "Ambiguity" and "Hallucination mitigation".29

**5\. "Atlas of Human-AI Interaction" (MIT Media Lab, 2025\)**

* *Significance:* A meta-science breakthrough. It uses LLMs to synthesize thousands of papers into a causal graph, representing the future of literature review in a field growing too fast for human reading speeds.7

**6\. "The Rise of the Agentic University" (UPCEA/Inside Higher Ed, 2025\)**

* *Significance:* Captures the sociological impact of Agentic AI. It moves beyond the "cheating" debates of 2023 to discuss the structural transformation of knowledge work and education in an era of autonomous agents.15

**7\. "To Trust or to Think: Cognitive Forcing Functions" (Buçinca et al., 2021; Revisited 2025\)**

* *Significance:* Reintroduced in the LLM era, this work challenges the "seamless design" dogma. It provides empirical evidence that "friction" is necessary to prevent over-reliance on AI.18

**8\. "Agentic AI Frameworks: Architectures, Protocols, and Design Challenges" (Wang et al., 2025\)**

* *Significance:* A comprehensive technical survey of the "Agentic Turn," defining the key patterns (ReAct, Orchestrator) that are shaping the software architecture of 2026\.14

### ---

**Conclusion**

By January 2026, Human-AI Interaction has matured into a critical discipline that sits at the intersection of computer science, psychology, and design. The field has successfully navigated the initial shock of the LLM revolution and is now grappling with the deeper, systemic challenges of **Agentic AI**.

The trajectory for the remainder of the decade is clear: the field will focus less on "how to prompt" and more on "how to orchestrate." As AI systems recede into the background ("Ambient AI") or take on autonomous roles ("Agentic AI"), the measure of success in HAI will shift from *engagement* to *alignment*—ensuring that these powerful, semi-independent systems remain reliable extensions of human intent. The "Human" in Human-AI Interaction has never been more important.

### ---

**Table 1: Evolution of HAI Interaction Paradigms (2020–2026)**

| Feature | Command-Based (HCI) | Intent-Based (GenAI Phase 1\) | Agentic (GenAI Phase 2\) |
| :---- | :---- | :---- | :---- |
| **Timeframe** | Pre-2022 | 2022–2024 | 2025–2026 |
| **User Role** | Operator | Prompter / Curator | Supervisor / Architect |
| **AI Role** | Tool (Passive) | Oracle / Generator (Reactive) | Agent / Partner (Proactive) |
| **Input** | Click, Touch, Syntax | Natural Language Prompt | High-level Goal / Policy |
| **Key Metric** | Usability / Efficiency | Output Quality / Relevance | Reliability / Autonomy |
| **Failure Mode** | Error Message | Hallucination | Misalignment / Runaway |
| **Dominant Interface** | GUI (WIMP) | Chat / Conversational UI | Generative UI / Ambient |

### ---

**Table 2: Key HAI Research Themes & Venues (2025-2026)**

| Domain | Key Research Questions | Primary Venues |
| :---- | :---- | :---- |
| **Co-Creativity** | How to support "double diamond" discovery? | CHI, C\&C (Creativity & Cognition) |
| **Agentic UX** | How to design for observability & control? | UIST, arXiv (Industry Labs) |
| **Trust & Safety** | How to measure "interaction harms"? | FAccT, AIES, Anthropic Reports |
| **Hybrid Intelligence** | How to combine human & AI reasoning? | HHAI, IUI |
| **Education/Literacy** | How to teach "prompt literacy"? | CHI, L@S (Learning at Scale) |

#### **Works cited**

1. Full article: The Changing Nature of Human-AI Relations: A Scoping Review on Terminology and Evolvement in the Scientific Literature \- Taylor & Francis, accessed February 1, 2026, [https://www.tandfonline.com/doi/full/10.1080/10447318.2025.2482742](https://www.tandfonline.com/doi/full/10.1080/10447318.2025.2482742)  
2. Towards Interactive Evaluations for Interaction Harms in Human-AI Systems, accessed February 1, 2026, [https://knightcolumbia.org/content/towards-interactive-evaluations-for-interaction-harms-in-human-ai-systems](https://knightcolumbia.org/content/towards-interactive-evaluations-for-interaction-harms-in-human-ai-systems)  
3. The Architecture Behind Autonomous AI Agents \- Core Execution Patterns, accessed February 1, 2026, [https://ashamaei.medium.com/the-architecture-behind-autonomous-ai-agents-core-execution-patterns-c9eead631f79](https://ashamaei.medium.com/the-architecture-behind-autonomous-ai-agents-core-execution-patterns-c9eead631f79)  
4. Embodied AI Workshop at CVPR 2025 \- Microsoft Research, accessed February 1, 2026, [https://www.microsoft.com/en-us/research/event/embodied-ai-workshop-at-cvpr-2025/](https://www.microsoft.com/en-us/research/event/embodied-ai-workshop-at-cvpr-2025/)  
5. AI Didn't Create the Medical Research Crisis—But It's Scaling It | Columbia AI, accessed February 1, 2026, [https://ai.columbia.edu/news/ai-didnt-create-medical-research-crisis-its-scaling-it](https://ai.columbia.edu/news/ai-didnt-create-medical-research-crisis-its-scaling-it)  
6. Introducing Anthropic Interviewer: What 1,250 Professionals Tell Us About Working with AI, accessed February 1, 2026, [https://www.innovativehumancapital.com/article/introducing-anthropic-interviewer-what-1-250-professionals-told-us-about-working-with-ai](https://www.innovativehumancapital.com/article/introducing-anthropic-interviewer-what-1-250-professionals-told-us-about-working-with-ai)  
7. Overview ‹ Atlas of Human-AI Interaction \- MIT Media Lab, accessed February 1, 2026, [https://www.media.mit.edu/projects/atlas-of-human-ai-interaction/overview/](https://www.media.mit.edu/projects/atlas-of-human-ai-interaction/overview/)  
8. Google Research 2025: Bolder breakthroughs, bigger impact, accessed February 1, 2026, [https://research.google/blog/google-research-2025-bolder-breakthroughs-bigger-impact/](https://research.google/blog/google-research-2025-bolder-breakthroughs-bigger-impact/)  
9. The New Collaborative Era: Humans \+ AI in 2026 | Blog | Mindbreeze InSpire, accessed February 1, 2026, [https://www.mindbreeze.com/blog/the-new-collaborative-era-humans-ai-in-2026](https://www.mindbreeze.com/blog/the-new-collaborative-era-humans-ai-in-2026)  
10. Human-AI collaboration is not very collaborative yet: a taxonomy of interaction patterns in AI-assisted decision making from a systematic review \- Frontiers, accessed February 1, 2026, [https://www.frontiersin.org/journals/computer-science/articles/10.3389/fcomp.2024.1521066/full](https://www.frontiersin.org/journals/computer-science/articles/10.3389/fcomp.2024.1521066/full)  
11. A taxonomy of interaction patterns in AI-assisted decision making from a s \- arXiv, accessed February 1, 2026, [https://arxiv.org/pdf/2310.19778](https://arxiv.org/pdf/2310.19778)  
12. Human-Centered Artificial Intelligence \- Emergent Mind, accessed February 1, 2026, [https://www.emergentmind.com/topics/human-centered-artificial-intelligence-hcai](https://www.emergentmind.com/topics/human-centered-artificial-intelligence-hcai)  
13. The double-edged sword effect of generative AI anthropomorphism on users' emotional attachment: the moderating role of task types \- Emerald Publishing, accessed February 1, 2026, [https://www.emerald.com/ajim/article/doi/10.1108/AJIM-03-2025-0125/1331656/The-double-edged-sword-effect-of-generative-AI](https://www.emerald.com/ajim/article/doi/10.1108/AJIM-03-2025-0125/1331656/The-double-edged-sword-effect-of-generative-AI)  
14. Agentic AI: A Review, Applications, and Open Research Challenges \- Preprints.org, accessed February 1, 2026, [https://www.preprints.org/manuscript/202512.0592](https://www.preprints.org/manuscript/202512.0592)  
15. The Rise of the Agentic AI University in 2026 \- UPCEA, accessed February 1, 2026, [https://upcea.edu/the-rise-of-the-agentic-ai-university-in-2026/](https://upcea.edu/the-rise-of-the-agentic-ai-university-in-2026/)  
16. 'Embodied' AI in Virtual Reality Improves Programming Student Confidence, accessed February 1, 2026, [https://news.ncsu.edu/2025/10/embodied-ai-vr-learning/](https://news.ncsu.edu/2025/10/embodied-ai-vr-learning/)  
17. The case against conversational interfaces \- julian.digital, accessed February 1, 2026, [https://julian.digital/2025/03/27/the-case-against-conversational-interfaces/](https://julian.digital/2025/03/27/the-case-against-conversational-interfaces/)  
18. To Trust or to Think: Cognitive Forcing Functions Can Reduce Overreliance on AI in AI-assisted Decision-making \- Intelligent Interactive Systems Group at Harvard, accessed February 1, 2026, [https://iis.seas.harvard.edu/papers/2021/bucinca21trust.pdf](https://iis.seas.harvard.edu/papers/2021/bucinca21trust.pdf)  
19. CHI 2025 – Research Impact & Leadership, accessed February 1, 2026, [https://sites.gatech.edu/research/chi-2025/](https://sites.gatech.edu/research/chi-2025/)  
20. Fourteen papers by CSE researchers at CHI 2025 \- University of Michigan, accessed February 1, 2026, [https://cse.engin.umich.edu/stories/14-papers-by-cse-researchers-at-chi-2025](https://cse.engin.umich.edu/stories/14-papers-by-cse-researchers-at-chi-2025)  
21. HHAI 2025: The 4th International Conference Series on Hybrid Human-Artificial Intelligence, accessed February 1, 2026, [https://hhai-conference.org/2025/](https://hhai-conference.org/2025/)  
22. HCI International 2025, accessed February 1, 2026, [https://2025.hci.international/](https://2025.hci.international/)  
23. AI-HCI: Artificial Intelligence in HCI \- Program, accessed February 1, 2026, [https://2025.hci.international/AI-HCI-program.html](https://2025.hci.international/AI-HCI-program.html)  
24. GenAICHI 2025: Generative AI and HCI at CHI 2025 \- IBM Research, accessed February 1, 2026, [https://research.ibm.com/publications/genaichi-2025-generative-ai-and-hci-at-chi-2025](https://research.ibm.com/publications/genaichi-2025-generative-ai-and-hci-at-chi-2025)  
25. Generative AI and HCI: GenAICHI 2025, accessed February 1, 2026, [https://generativeaiandhci.github.io/](https://generativeaiandhci.github.io/)  
26. Google DeepMind supports US Department of Energy on Genesis: a national mission to accelerate innovation and scientific discovery, accessed February 1, 2026, [https://deepmind.google/blog/google-deepmind-supports-us-department-of-energy-on-genesis/](https://deepmind.google/blog/google-deepmind-supports-us-department-of-energy-on-genesis/)  
27. The Ultimate Guide to AI Design Frameworks in 2025: Choosing the Right Approach for Your Team | by Farzin Raisstousi | Medium, accessed February 1, 2026, [https://medium.com/@farzinraisstousi/the-ultimate-guide-to-ai-design-frameworks-in-2025-choosing-the-right-approach-for-your-team-5ae06336dc58](https://medium.com/@farzinraisstousi/the-ultimate-guide-to-ai-design-frameworks-in-2025-choosing-the-right-approach-for-your-team-5ae06336dc58)  
28. Research Focus: Week of April 21, 2025 \- Microsoft, accessed February 1, 2026, [https://www.microsoft.com/en-us/research/blog/research-focus-week-of-april-21-2025/](https://www.microsoft.com/en-us/research/blog/research-focus-week-of-april-21-2025/)  
29. Guidelines for human-AI interaction design \- Microsoft Research, accessed February 1, 2026, [https://www.microsoft.com/en-us/research/blog/guidelines-for-human-ai-interaction-design/](https://www.microsoft.com/en-us/research/blog/guidelines-for-human-ai-interaction-design/)  
30. Beyond Static AI Evaluations: Advancing Human Interaction Evaluations for LLM Harms and Risks \- arXiv, accessed February 1, 2026, [https://arxiv.org/html/2405.10632v1](https://arxiv.org/html/2405.10632v1)  
31. Which Economic Tasks are Performed with AI? Evidence from Millions of Claude Conversations, accessed February 1, 2026, [https://assets.anthropic.com/m/2e23255f1e84ca97/original/Economic\_Tasks\_AI\_Paper.pdf](https://assets.anthropic.com/m/2e23255f1e84ca97/original/Economic_Tasks_AI_Paper.pdf)  
32. Overview ‹ AHA: Advancing Humans with AI \- MIT Media Lab, accessed February 1, 2026, [https://www.media.mit.edu/groups/aha/overview/](https://www.media.mit.edu/groups/aha/overview/)  
33. Atlas of Human-AI Interaction (v1): An Interactive Meta-Science Platform for Large-Scale Research Literature Sensemaking \- arXiv, accessed February 1, 2026, [https://arxiv.org/html/2509.25499v1](https://arxiv.org/html/2509.25499v1)  
34. Artificial Intelligence Index Report 2025 | Stanford HAI, accessed February 1, 2026, [https://hai.stanford.edu/assets/files/hai\_ai\_index\_report\_2025.pdf](https://hai.stanford.edu/assets/files/hai_ai_index_report_2025.pdf)  
35. Human-Centered AI \- Human-Computer Interaction Institute, accessed February 1, 2026, [https://hcii.cmu.edu/research-areas/human-centered-ai](https://hcii.cmu.edu/research-areas/human-centered-ai)  
36. Most Influential ArXiv (Human-Computer Interaction) Papers (2025-03 Version), accessed February 1, 2026, [https://www.paperdigest.org/2025/03/most-influential-arxiv-human-computer-interaction-papers-2025-03-version/](https://www.paperdigest.org/2025/03/most-influential-arxiv-human-computer-interaction-papers-2025-03-version/)  
37. \[PDF\] Risk or Chance? Large Language Models and Reproducibility in HCI Research, accessed February 1, 2026, [https://www.semanticscholar.org/paper/2af09a939a0a032b8e48327321b9a3338cf85a65](https://www.semanticscholar.org/paper/2af09a939a0a032b8e48327321b9a3338cf85a65)  
38. Consumers don't want chat bots: Thinking about the future UX for AI apps \- Reddit, accessed February 1, 2026, [https://www.reddit.com/r/ArtificialInteligence/comments/1k82rwn/consumers\_dont\_want\_chat\_bots\_thinking\_about\_the/](https://www.reddit.com/r/ArtificialInteligence/comments/1k82rwn/consumers_dont_want_chat_bots_thinking_about_the/)  
39. Watching AI Think: User Perceptions of Visible Thinking in Chatbots \- arXiv, accessed February 1, 2026, [https://arxiv.org/html/2601.16720v1](https://arxiv.org/html/2601.16720v1)  
40. Ambient AI In UX: Interfaces That Work Without Buttons \- Raw.Studio, accessed February 1, 2026, [https://raw.studio/blog/ambient-ai-in-ux-interfaces-that-work-without-buttons/](https://raw.studio/blog/ambient-ai-in-ux-interfaces-that-work-without-buttons/)  
41. Ambient AI Tool Adoption in US Hospitals and Associated Factors \- AJMC, accessed February 1, 2026, [https://www.ajmc.com/view/ambient-ai-tool-adoption-in-us-hospitals-and-associated-factors](https://www.ajmc.com/view/ambient-ai-tool-adoption-in-us-hospitals-and-associated-factors)  
42. From Conversation to Chart: An Analysis of Clinician Edits to Ambient AI Draft Notes, accessed February 1, 2026, [https://www.medrxiv.org/content/10.64898/2026.01.05.26343471v2.full-text](https://www.medrxiv.org/content/10.64898/2026.01.05.26343471v2.full-text)  
43. UX Roundup: 2025 Predictions Revisited | AI Paradigm Shifts | AI and Doctor Burnout | Useful AI Sells \- UX Tigers, accessed February 1, 2026, [https://www.uxtigers.com/post/ux-roundup-20251222](https://www.uxtigers.com/post/ux-roundup-20251222)  
44. AI is finally learning to shut up | by Imran | Bootcamp | Jan, 2026 \- Medium, accessed February 1, 2026, [https://medium.com/design-bootcamp/ai-is-finally-learning-to-shut-up-62af1d2c01c8](https://medium.com/design-bootcamp/ai-is-finally-learning-to-shut-up-62af1d2c01c8)  
45. 7 AI Shifts That Will Shape 2026 — and the Decade Beyond | by Swapnil | DevSecOps & AI, accessed February 1, 2026, [https://medium.com/devsecops-ai/7-ai-shifts-that-will-shape-2026-and-the-decade-beyond-a0834a7efafd](https://medium.com/devsecops-ai/7-ai-shifts-that-will-shape-2026-and-the-decade-beyond-a0834a7efafd)  
46. Prompting Generative AI with Interaction-Augmented Instructions | Request PDF, accessed February 1, 2026, [https://www.researchgate.net/publication/391152771\_Prompting\_Generative\_AI\_with\_Interaction-Augmented\_Instructions](https://www.researchgate.net/publication/391152771_Prompting_Generative_AI_with_Interaction-Augmented_Instructions)  
47. An Empirical Evaluation of Prompting Strategies for Large Language Models in Zero-Shot Clinical Natural Language Processing: Algorithm Development and Validation Study \- JMIR Medical Informatics, accessed February 1, 2026, [https://medinform.jmir.org/2024/1/e55318/](https://medinform.jmir.org/2024/1/e55318/)  
48. Prompting Generative AI with Interaction-Augmented Instructions \- arXiv, accessed February 1, 2026, [https://arxiv.org/html/2503.02874v1](https://arxiv.org/html/2503.02874v1)  
49. GenAI Prompt Literacy in Higher Ed Teaching and Learning \- Lamar University, accessed February 1, 2026, [https://www.lamar.edu/lu-online/instructional-support/blog/2025/10/genai-prompt-literacy-in-higher-ed-teaching-and-learning.html](https://www.lamar.edu/lu-online/instructional-support/blog/2025/10/genai-prompt-literacy-in-higher-ed-teaching-and-learning.html)  
50. Fostering AI Literacy in Undergraduates: A ChatGPT Workshop Case Study \- Digital Commons @ LMU, accessed February 1, 2026, [https://digitalcommons.lmu.edu/cgi/viewcontent.cgi?article=1178\&context=librarian\_pubs](https://digitalcommons.lmu.edu/cgi/viewcontent.cgi?article=1178&context=librarian_pubs)  
51. Full article: How Do Lay Users Seek Information with ChatGPT: An In-Situ Interview Study, accessed February 1, 2026, [https://www.tandfonline.com/doi/full/10.1080/10447318.2025.2586086](https://www.tandfonline.com/doi/full/10.1080/10447318.2025.2586086)  
52. Exploring the Impact of LLM Prompting on Students' Learning \- MDPI, accessed February 1, 2026, [https://www.mdpi.com/2813-4346/4/3/31](https://www.mdpi.com/2813-4346/4/3/31)  
53. An Experimental Comparison of Cognitive Forcing Functions for Execution Plans in AI-Assisted Writing: Effects On Trust, Overreliance, and Perceived Critical Thinking \- arXiv, accessed February 1, 2026, [https://arxiv.org/html/2601.18033v1](https://arxiv.org/html/2601.18033v1)  
54. Emerging Reliance Behaviors in Human-AI Content Grounded Data Generation: The Role of Cognitive Forcing Functions and Hallucinations \- arXiv, accessed February 1, 2026, [https://arxiv.org/html/2409.08937v2](https://arxiv.org/html/2409.08937v2)  
55. Agentic AI patterns and workflows on AWS \- AWS Prescriptive Guidance, accessed February 1, 2026, [https://docs.aws.amazon.com/prescriptive-guidance/latest/agentic-ai-patterns/introduction.html](https://docs.aws.amazon.com/prescriptive-guidance/latest/agentic-ai-patterns/introduction.html)  
56. 2026 is set to be the year of agentic AI, industry predicts \- Nextgov/FCW, accessed February 1, 2026, [https://www.nextgov.com/artificial-intelligence/2025/12/2026-set-be-year-agentic-ai-industry-predicts/410324/](https://www.nextgov.com/artificial-intelligence/2025/12/2026-set-be-year-agentic-ai-industry-predicts/410324/)  
57. 5 Most Popular Agentic AI Design Patterns in 2025 \- Azilen Technologies, accessed February 1, 2026, [https://www.azilen.com/blog/agentic-ai-design-patterns/](https://www.azilen.com/blog/agentic-ai-design-patterns/)  
58. Choose a design pattern for your agentic AI system | Cloud Architecture Center, accessed February 1, 2026, [https://docs.cloud.google.com/architecture/choose-design-pattern-agentic-ai-system](https://docs.cloud.google.com/architecture/choose-design-pattern-agentic-ai-system)  
59. UX Design Considerations for Human AI Agent Interaction \- CLTC Berkeley, accessed February 1, 2026, [https://cltc.berkeley.edu/publication/ux-design-considerations-for-human-ai-agent-interaction/](https://cltc.berkeley.edu/publication/ux-design-considerations-for-human-ai-agent-interaction/)  
60. Risk or Chance? Large Language Models and Reproducibility in HCI Research, accessed February 1, 2026, [https://www.researchgate.net/publication/385364837\_Risk\_or\_Chance\_Large\_Language\_Models\_and\_Reproducibility\_in\_HCI\_Research](https://www.researchgate.net/publication/385364837_Risk_or_Chance_Large_Language_Models_and_Reproducibility_in_HCI_Research)  
61. On LLM Wizards: Identifying Large Language Models' Behaviors for Wizard of Oz Experiments | Request PDF \- ResearchGate, accessed February 1, 2026, [https://www.researchgate.net/publication/382178105\_On\_LLM\_Wizards\_Identifying\_Large\_Language\_Models'\_Behaviors\_for\_Wizard\_of\_Oz\_Experiments](https://www.researchgate.net/publication/382178105_On_LLM_Wizards_Identifying_Large_Language_Models'_Behaviors_for_Wizard_of_Oz_Experiments)  
62. The AI of Oz: A Conceptual Framework for Democratizing Generative AI in Live-Prototyping User Studies \- MDPI, accessed February 1, 2026, [https://www.mdpi.com/2076-3417/15/10/5506](https://www.mdpi.com/2076-3417/15/10/5506)  
63. SRWToolkit: An Open Source Wizard of Oz Toolkit to Create Social Robotic Avatars \- arXiv, accessed February 1, 2026, [https://arxiv.org/html/2509.04356v1](https://arxiv.org/html/2509.04356v1)  
64. The Future of AI in UX : Integrating AI into Design Processes | by Hazal merve akan, accessed February 1, 2026, [https://medium.com/commencis/the-future-of-ai-in-ux-design-a-comprehensive-guide-to-integrating-artificial-intelligence-into-2339f168dd56](https://medium.com/commencis/the-future-of-ai-in-ux-design-a-comprehensive-guide-to-integrating-artificial-intelligence-into-2339f168dd56)  
65. AI‑Powered Prototyping Tools: Guide (2025) \- Parallel HQ, accessed February 1, 2026, [https://www.parallelhq.com/blog/ai-powered-prototyping-tools](https://www.parallelhq.com/blog/ai-powered-prototyping-tools)  
66. 5 Years of AI Design Sprint: Transforming How Businesses Approach Artificial Intelligence, accessed February 1, 2026, [https://nexocode.com/blog/posts/5-years-of-ai-design-sprint-transforming-how-businesses-approach-artificial-intelligence/](https://nexocode.com/blog/posts/5-years-of-ai-design-sprint-transforming-how-businesses-approach-artificial-intelligence/)  
67. A Step-by-Step Guide to AI Design Sprint Hackathons, accessed February 1, 2026, [https://www.designsprint.academy/blog/a-step-by-step-guide-to-ai-design-sprint-hackathons](https://www.designsprint.academy/blog/a-step-by-step-guide-to-ai-design-sprint-hackathons)  
68. Effect of anthropomorphism and perceived intelligence in chatbot avatars of visual design on user experience \- Frontiers, accessed February 1, 2026, [https://www.frontiersin.org/journals/computer-science/articles/10.3389/fcomp.2025.1531976/pdf](https://www.frontiersin.org/journals/computer-science/articles/10.3389/fcomp.2025.1531976/pdf)  
69. The benefits and dangers of anthropomorphic conversational agents \- PNAS, accessed February 1, 2026, [https://www.pnas.org/doi/10.1073/pnas.2415898122](https://www.pnas.org/doi/10.1073/pnas.2415898122)  
70. From robots to chatbots: unveiling the dynamics of human-AI interaction \- PMC, accessed February 1, 2026, [https://pmc.ncbi.nlm.nih.gov/articles/PMC12014614/](https://pmc.ncbi.nlm.nih.gov/articles/PMC12014614/)  
71. 2025 Year in Review: Themes, Trends, Status, Top 10 Articles \- UX Tigers, accessed February 1, 2026, [https://www.uxtigers.com/post/2025-review](https://www.uxtigers.com/post/2025-review)  
72. Full article: Agency in Human-AI Collaboration for Image Generation and Creative Writing: Preliminary Insights from Think-Aloud Protocols, accessed February 1, 2026, [https://www.tandfonline.com/doi/full/10.1080/10400419.2025.2587803](https://www.tandfonline.com/doi/full/10.1080/10400419.2025.2587803)  
73. The top 30 AI leaders to follow in 2025 \- Process Excellence Network, accessed February 1, 2026, [https://www.processexcellencenetwork.com/ai/articles/the-top-30-ai-leaders-in-pex-to-follow-in-2025](https://www.processexcellencenetwork.com/ai/articles/the-top-30-ai-leaders-in-pex-to-follow-in-2025)