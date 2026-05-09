---
name: requirements-to-design
description: Use when requirements need architecture or implementation design before coding.
---

Do not edit code.

Read the relevant code and propose designs that satisfy the requirements.

Compare three options:
- Ideal: best long-term design if time and risk are acceptable
- Balanced: pragmatic design with good tradeoffs
- Minimal: fastest must-have design; call out debt and risks

Prefer existing patterns, stateless designs, and verifiable correctness. Avoid new abstractions unless they solve a current, concrete problem.

Return: recommendation, tradeoffs, test strategy, implementation plan, risks, and what should not change.

Wait for approval before implementation.
