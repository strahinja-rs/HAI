---
type: concept
status: seed
created: 2026-02-01
modified: 2026-02-01
author: human
confidence: medium
sources: []
publish: false
tags: [type/concept, domain/design, original]
summary: Any interface where two parties take alternating turns — the broader category that includes chat, button selection, search, and other turn-based patterns.
---

# Turn-Based Interface

## Definition

A turn-based interface is any interaction pattern where two parties take alternating turns. One side acts, then the other side acts, then the first side acts again. This is the broadest category of interactive systems.

## Key Aspects

- Includes chat, but also includes: Google search (query → results → new query), button-based wizards, form submissions, command-line interfaces
- The defining feature is **alternation** — not the *quality* of what happens in each turn
- Contrast with: ambient AI (continuous, not turn-based), direct manipulation (simultaneous, not turn-based), streaming (one-directional)

## What Turn-Based Does NOT Guarantee

- It does not guarantee conversation — Google search is turn-based but not conversational
- It does not guarantee unconstrained responses — a multiple-choice quiz is turn-based but responses are constrained
- It does not guarantee equal participation — one side may always lead

## The Dimensionality Spectrum

Within turn-based interfaces, responses vary in dimensionality:
- **Low-dimensional:** clicking a button, selecting from options — constrained, reductive
- **High-dimensional:** typing free text, speaking — unconstrained, expanding the contextual space

When a turn-based interface has unconstrained response space on both sides, it becomes [[Chat-as-Interaction-Pattern]].

## Connections

- Related concepts: [[Chat-as-Interaction-Pattern]] (the unconstrained subset of turn-based interfaces), [[Adjustable-Autonomy]] (autonomy level determines how much each turn matters)
- Tensions with: ambient AI paradigm (which breaks the turn-based assumption entirely)

## Open Questions

- Is turn-based interaction a fundamental human communication pattern, or an artifact of technology?
- As AI becomes ambient and proactive, does the turn-based paradigm erode?
