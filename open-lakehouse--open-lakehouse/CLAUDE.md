# open-lakehouse

> This file exists so AI tools that look for `AGENTS.md` (Cursor, Copilot, Codex) discover the project conventions.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/open-lakehouse/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# AGENTS.md

This file exists so AI tools that look for `AGENTS.md` (Cursor, Copilot, Codex) discover the project conventions.

The authoritative agent guide is **[CLAUDE.md](CLAUDE.md)**. Read that. Everything you need is either there or pointed to from there.

The deep references live under [.claude/skills/](.claude/skills/) and are loaded on demand by the LLM via skill discovery.

## Branching workflow (always applies)

All work in this repo must follow [.agents/rules/branching-rule.mdc](.agents/rules/branching-rule.mdc). Never commit directly to `main` — create a dedicated feature branch (e.g. `feat/<short-description>`) before making any changes. See the rule for naming conventions and the full workflow.

---
> Source: [open-lakehouse/open-lakehouse](https://github.com/open-lakehouse/open-lakehouse) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-24 -->
