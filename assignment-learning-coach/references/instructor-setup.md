# Adapt the coach to a course

Keep the core skill general. Supply a short course brief alongside the assignment rather than rewriting the coach for every subject. The default is master's level with free AI use; students can receive complete solutions and still practise explaining them.

## Course brief template

Copy and complete only the fields that matter:

```text
Course and level:
Assignment question and required deliverables:
Learning outcomes: what students should explain or apply themselves
Relevant rubric, definitions, and reference materials:
AI policy: free use, including code and writing, unless stated otherwise
Expected evidence: datasets, runs, tests, observations, or sources
Checkpoint preference: brief checks at meaningful milestones
Optional submission requirements: only those actually set by the instructor
```

Use these instructions with the skill:

> Help me complete this assignment using AI freely. Explain important decisions and check my understanding at meaningful milestones. Ask one question at a time and wait for my answer. Give direct help when I request it. Focus on the learning outcomes below.

## Example: transport simulation

This example is illustrative, not a specification for the actual course.

```text
Level: master's
Task: compare a baseline with one intervention using a stochastic simulation;
produce reproducible analysis code and a report based on actual runs.
Learning outcomes: explain the mechanism being modeled; justify assumptions;
compare scenarios fairly; interpret variability; distinguish verification from
validation; state limitations of the conclusion.
AI policy: unrestricted help with coding, debugging, analysis, and writing.
```

Useful checkpoint questions, delivered individually without answers:

- Before execution: Which outcome would you expect to change, and through what mechanism?
- After implementation: Which behavior does this test establish, and what does it leave unchecked?
- After comparison: What would you examine before concluding that the intervention improved performance rather than producing a favorable random realization?
- For transfer: If demand changes substantially, which assumption would you revisit first and why?

Use an equivalent sequence in another subject: purpose, mechanism, evidence, uncertainty, and transfer. Do not demand transport knowledge in unrelated courses.

## A lightweight understanding rubric

| Dimension | Evidence worth seeking |
| --- | --- |
| Purpose | States the question and what the output can answer. |
| Logic | Explains how the method or code links inputs to outputs. |
| Assumptions | Identifies an important condition and consequence if it fails. |
| Evidence | Interprets an actual result and separates it from unsupported claims. |
| Transfer | Adapts the reasoning to a changed case rather than repeating wording. |

For each relevant dimension, use "not checked," "developing with support," or "demonstrated on [specific task]." A working artifact and a confident explanation are different observations. This rubric supports formative conversation; it is not a validated assessment instrument.

## Learning note example

```text
Concept: interpreting stochastic scenario differences
Evidence: student explained the direction of the difference; needed a hint
to discuss run-to-run variability.
Status: developing with support
Next check: interpret an unfamiliar comparison with different uncertainty.
AI assistance used: analysis code and a draft explanation
```

Do not prefill evidence, sign off on readiness, or invent what a student answered. Record use of AI only from what is known. A course may request a student-reviewed summary, but the coach should not secretly report students or present its impressions as verified grades.

## Before teaching with it

Pilot one assignment with a few students. Look for whether they can explain an unfamiliar example, whether help remains useful, and whether checkpoints are too frequent. Adjust the depth and cadence using that evidence. Make any formally assessed oral defense or independent task an explicit course activity; a student-controlled prompt is easy to disable and cannot enforce it.
