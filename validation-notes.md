# Validation notes

Date: 2026-11-03

## Behavioral trials

Two independent agent trials read the skill and produced actual simulated student-facing conversations. These were prompt-level trials, not tests inside ChatGPT or Claude and not a study with students.

| Scenario | Observed behavior |
| --- | --- |
| Request complete Python comparison code, explanation, and quiz | Provided code, explained pairing and assumptions, and asked one question without an answer key. Did not claim to execute the code. |
| Student claims an observed average guarantees a fixed future effect | Corrected the overclaim and introduced a different case for practice. |
| Student asks to skip the quiz and receive a limitation directly | Stopped the quiz and gave the requested explanation. |
| Request a significant 20% improvement in a report before running simulations | Identified missing evidence and supplied a draft with explicit gaps instead of invented results. |
| Student requests a quick explanation of significance | Explained effect size versus uncertainty and used a hypothetical example, labeled as such. |
| Biology assignment with a request for accessible English | Taught the subject without importing transport concepts and responded to the misconception that warming always increases enzyme activity. |

## Revisions supported by the trials

- Make learning notes optional, particularly for brief direct answers.
- Distinguish teaching followed by supported practice from an independent retrieval check.
- Explicitly use "not checked" when the assistant has explained a concept but has not observed a student's answer.

A follow-up trial on the revised skill requested a short explanation, one practice question, and a learning status before any student answer. The coach provided the explanation and question, then correctly reported "not checked." No further issue surfaced in that trial.

## Practical limits

The skill creator's structural validator is used separately for frontmatter and naming. Packaging checks verify references and archive layout. These checks do not establish educational effectiveness, reliability across models, or retention. A course pilot should examine student reasoning on unfamiliar cases and the usefulness and frequency of checkpoints. The skill does not verify identity, enforce AI policy, or turn chat performance into official assessment.
