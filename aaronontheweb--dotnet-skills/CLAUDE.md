# dotnet-skills

> This repo supports both Claude Code and OpenCode.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/dotnet-skills/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# AGENTS.md

This repo supports both Claude Code and OpenCode.

When adding/removing skills or agents, keep the router/index snippets up to date so downstream repos can copy/paste them.

Reference:
- `skills/meta/skills-index-snippets/SKILL.md`

Maintenance:
1. Update `.claude-plugin/plugin.json`
2. Run `./scripts/validate-marketplace.sh`
3. Regenerate the compressed index: `./scripts/generate-skill-index-snippets.sh`

---
> Source: [Aaronontheweb/dotnet-skills](https://github.com/Aaronontheweb/dotnet-skills) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-04-20 -->
