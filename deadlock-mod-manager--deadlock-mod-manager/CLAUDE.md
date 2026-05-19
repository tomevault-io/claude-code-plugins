# 031-never-use-any

> Never use `any`, `unknown`, or TypeScript type casting.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/031-never-use-any/SKILL.md
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
> Source: [deadlock-mod-manager/deadlock-mod-manager](https://github.com/deadlock-mod-manager/deadlock-mod-manager) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-18 -->
