# omakaseagent

> This project follows the [Omakase](https://github.com/rblalock/omakaseagent) standard — senior craftsmanship, zero AI slop, mandatory critique.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/omakaseagent/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# AGENTS

## Omakase Standards

This project follows the [Omakase](https://github.com/rblalock/omakaseagent) standard — senior craftsmanship, zero AI slop, mandatory critique.

**Native agents (primary entry points):**
- `@omakase-engineer` — implementation, architecture, refactoring
- `@omakase-critic` — quality enforcement and review
- `@omakase-archivist` — memory and decisions

Specialists (`omakase-senior-reviewer`, `omakase-skill-judge`, etc.) are internal — invoked by leads via Task, not directly.

**Memory:** `.omakaseagent/taste.md` and `.omakaseagent/decisions.md`

**Fallback router:** `/omakase-router plan` / `/omakase-router taste` (skill `omakase-router` in `.agents/skills/omakase/`) — not for lead work.

---
> Source: [rblalock/omakaseagent](https://github.com/rblalock/omakaseagent) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-30 -->
