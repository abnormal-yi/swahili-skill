# Swahili Agent Skill

A comprehensive Swahili (Kiswahili) language reference for AI agents — covering grammar (sarufi), noun classes (ngeli), verb conjugations, vocabulary (msamiati), Sheng slang, East African tech/business/tourism terminology, and cultural context.

## Structure

```
swahili-skill/
├── SKILL.md                       # Main skill reference
├── AGENTS.md                      # Compiled quick reference
├── README.md                      # This file
├── LICENSE                         # MIT license
├── metadata.json                  # Version, tags, organization
└── rules/                          # Individual topic rules
    ├── _template.md               # Template for new rules
    ├── noun-classes.md            # 16 noun classes & agreement
    ├── verb-conjugation.md        # All tenses, negation, imperatives, modals
    ├── vocabulary.md               # Greetings, verbs, numbers, days, time
    ├── tech-business-vocabulary.md # Web dev, WordPress, business, tourism/safari terms
    ├── grammar.md                  # Sentence structure, relative clauses, questions
    ├── sheng.md                    # Swahili-English urban slang + TZ Bongo slang
    └── cultural-context.md         # Politeness, proverbs, etiquette, titles
```

## Usage

```bash
npx skills add abnormal-yi/swahili-skill
```

Or clone directly:

```bash
git clone https://github.com/abnormal-yi/swahili-skill.git
cp -r swahili-skill/* ~/.agents/skills/swahili/
```

## Topics

- **16 noun classes** — M-/WA-, M-/MI-, JI-/MA-, KI-/VI-, N-/N-, U-, PA-, KU-, MU-
- **Verb conjugation** — present, past, future, perfect, habitual, subjunctive, conditional, imperative, modal obligation, negation
- **Object infixes** — -ni-, -ku-, -m-, -tu-, -wa-, -ki-
- **Core vocabulary** — greetings, verbs, numbers, days, time
- **Tech/business/tourism vocabulary** — WordPress & web dev terms, client communication, safari/tourism terminology, realistic code-switched phrases
- **Grammar** — SVO, adjective agreement, possessives, demonstratives, relative clauses, question formation, negation of "to be/have"
- **Sheng** — East African urban slang plus Tanzanian Bongo slang, with regional (TZ vs KE) notes
- **Cultural context** — Shikamoo, methali (proverbs), etiquette, titles, business/digital communication norms
- **Common mistakes** — frequent errors with corrections

## Compatibility

Claude Code, Cursor, Codex, GitHub Copilot, Windsurf, Gemini CLI, Cline, AMP

## License

MIT
