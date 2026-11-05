# Assignment Learning Coach

**Use AI freely. Understand the work you submit.**

A portable AI coaching skill for students working on coding assignments, lab reports, and analyses. It combines complete AI assistance with short, adaptive checks on the purpose, logic, assumptions, evidence, and limitations of an assignment.

Designed with a master's-level transport-simulation course in mind, while keeping the core instructions general enough for other subjects and levels.

## What it does

- Provides full code, debugging, analysis, and writing assistance when requested.
- Explains important choices and connects implementation to the assignment's purpose.
- Offers brief quizzes at meaningful milestones, asking one question at a time and waiting for an answer.
- Gives specific feedback, explains misconceptions, and checks transfer to a changed example.
- Distinguishes working code from student understanding, and observed results from unsupported claims.
- Adapts difficulty and respects requests for hints, direct explanations, or a pause in quizzing.

The default is unrestricted AI use. Students do not have to pass a quiz or attempt a task before receiving help. Supplied course rules can configure a different policy.

## Quick start: ChatGPT or a regular Claude chat

Paste [student-coach-instructions.md](student-coach-instructions.md) into a new chat, then provide the assignment, rubric, and relevant work:

> Help me complete this assignment using AI freely and understand the main logic. Explain important choices and quiz me briefly at meaningful milestones, one question at a time. Here is my assignment and what I have so far: ...

For repeated use in ChatGPT, add the instructions file to a project and put this in the project instructions:

> Use student-coach-instructions.md as my learning-coach instructions. Help with code and writing, explain important decisions, and offer short understanding checks. Ask one question at a time and wait for my answer. Respect requests for direct help or to pause the quiz.

Start related chats inside the project. See [OpenAI's project documentation](https://learn.chatgpt.com/docs/projects?surface=app).

## Claude custom skill

Download [assignment-learning-coach.zip](assignment-learning-coach.zip), then upload and enable it through **Customize > Skills > Create skill > Upload a skill**, where available. Skills require the relevant account capabilities and organizational permissions. See [Claude's skill guide](https://support.claude.com/en/articles/12512180-use-skills-in-claude).

The ZIP contains the named skill folder, its instructions, references, metadata, and MIT license. No API key, external quiz service, background watcher, or plugin dependency is required by the skill.

## Codex and other skill-compatible tools

Copy the [assignment-learning-coach](assignment-learning-coach) directory into your tool's skills directory. For a personal Codex installation, use `~/.codex/skills/assignment-learning-coach/`, then invoke `$assignment-learning-coach`.

The skill is automatically discoverable for student coaching tasks. It should not turn unrelated professional work into a lesson. A regular-chat fallback is always available through the standalone instructions file.

## For instructors

Use the [course configuration guide](assignment-learning-coach/references/instructor-setup.md) to supply learning outcomes, assignment requirements, and evidence expectations. It includes a transport-simulation example and a small formative rubric.

A useful checkpoint sequence is:

1. Explain the question and the approach.
2. Predict or trace what the code or method will do.
3. Interpret an actual result and its uncertainty.
4. Apply the idea to a changed case.

Each question is delivered separately. The coach offers explanations when the student is stuck; it does not turn the interaction into an endless interrogation.

## Scope and validation

This is a formative learning aid. A student-controlled prompt cannot enforce participation, authenticate independent work, certify learning, or replace an instructor's assessment. Student records remain in the conversation unless saving is requested or configured; the skill does not secretly report to instructors.

[Validation notes](validation-notes.md) describe structural checks and simulated student conversations. These are not a real-student study or evidence of improved learning outcomes. Pilot the skill in your course and adjust question depth and frequency based on student experience.

## Inspiration and attribution

The design considers [andrej-karpathy-skills](https://github.com/multica-ai/andrej-karpathy-skills), [Matt Pocock's teaching and grilling skills](https://github.com/mattpocock/skills), [AnerGcorp/VibeLearn](https://github.com/AnerGcorp/vibelearn), and [MatthewKim07/vibe-learn](https://github.com/MatthewKim07/vibe-learn).

These are design inspirations. Their software is not bundled, and this project does not require their services.

## License

[MIT](LICENSE). Copyright (c) 2026 AimanKhan1997.
