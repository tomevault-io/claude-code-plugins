# playwright-opentelemetry

> Always run unit tests from workspace root: `pnpm tsc`

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/playwright-opentelemetry/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Agent Guidelines for playwright-opentelemetry

Always run unit tests from workspace root: `pnpm tsc`
Always typecheck from workspace root: `pnpm test`
Never make types.ts files.

## For trace-reporter

### Build & Test Commands
- `pnpm test:e2e` - Run e2e tests (playwright)
- `pnpm typecheck` - Type checking with tsc
- `pnpm format` - Format code with Biome

### Running Single Tests
- E2E test: `pnpm test:e2e example.spec.ts` or `pnpm test:e2e --grep "test name"`

---
> Source: [endformdev/playwright-opentelemetry](https://github.com/endformdev/playwright-opentelemetry) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-24 -->
