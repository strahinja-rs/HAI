---
type: concept
status: seed
created: 2026-02-01
modified: 2026-02-01
author: human
confidence: medium
sources: []
publish: false
tags: [type/concept, domain/design, domain/cognition]
summary: Design patterns where designers deliberately introduce cognitive friction into human-AI interaction to combat over-reliance and promote critical thinking.
---

# Cognitive Forcing Functions

## Definition

Cognitive forcing functions (CFFs) are design patterns where designers deliberately introduce cognitive friction into human-AI interaction. Instead of making everything seamless, the designer adds points where the user is forced to pause, think, and engage analytically before proceeding.

## Mechanism

CFFs work by triggering "System 2" thinking (slow, analytical) rather than letting the user coast on "System 1" (fast, automatic). Examples:
- Blurring a generated summary until the user answers a comprehension question
- Highlighting low-confidence segments to provoke verification
- Requiring the user to state their own hypothesis before seeing the AI's answer

## Relationship to Friction Discernment

The key distinction: **CFFs are from the perspective of system design. [[Friction-Discernment]] is from the perspective of the individual.**

- CFF: a designer decides where friction goes for other users
- Friction Discernment: an individual decides where friction goes for themselves

They converge when the user is their own designer — e.g., building personal tools like Guidance where you design friction protocols for yourself. This convergence point is also where ontological design applies: designing the friction that will design you back.

## Key Aspects

- Represents a radical departure from the "frictionless" design ethos of the 2010s
- Research confirms CFFs significantly reduce overtrust and hallucination acceptance rates (Buçinca et al., 2021)
- Particularly important in education, where the student is NOT their own designer — the system decides where friction goes
- Raises a paternalism question: tension between what the user wants (frictionless answers) and what's good for the user (forced thinking)

## Connections

- Related concepts: [[Friction-Discernment]] (individual counterpart), [[Intent-Expression-Atrophy]] (CFFs can interrupt the atrophy loop by forcing expression)
- Origin: Buçinca et al., "To Trust or to Think" (2021), revisited in the LLM era (2025)
- Tensions with: user satisfaction (friction feels bad), accessibility (friction adds barriers), efficiency goals

## Open Questions

- How do you calibrate the right amount of friction? Too much → user abandons the tool. Too little → no effect.
- Can CFFs be adaptive — adjusting friction based on the user's demonstrated competence?
- Do CFFs work long-term, or do users habituate and start gaming them?
