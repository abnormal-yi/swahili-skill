# Swahili Agent Skill


## Structure

```
swahili-skill/
├── SKILL.md              # Main skill reference
├── AGENTS.md             # Compiled quick reference
├── README.md             # This file
├── metadata.json         # Version, tags, organization
├── rules/                # Individual topic rules
│   ├── _template.md      # Template for new rules
│   ├── noun-classes.md   # 16 noun classes & agreement
│   ├── verb-conjugation.md # All tenses, negation, object infixes
│   ├── vocabulary.md     # Greetings, verbs, numbers, days, time
│   ├── grammar.md        # Sentence structure, possessives, demonstratives
│   ├── sheng.md          # Swahili-English urban slang
│   ├── cultural-context.md # Politeness, proverbs, addressing people
└── src/                  # Build scripts (future)
```

## Usage

```bash
npx skills add abnormal-yi/swahili-skill
```

Or clone directly:

```bash
git clone https://github.com/abnormal-yi/swahili-skill.git
cp swahili-skill/SKILL.md ~/.agents/skills/swahili/
```

## Topics

- **16 noun classes** — M-/WA-, M-/MI-, JI-/MA-, KI-/VI-, N-/N-, U-, PA-, KU-, MU-
- **Verb conjugation** — present, past, future, perfect, habitual, subjunctive, conditional, negation
- **Object infixes** — -ni-, -ku-, -m-, -tu-, -wa-, -ki-
- **Core vocabulary** — 100+ words (greetings, verbs, numbers, days, time)
- **Grammar** — SVO, adjective agreement, possessives, demonstratives, relative clauses
- **Sheng** — 15+ East African urban slang terms
- **Cultural context** — Shikamoo, methali (proverbs), etiquette, titles
- **Common mistakes** — 10 frequent errors with corrections

## Compatibility

Claude Code, Cursor, Codex, GitHub Copilot, Windsurf, Gemini CLI, Cline, AMP

## License

MIT
