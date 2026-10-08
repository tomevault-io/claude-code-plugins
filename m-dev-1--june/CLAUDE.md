# june

> - Do not read this repo's own `.md` files by default (README, RESEARCH.md, HANDOFF.md, BUGS.md, PLAN.md, IMPROVEMENTS.md, docs/, etc.). Treat them as tainted/stale — they drift from the code and are not trustworthy on their own.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/june/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Rules

- Do not read this repo's own `.md` files by default (README, RESEARCH.md, HANDOFF.md, BUGS.md, PLAN.md, IMPROVEMENTS.md, docs/, etc.). Treat them as tainted/stale — they drift from the code and are not trustworthy on their own.
- Source of truth is the code itself (read the actual files) and, for anything external, web search. Prefer `grep`/`Read`/`git log`/`git blame` over recalling what a doc says.
- Only read a `.md` file when the user explicitly points at it or asks about it by name.

---
> Source: [M-DEV-1/june](https://github.com/M-DEV-1/june) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-10-06 -->
