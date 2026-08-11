# vecs

> `vecs` is an ECS core for game engines.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/vecs/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Vecs
## Project
`vecs` is an ECS core for game engines.

- Author: Row/RowDaBoat (Me)
- Issues are tracked as VEPs (Vecs Enhancement Prompts) in the `issues.local/` directory.
- `VEP 0` outlines how to write VEPs.

Changes must be localized to the task we're focusing on, any extra change outside of our current focus will only generate friction.
Answers must be technical and honest.

## Tech stack
nim, ECS architecture, arrays of structures.

## Code style
- Semantic naming over comments.
- Never-nester principle: max 1-2 nesting levels; extract methods instead.
- No `continue` in loops; extract the loop's body to it's own `proc` and use early returns.
- `camelCase` for procs/variables, `PascalCase` for types.
- Two blank lines between proc/type declarations.
- Use named variables to avoid too much inlining.
- Full words for variable names (no abbreviations).
- Functions should do one thing.
- Commit messages: brief, intention-focused.

## Markdown style
- Two blank lines before titles.
- Text on immediate next line after a title.

---
> Source: [RowDaBoat/vecs](https://github.com/RowDaBoat/vecs) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-11 -->
