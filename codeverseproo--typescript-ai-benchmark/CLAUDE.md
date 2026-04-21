# typescript-ai-benchmark

> description: TypeScript strict mode enforcement

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/typescript-ai-benchmark/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Full config: https://github.com/beyondit/typescript-ai-benchmark

---
description: TypeScript strict mode enforcement
globs: ["**/*.ts", "**/*.tsx"]
alwaysApply: true
---

- NEVER use `any`. Use `unknown`.
- NEVER use `as unknown as X`. Implement a type guard.
- NEVER suppress errors with `@ts-ignore`.
- ALWAYS run `tsc --noEmit` before marking a task done.
- When a type can't be threaded — stop and ask. Don't assert.

---
> Converted and distributed by [TomeVault](https://tomevault.io/claim/codeverseproo) — claim your Tome and manage your conversions.
<!-- tomevault:4.0:claude_md:2026-04-09 -->
