# Swahili Agent Skill — Compiled Reference

> Compiled from `rules/` — for AI agent consumption.

## Overview

Swahili (Kiswahili) is a Bantu language spoken by over 200 million people in East and Central Africa. This skill covers grammar (sarufi), noun classes (ngeli), verb conjugations (vitenzi), vocabulary (msamiati), Sheng slang, cultural context, and the skills.sh ecosystem.

**Trigger:** User speaks Swahili or Sheng. User asks for translation, grammar help, or culturally appropriate East African communication.

## Sections

| Section | File | Impact |
|---------|------|--------|
| Noun Classes | `rules/noun-classes.md` | HIGH |
| Verb Conjugation | `rules/verb-conjugation.md` | HIGH |
| Core Vocabulary | `rules/vocabulary.md` | MEDIUM-HIGH |
| Tech/Business/Tourism Vocabulary | `rules/tech-business-vocabulary.md` | HIGH |
| Sentence Structure | `rules/grammar.md` | MEDIUM-HIGH |
| Sheng | `rules/sheng.md` | MEDIUM |
| Cultural Context | `rules/cultural-context.md` | MEDIUM |
| Skills Ecosystem | `rules/skills-ecosystem.md` | LOW |

## Quick Reference

### Subject Prefixes
| Person | Prefix | Present | Past | Future |
|--------|--------|---------|------|--------|
| Mimi (I) | ni- | ninasoma | nilisoma | nitasoma |
| Wewe (you sg) | u- | unasoma | ulisoma | utasoma |
| Yeye (he/she) | a- | anasoma | alisoma | atasoma |
| Sisi (we) | tu- | tunasoma | tulisoma | tutasoma |
| Ninyi (you pl) | m- | mnasoma | mlisoma | mtasoma |
| Wao (they) | wa- | wanasoma | walisoma | watasoma |

### Negation
| Tense | Pattern | Example |
|-------|---------|---------|
| Present | si- + stem + -i | sisomi |
| Past | si- + ku- + stem | sikusoma |
| Future | si- + ta- + stem | sitasoma |
| Perfect | si- + ja- + stem | sijasoma |

### Noun Class Agreement
| Class | Example | Adjective | Possessive |
|-------|---------|-----------|------------|
| 1 M- | mtu | mzuri | wangu |
| 2 WA- | watu | wazuri | wangu |
| 7 KI- | kitu | kizuri | changu |
| 8 VI- | vitu | vizuri | vyangu |
| 9 N- | nyumba | nzuri | yangu |

### Key Greetings
| Swahili | Context |
|---------|---------|
| Shikamoo | To elder/authority |
| Marahaba | Reply to Shikamoo |
| Habari | General hello |
| Mambo? | Casual/Sheng |
| Poa / Fresh | Casual reply |

### Common Mistakes
1. **Time shift**: Saa moja = 7 AM (not 1 AM — Swahili time is +6)
2. **Class agreement**: kitu **mzuri** ❌ → kitu **kizuri** ✅
3. **Stative verbs**: "ninajua" ❌ → "najua" ✅
4. **Sheng vs Standard**: Use standard Swahili for formal contexts
5. **Negation form**: "sikusoma" for past, not present

### Verification Checklist
- [ ] Noun class agreement throughout
- [ ] Correct tense marker
- [ ] Proper negation pattern
- [ ] Register: formal vs casual/Sheng
- [ ] Cultural appropriateness (Shikamoo for elders, right hand for giving)

---

See individual files in `rules/` for detailed reference.
