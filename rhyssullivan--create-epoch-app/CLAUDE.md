# never-use-as-any

> Never use `any`, `unknown`, or TypeScript type casting.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/never-use-as-any/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


Never use `any`, `unknown`, or TypeScript type casting.

This includes:
- The `any` type
- The `unknown` type
- Type assertions using `as` (e.g., `value as SomeType`)
- Type assertions using angle brackets (e.g., `<SomeType>value`)

Types should be correct and properly inferred or explicitly defined. If you find yourself needing to cast types, refactor the code to use proper type definitions, type guards, or type narrowing instead.

---
> Source: [RhysSullivan/create-epoch-app](https://github.com/RhysSullivan/create-epoch-app) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-04-22 -->
