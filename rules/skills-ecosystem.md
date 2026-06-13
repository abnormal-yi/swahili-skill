---
title: Skills Ecosystem (Mfumo wa Skills.sh)
impact: LOW
impactDescription: Reference for navigating the open agent skills ecosystem
tags: skills.sh, npx-skills, vercel, ecosystem
---

## Skills Ecosystem

### What is skills.sh?

[skills.sh](https://skills.sh) is the **open directory for AI agent skills**, operated by Vercel. It indexes every public skill shipped through the open skills CLI and ranks them by anonymous install telemetry.

### npx skills CLI Reference

| Command | Description |
|---------|-------------|
| `npx skills find <query>` | Search for skills |
| `npx skills add <package>` | Install a skill |
| `npx skills check` | Check for updates |
| `npx skills update` | Update all skills |
| `npx skills init` | Create a new skill |
| `npx skills list` | List installed skills |
| `npx skills remove <package>` | Remove a skill |

### Flags

| Flag | Meaning |
|------|---------|
| `-g` | Global installation |
| `-y` | Skip confirmation |

### Publishing a Skill

1. Create: `npx skills init skill-name`
2. Write `SKILL.md` at repo root
3. Push to a public GitHub repo
4. skills.sh indexes automatically

### Supported Agents

Claude Code, Cursor, Codex, GitHub Copilot, Windsurf, Gemini, Cline, AMP, Antigravity, ClawdBot

Reference: [Skills Ecosystem in SKILL.md](#skills-ecosystem)
