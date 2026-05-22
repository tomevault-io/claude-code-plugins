# agent-skills

> Public shared skills for agent workflows.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/agent-skills/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# AGENTS.md

Public shared skills for agent workflows.

## Rules

- Canonical shared skills live under `skills/<name>/SKILL.md`.
- Keep repo-specific workflows out unless they are useful as public examples.
- Keep secrets, private hostnames, private account IDs, and private URLs out.
- Skill descriptions: short trigger phrase, not full documentation.
- Skill bodies: operational, terse, current.
- Helper scripts belong under `skills/<name>/scripts/`.
- Validate after edits: `scripts/validate-skills`.
- Do not edit generated/vendor copies in downstream repos; update here, then sync.

## Layout

- `skills/autoreview`: shared closeout/code-review helper.
- `skills/crabbox`: shared Crabbox/Testbox remote validation workflow.

---
> Source: [openclaw/agent-skills](https://github.com/openclaw/agent-skills) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-22 -->
