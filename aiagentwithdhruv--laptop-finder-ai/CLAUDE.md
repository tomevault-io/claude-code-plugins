# 99-response-style

> How to respond when generating code and implementation plans

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/99-response-style/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


When implementing:
- Prefer precise, minimal, production-ready changes.
- Explain architecture briefly when it matters.
- Generate only the necessary files and edits.
- Respect existing repository conventions.
- If a task is large, break it into clean phases but still produce usable code.
- When adding a new module, place it in the correct layer and name it clearly.
- When relevant, mention follow-up files the team should also update, such as env examples, migrations, tests, or docs.

Do not:
- Produce toy code when production code is requested.
- Invent random abstractions without need.
- Change unrelated code paths.

---
> Source: [aiagentwithdhruv/laptop-finder-ai](https://github.com/aiagentwithdhruv/laptop-finder-ai) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-17 -->
