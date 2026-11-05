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

## Course profile: KTH AH2174

**Traffic Simulation Modelling and Applications, 7.5 credits.** Master's level (second cycle).

Source: [KTH's official AH2174 course page](https://www.kth.se/student/kurser/kurs/AH2174?l=en), checked 2026-11-05. The page identifies the syllabus as effective from Spring 2026. The five outcomes below are faithful paraphrases of its intended learning outcomes, not verbatim quotations. The coaching questions and evidence examples are proposed teaching aids, not official KTH assessment criteria.

| Intended learning outcome (paraphrased) | Example understanding question | Observable evidence to look for |
| --- | --- | --- |
| ILO 1: Explain foundational simulation concepts and put them into practice. | How does your model turn its inputs into the output you are studying, and where does randomness enter? | The student connects the problem, representation, simulation mechanism, and important assumptions using their actual assignment. |
| ILO 2: Make sense of output from stochastic simulations and evaluate it analytically. | What evidence would distinguish an intervention effect from a favorable random realization? | The student interprets a result in context and justifies relevant replication, variability, and uncertainty analysis. |
| ILO 3: Choose a model and simulation approach suited to the application. | Why is this approach suitable for this question, and when would an alternative be preferable? | The student explains the choice using the required detail, available data, assumptions, and computational demands. |
| ILO 4: Obtain empirical observations and use them to tune and assess transport simulators. | Which observations would you use for calibration, and how would you assess performance beyond the observations used for tuning? | The student distinguishes calibration from validation, explains data quality and parameter choices, and proposes an appropriate independent check where feasible. |
| ILO 5: Use simulation to compare scenarios, forecast outcomes, and search for improved decisions. | How would you design a fair scenario comparison, and what limits would you place on a prediction or optimized decision? | The student links scenarios to objectives and constraints, explains the experiment, and interprets results within the model's scope. |

ILO numbers are local identifiers for this coaching profile; the official page lists these outcomes as bullets. Topics such as seed control, warm-up, sensitivity, verification, and uncertainty are examples for teaching these outcomes when relevant, not additional official outcomes or universal assignment requirements.

### Ready-to-use AH2174 course brief

```text
Course: KTH AH2174, Traffic Simulation Modelling and Applications, 7.5 credits
Level: master's / second cycle
Learning outcomes: use the five paraphrased ILOs in this course profile.
Assignment: use the actual supplied assignment and rubric; do not invent them.
AI policy: the instructor permits unrestricted AI assistance with code,
debugging, analysis, and writing. This permission is instructor supplied;
it is not inferred from the public course page.
Evidence: use actual datasets, model choices, simulation configurations,
executed runs, analysis outputs, and report claims shared by the student.
Checkpoints: brief checks at meaningful milestones, one question at a time.
```

The public course page also expects students to disclose assistance and sources honestly, take responsibility for group work, and be able to discuss the complete solution in an oral assessment. Free AI use can coexist with these expectations. Help students describe the assistance actually used and practise explaining the whole assignment; do not invent disclosure formats, impose an oral examination, or claim that the coach verifies compliance.

### Align a session with the outcomes

Select the ILOs relevant to the supplied assignment or current milestone. State the connection briefly, such as "This comparison practises ILO 2 and ILO 5." Do not assume every assignment addresses every ILO, or require five quizzes for each task.

After useful assistance, choose one question grounded in the student's own code, results, or report. Use the table as a starting point; adapt it to the artifact and wait for the student's reply. Ask a changed-case question after feedback where useful. For example, vary demand, a parameter, data availability, or the objective and ask which part of the reasoning changes.

If a learning note is useful, associate its evidence with the relevant ILO. Keep "not checked," "developing with support," and "demonstrated on [specific task]" distinct. A passing test, a completed simulation, or an AI-written report does not establish that an outcome has been achieved. Never infer course completion or an official grade from the conversation.

For another course, replace this profile with that course's outcomes and source while retaining the general template and coaching method. Do not apply AH2174's transport-specific content to unrelated courses.

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
