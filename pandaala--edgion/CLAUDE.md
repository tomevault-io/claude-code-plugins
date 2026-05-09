# 00-edgion-entry

> Repository entry rule for Edgion. Keep Cursor aligned with AGENTS.md and the skills-based knowledge map.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/00-edgion-entry/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


Use `AGENTS.md` in the repository root as the canonical project instruction file.

When a task needs project-specific context:

1. Start from `skills/SKILL.md`
2. Read only the relevant domain `SKILL.md`
3. Load specific reference files only when needed

Use `docs/` for human-facing background and longer explanations, not as the default full-context source.

Keep Cursor-specific instructions thin here. Project knowledge should stay centralized in `AGENTS.md` and `skills/`.

---
> Source: [Pandaala/Edgion](https://github.com/Pandaala/Edgion) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-05 -->
