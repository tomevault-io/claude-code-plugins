# slop-grader

> - Prefer snapshot testing instead of a list of assertions, use inline snapshots preferably

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/slop-grader/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

- Prefer snapshot testing instead of a list of assertions, use inline snapshots preferably
- Run `npm run verify` when completing a task (not after every intermediate edit)
- Never add any backwards compatibility regarding the code, there is no external consumer of the code
- Never use any or unkown in normal circumstances
- Never use duck typing when proper types are possible (discriminated union missing?)
- Update the README.md and SKILL.md when changing functionality

---
> Source: [lukstei/slop-grader](https://github.com/lukstei/slop-grader) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-21 -->
