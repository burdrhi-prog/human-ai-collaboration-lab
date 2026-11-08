# Human–AI Collaboration Lab 🤖

**Human-in-the-Loop AI Evaluation · Adaptive Interaction Design · Correction Loops · Context Integrity**

> **Status:** Research framework and synthetic evaluation scenarios documented. No performance experiment has been run yet.

## The idea
What if an AI assistant could remain warm and approachable **without becoming agreeable at the expense of accuracy**? This independent project translates practical collaboration lessons from a November 7–8, 2026 conversation—nicknamed the **Bot Bro** experiment—into testable interaction requirements.

**“It doesn't need validation. It needs CORRECTIONS.”**

**“Make it comfortable to be wrong, not comfortable to stay wrong.”**

## The problem
AI assistants can repeat errors, lose context, respond defensively to correction, or sound confident when evidence is incomplete. Personalization alone does not solve these problems. A better workflow needs explicit verification triggers, correction handling, source priority, and transparent uncertainty.

## Framework at a glance

```text
User request + context
         |
         v
Evidence-aware response
         |
         v
User feedback / "Are you sure?"
         |
         v
Identify mistaken assumption
         |
         v
Verify source and revise
         |
         v
Check whether correction persists
```

### Four layers of context
1. **Persistent user context:** useful preferences, not proof.
2. **Retrievable project knowledge:** earlier decisions to look up and check.
3. **Current working context:** immediate task state.
4. **Source-of-truth evidence:** inspected records and reproducible outputs.

**Memory should help AI know where to look—not pretend it already knows the answer.**

## Practical collaboration case study
[From GitHub terminology barriers to a four-project portfolio](docs/real-world-workflow-case-study.md) documents the actual workflow outcome without claiming controlled AI performance improvements.

## Explore the project
- [Human–AI Correction Loop](docs/correction-loop.md) — principles, flow, and boundaries.
- [Evaluation plan](docs/evaluation-plan.md) — comparison conditions and scoring rubric.
- [Synthetic scenarios](examples/synthetic-scenarios.csv) — six fictional test cases.
- [Employer-facing skills](docs/portfolio-positioning.md) — transferable competencies and claim boundaries.

## Planned evaluation
Compare baseline and correction-loop instructions on identical synthetic scenarios. Score correction accuracy, evidence calibration, context handling, tone consistency, and actionability. Record model settings, multiple runs, and failure cases.

**No improvement claims yet:** This repository currently contains the proposed method and test materials, not measured results.

## Privacy and integrity
Real private conversations and investigation records are not published. Synthetic examples illustrate the concepts. The project does not claim to change model weights, guarantee memory, or establish broad scientific conclusions.

*Independent applied AI evaluation project. Designed to demonstrate requirements writing, quality assessment, iterative feedback, and evidence-conscious workflow design.*
