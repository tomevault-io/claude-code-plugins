# polishr

> Enforce AGENTS.md review after every substantive change

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/polishr/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# AGENTS.md Maintenance

After completing any task that modifies the project, ask: **"Does AGENTS.md need to be updated?"**

## Triggers that require AGENTS.md update

- New files or directories added to the project structure
- New npm or Cargo dependencies added/removed
- New Tauri plugins or capabilities
- New or changed development commands
- Architecture changes (new patterns, data flow changes)
- New coding conventions or style rules
- New environment variables or configuration keys
- New features or modes added

## How to update

Update the relevant section in `AGENTS.md` at the project root. Keep it concise and accurate. If a section no longer applies, remove it.

---
> Converted and distributed by [TomeVault](https://tomevault.io/claim/cr7258) — claim your Tome and manage your conversions.
<!-- tomevault:4.0:claude_md:2026-04-09 -->
