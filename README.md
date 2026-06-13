# Swahili Agent Skill

A comprehensive Swahili (Kiswahili) language reference for AI agents — covering grammar, noun classes, verb conjugations, vocabulary, Sheng slang, and the skills.sh ecosystem.

## Features

- **16 noun classes** (ngeli) with agreement patterns
- **Full verb conjugation** — present, past, future, perfect, habitual, negative, subjunctive
- **Grammar** — sentence structure, possessives, demonstratives, relative clauses, narrative tense
- **Vocabulary** — greetings, numbers, days, time, common verbs and phrases
- **Sheng** — East African urban slang dictionary
- **Cultural context** — politeness, proverbs (methali), customs, addressing people
- **skills.sh ecosystem** — how to use `npx skills` CLI, publish skills, and navigate the open skills directory
- **Common mistakes** — time confusion, noun class agreement, negation patterns

## Usage

This skill auto-activates when an AI agent detects Swahili language input. Add it to any compatible AI agent:

```bash
npx skills add abnormal-yi/swahili-skill
```

Or clone and copy manually:

```bash
git clone https://github.com/abnormal-yi/swahili-skill.git
cp swahili-skill/SKILL.md ~/.agents/skills/swahili/
```

## Compatibility

Works with any agent that supports `SKILL.md`-based skills:

- Claude Code
- Cursor
- Codex (OpenCode)
- GitHub Copilot
- Windsurf
- Gemini CLI
- Cline
- AMP

## Repository Structure

```
swahili-skill/
├── SKILL.md       # Main skill reference
└── README.md      # This file
```

## Contributing

Pull requests welcome — especially for additional vocabulary, Sheng terms, proverbs, or grammatical corrections.

## License

MIT
