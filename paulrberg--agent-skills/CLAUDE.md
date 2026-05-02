# agent-skills

> Collection of agent skills for Claude Code, Codex, etc. See @README for full details.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/agent-skills/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Agent Skills

Collection of agent skills for Claude Code, Codex, etc. See @README for full details.

## Rules

- When the user asks to create, edit, or remove a skill while the current working directory is this repo, modify the skill(s) here only (not globally)
- When a skill is added or removed, update the skills table in @README
- Bash scripts must be compatible with Bash v3.2 (`/bin/bash`), because Codex uses the built-in Bash by default
- In SKILL.md frontmatter, sort fields alphabetically but always place `description` last

---
> Source: [PaulRBerg/agent-skills](https://github.com/PaulRBerg/agent-skills) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-04-29 -->
