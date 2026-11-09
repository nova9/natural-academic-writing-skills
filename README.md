# Natural Academic Writing

An agent skill for drafting, revising, and reviewing academic prose while preserving meaning, evidence, and the author's voice.

Use it for research papers, theses, literature reviews, abstracts, reports, and individual paragraphs. It helps improve clarity, organization, and sentence flow while preserving technical terminology, citations, numerical values, and appropriate uncertainty.

## Install

With Node.js and npm installed, run:

```bash
npx skills add nova9/natural-academic-writing-skills
```

Follow the prompts to choose your agent and installation scope. To install only this skill:

```bash
npx skills add nova9/natural-academic-writing-skills --skill natural-academic-writing
```

Add `-g` to install across projects. See the [Skills CLI documentation](https://github.com/vercel-labs/skills) for supported agents and options.

## Usage

Ask your agent to use `natural-academic-writing` and provide the text or notes to work from. Include any word limit, audience, venue requirements, or style guide.

Example requests:

- “Use natural-academic-writing to revise this abstract for clarity. Preserve all claims and citations, and keep it under 250 words.”
- “Review this introduction for unclear reasoning and unsupported claims. Give feedback without rewriting it.”
- “Draft a methods section from these notes. Flag missing details instead of inventing them.”
- “Make this paragraph less formulaic while preserving my terminology and level of certainty.”

The skill prioritizes faithful editing and evidence. It does not invent sources, findings, or data, and it does not optimize for AI-detector scores. Language editing does not establish factual accuracy or verify references.

## Skill source

The instructions live in [`.agents/skills/natural-academic-writing/SKILL.md`](.agents/skills/natural-academic-writing/SKILL.md).

## Contributing

Issues and pull requests are welcome. For proposed editing rules, include an example and explain how the change improves clarity without changing the author's meaning.

## License

[MIT](LICENSE).
