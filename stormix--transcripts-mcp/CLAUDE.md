# 050-testing

> Testing conventions for Vitest specs

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/050-testing/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Testing Guidelines

Use Vitest. Specs live under each package's `src/tests/` tree.

## Running tests

```bash
pnpm test
pnpm --filter @transcripts-mcp/core test
pnpm --filter @transcripts-mcp/adapters test
```

## File placement

- Suffix is `.spec.ts`. Never `.test.ts`. Never `__tests__` folders.
- Put specs in a `src/tests/` tree that mirrors source.

```
src/cursor.ts
src/tests/cursor.spec.ts
```

## Naming

Pattern: "should [specific outcome] when [condition]".

---
> Source: [Stormix/transcripts-mcp](https://github.com/Stormix/transcripts-mcp) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-07 -->
