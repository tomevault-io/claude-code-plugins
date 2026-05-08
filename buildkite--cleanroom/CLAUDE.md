# cleanroom

> - Keep implementation backend-agnostic by default.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/cleanroom/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Agent Notes

- Keep implementation backend-agnostic by default.
- Prefer backend-neutral CLI/API surfaces; place backend-specific runtime details in runtime config (XDG config) and adapter internals.
- This project is in early development: breaking changes are acceptable, and legacy/backwards-compat paths are not required unless explicitly requested.

---
> Source: [buildkite/cleanroom](https://github.com/buildkite/cleanroom) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-03 -->
