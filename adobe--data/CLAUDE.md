# data

> - separation of concerns

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/data/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Stack

pnpm
vite
typescript

# Paradigm

- separation of concerns
- Functional programming
- Data oriented
- Prefer Immutable data, but mutation allowed for high performance
- No classes, enums or inheritance

# Linting

- Use modern Typescript.
- End statements with semicolons.
- Use `const` and `let` instead of `var`.
- Use `??` instead of `||` for nullish coalescing.

# Testing

- Use pnpm test [filename] -- --run to make tests exit automatically
- BEFORE FIXING, pause and verify test and implementation and describe which one is in error.
- Focus on concise code coverage and edge cases.
- Unit tests live adjacent to files they test as <my-file>.test.ts

---
> Source: [adobe/data](https://github.com/adobe/data) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-15 -->
