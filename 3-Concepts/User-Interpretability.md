---
type: concept
status: seed
created: 2026-02-01
modified: 2026-02-01
author: human
confidence: medium
sources: []
publish: false
tags: [type/concept, domain/design, domain/relating]
summary: The UX notion that AI output should include explanations of its own formation, enabling users to interpret and trust results.
---

# User Interpretability

## Definition

User interpretability is the UX-facing concern that AI output should be such that the user can interpret it — the output includes an explanation of its own formation. This was the dominant meaning of "interpretability" in HAI before ~2022, focused on questions like "why was my loan denied?" or "why was this recommended?"

## Key Aspects

- Predates [[Mechanistic-Interpretability]] as a research concern
- Rooted in UX and trust: users need to understand AI decisions to appropriately trust, contest, or override them
- Directly connects to real-world stakes: credit decisions, medical diagnoses, hiring filters
- The shift from user interpretability to mechanistic interpretability reflects the field's ontological transformation — from "how do we explain AI to people?" to "how do we understand AI at all?" [Claude: this framing of the shift as ontological is an enhancement — your original observation was that these are "two layers of the same problem"]

## Connections

- Related concepts: [[Mechanistic-Interpretability]], [[Friction-Discernment]] (explanation as productive friction), [[Intent-Expression-Atrophy]] (if users can't interpret AI output, they can't push back on it)
- Tensions with: efficiency (explanations add friction), model complexity (harder to explain as models scale)

## Open Questions

- As models become conversational, does user interpretability shift from "explain this decision" to "I'll just ask it why"? Does conversation itself become the interpretability layer?
