# Deep Concept Learning Skill

A structured [Agent Skill](https://github.com/anthropics/skills) for [Claude Code](https://code.claude.com/docs/en/skills), [Claude.ai](https://support.claude.com/en/articles/12512198-how-to-create-custom-skills), [OpenAI Codex](https://developers.openai.com/plugins/build/skills), and other compatible AI agents. It teaches complex technical or academic concepts from the ground up using prerequisite breakdowns, real-world analogies, worked examples, common mistakes, 5-minute thinking tasks, practice questions, and a Hinglish recap.

## Quick Install (`npx skills`)

Install directly into Claude Code, OpenAI Codex, Cursor, or 75+ supported agents using the [`npx skills` CLI](https://github.com/vercel-labs/skills):

```bash
npx skills add arshhx000/deep-concept-learning-skill --skill deep-concept-learning
```

To install globally across all your projects:

```bash
npx skills add arshhx000/deep-concept-learning-skill --skill deep-concept-learning -g
```

## How to Use

* **Claude Code**: Type `/deep-concept-learning <topic>` or ask naturally (e.g., *"Teach me how DNS resolution works from scratch"*).
* **OpenAI Codex**: Type `$deep-concept-learning <topic>` or ask naturally to trigger the learning framework.
* **Claude.ai (Web / Desktop)**: Download `skills/deep-concept-learning/SKILL.md`, zip the `deep-concept-learning` folder, and upload it under **Customize > Skills > + Create skill > Upload skill** ([Claude Help Center](https://support.claude.com/en/articles/12512198-how-to-create-custom-skills)).

## What This Skill Does

1. **Checks Prior Knowledge**: Estimates current familiarity and maps how the topic connects to earlier and future concepts.
2. **Builds Layered Foundations**: Explains hidden prerequisite terms from the smallest building blocks before introducing the main concept.
3. **Teaches Through Association**: Connects abstract ideas to everyday analogies and familiar technical systems (UI, databases, apps, workflows).
4. **Reinforces with Examples & Worked Problems**: Provides practical examples, exam-relevant worked solutions, and common student pitfalls.
5. **Trains Active Recall**: Includes 5-minute reasoning tasks, 3–5 graded practice questions (without spoiling answers), a quick English summary, and a natural Hinglish recap.

## License

MIT
