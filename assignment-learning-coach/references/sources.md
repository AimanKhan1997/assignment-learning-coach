# Sources and design decisions

Reviewed 2026-11-03. These are design inspirations, not evidence that this new skill improves learning. The instructions were written for this course use case; no upstream software or service is required.

| Source | Useful idea | Adaptation here |
| --- | --- | --- |
| [multica-ai/andrej-karpathy-skills](https://github.com/multica-ai/andrej-karpathy-skills/blob/main/skills/karpathy-guidelines/SKILL.md) | Explicit assumptions, limited scope, simple implementation, verifiable outcomes. | Make the assignment's meaning and evidence explicit; distinguish artifact checks from understanding checks. |
| [mattpocock/skills: grilling](https://github.com/mattpocock/skills/blob/main/skills/productivity/grilling/SKILL.md) | Questions expose assumptions and decisions. | Ask one learning question at a time without an answer recommendation; keep challenge supportive and bounded. |
| [mattpocock/skills: grill-with-docs](https://github.com/mattpocock/skills/blob/main/skills/engineering/grill-with-docs/SKILL.md) and [domain-modeling](https://github.com/mattpocock/skills/blob/main/skills/engineering/domain-modeling/SKILL.md) | Record resolved terms and reasoning. | Optional compact learning notes instead of mandatory engineering documentation. |
| [mattpocock/skills: teach](https://github.com/mattpocock/skills/blob/main/skills/productivity/teach/SKILL.md) | Goal-related lessons, adaptive challenge, retrieval, and later revisiting. | Anchor questions to the assignment and distinguish immediate supported fluency from independent performance. |
| [AnerGcorp/vibelearn](https://github.com/AnerGcorp/vibelearn) | Generate concept-specific quizzes from real coding work; vary question format and difficulty. | Use only work shared in the current context; no background hooks, cloud sync, numerical mastery model, or automatic scheduling. |
| [MatthewKim07/vibe-learn](https://github.com/MatthewKim07/vibe-learn) | Adjustable help and explain-back interactions. | Respect hints or full-solution preferences while offering understanding checks; do not require a prior attempt. |

Several projects use similar VibeLearn names. Both repositories above were considered; neither is assumed to be the uniquely intended project.

The general design is help -> retrieve -> feedback -> apply to a changed case. It is a practical coaching design, not a claim of measured educational effectiveness. No monitoring backend, assessment verification, account integration, or external dependency is installed.
