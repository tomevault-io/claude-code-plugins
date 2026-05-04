# account-sdk

> When running tests with npm, yarn, or vitest, ALWAYS include flags to prevent interactive/watch mode:

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/account-sdk/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Cursor AI Assistant Rules

## Test Execution Guidelines

### Always use non-interactive mode for tests
When running tests with npm, yarn, or vitest, ALWAYS include flags to prevent interactive/watch mode:

- For npm test: use `npm test -- --run`
- For yarn test: use `yarn test --run`
- For vitest directly: use `vitest run`
- For jest: use `jest --no-watch`

---
> Source: [base/account-sdk](https://github.com/base/account-sdk) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-04 -->
