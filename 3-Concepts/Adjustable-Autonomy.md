---
type: concept
status: seed
created: 2026-02-01
modified: 2026-02-01
author: human
confidence: medium
sources: []
publish: false
tags: [type/concept, domain/design, domain/agency]
summary: A design pattern that allows users to dial up or down an AI agent's autonomy based on their trust level and the type of task.
---

# Adjustable Autonomy

## Definition

Adjustable autonomy is a design pattern in human-AI interaction that allows users to tune, control, and dial up or down the autonomy of an AI agent. The user controls how independently the agent acts, based on the trust they have in the agent for specific types of tasks.

## How It Works

The user sets different autonomy levels for different activities:
- **Autopilot** — agent acts independently, user gets notifications (e.g., scheduling meetings)
- **Co-pilot** — agent drafts, user reviews and approves (e.g., writing emails)
- **Manual** — user directs every step, agent assists (e.g., high-stakes financial decisions)

The same user might use all three modes within a single session, shifting between them fluidly.

## Key Aspects

- Resolves the **control-autonomy paradox**: users want the convenience of autonomy but fear the loss of control. Adjustable autonomy lets them have both, calibrated per task.
- The mechanism that enables **interaction patterns to mix freely** — directive, feedback loop, task iteration, and delegation aren't fixed modes but points on the autonomy dial
- Trust is the input variable: higher trust → more autonomy. Trust varies by task type, not just by overall confidence in the system.
- Maps to the HITL/HOTL spectrum: Human-in-the-loop (low autonomy) → Human-on-the-loop (supervisory) → Human-out-of-the-loop (audit only)

## Connections

- Related concepts: [[Friction-Discernment]] (choosing autonomy level IS a friction discernment decision — more autonomy = less friction), [[Cognitive-Forcing-Functions]] (CFFs can be built into the autonomy transitions — e.g., requiring confirmation before escalating to autopilot), [[Interaction-Field]] (autonomy level shapes the quality of the field)
- Tensions with: efficiency (constant adjustment is overhead), user skill (novice users may not know when to dial down)

## Open Questions

- Should the system suggest autonomy levels, or should the user always set them manually?
- Can the agent itself request more or less autonomy based on its confidence? (Negotiated control)
- What happens when users set autonomy too high for their competence level? Who's responsible for the outcome?
