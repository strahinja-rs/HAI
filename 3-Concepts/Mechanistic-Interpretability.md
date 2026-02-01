---
type: concept
status: seed
created: 2026-02-01
modified: 2026-02-01
author: human
confidence: medium
sources: []
publish: false
tags: [type/concept, domain/safety, domain/technical]
summary: Understanding AI by examining the internals of neural networks — correlating outputs with activation patterns.
---

# Mechanistic Interpretability

## Definition

Mechanistic interpretability is the study of AI model internals — looking directly into neural networks to find correlations between outputs and the firing patterns of individual neurons and circuits. Researchers examine where networks activate and how they behave when producing specific outputs. The analogy is neuroscience: studying the brain itself rather than asking the patient what they think.

## Key Aspects

- Emerged as a distinct research program post-2022 (notably at Anthropic, but also DeepMind and others)
- Concerned with *safety and science* — understanding what models actually do, not just what they appear to do
- Distinct from [[User-Interpretability]], which is the UX-facing concern of explaining decisions to users
- These two form layers of the same problem: one looks inward (mechanisms), the other looks outward (communication to humans) [Claude: this "two layers" framing is your original observation from Session 2]

## Connections

- Related concepts: [[User-Interpretability]], [[Interaction-Field]] (knowing what's happening inside the "other" participant)
- Tensions with: speed of deployment (interpretability research is slower than capability research)

## Open Questions

- Can mechanistic interpretability eventually *feed into* user interpretability — i.e., can understanding model internals produce better explanations for users?
- Does the gap between these two layers widen or narrow as models scale?
