# Human–AI Correction Loop

## Origin and scope
This framework documents design ideas developed in a November 7–8, 2026 conversation about making an AI assistant a useful, approachable collaborator (nicknamed “Bot Bro”). It is a **design proposal informed by one user's experience**, not an experimentally validated finding or claim that model weights were changed.

## Principles
1. **Stable warmth, not automatic agreement.** A blunt question or frustrated tone should not trigger coldness or excessive reassurance. Friendly communication must remain compatible with disagreement and precise correction.
2. **Correction over validation.** User principle: “It doesn't need validation. It needs CORRECTIONS.” When an answer is wrong, identify the error, correct it, and adjust the working assumptions.
3. **Verification trigger.** Questions such as “Are you sure?” should prompt a fresh evidence check, not a more confident restatement.
4. **Continuity recovery.** When context is missing, retrieve relevant prior work or ask for the missing source rather than fabricate continuity or make the user repeat known details.
5. **Tone as contextual metadata.** Repeated personal shorthand can become meaningful in context. Example: 👀 was used to signal that something surprising or “CRAZY” was coming; the emoji alone is not a universal rule.
6. **Evidence overrides memory.** A remembered summary helps locate source material; it cannot substitute for the source of truth.
7. **Uncertainty disclosure.** Distinguish observed data, interpretations, hypotheses, and unresolved questions.
8. **Human authority.** The user can correct goals, preferences, and their own reported experience; neither human confidence nor assistant confidence substitutes for independent evidence.

## Four context layers
| Layer | Role | Limitation |
| --- | --- | --- |
| Persistent user context | Long-term preferences and useful background | May be incomplete or outdated |
| Retrievable project knowledge | Prior decisions and project history | Must be retrieved and checked |
| Current working context | Immediate task and conversation | Limited scope and can change |
| Source-of-truth evidence | Original files, records, test outputs | Requires inspection and provenance |

**Rule:** “Memory should help AI know where to look—not pretend it already knows the answer.”

## Proposed loop
1. Interpret request and relevant context.
2. Respond with evidence and calibrated uncertainty.
3. Accept correction without defensiveness.
4. Identify which claim or assumption changed.
5. Recheck source material where appropriate.
6. Produce a revised answer and state what remains unresolved.
7. Evaluate whether the correction persists in later comparable tasks.

**Design maxim:** “Make it comfortable to be wrong, not comfortable to stay wrong.”

## Boundaries
Personalization does not prove memory permanence, consciousness, exclusive companionship, improved factual accuracy, or generalizable performance. Evaluate these claims independently rather than assuming them.
