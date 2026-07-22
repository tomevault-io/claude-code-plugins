# colyseus

> - Run `npm test -- --grep 'NAME OF TEST CASE'` from `bundles/colyseus` directory.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/colyseus/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Project Instructions

## Testing

- Run `npm test -- --grep 'NAME OF TEST CASE'` from `bundles/colyseus` directory.
  - Before running tests, must use `pnpm build` at root of monorepo if any of the child packages have changes.
- When making changes to `@colyseus/sdk`, make sure to run `npx tsc` from `./packages/sdk` to update TypeScript definitions.

---
> Source: [colyseus/colyseus](https://github.com/colyseus/colyseus) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-20 -->
