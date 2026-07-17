# keep-ui-tests

> description: Rules and guidelines for writing and running React tests

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/keep-ui-tests/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

---
description: Rules and guidelines for writing and running React tests
globs: *.spec.tsx, *.test.tsx, *.test.ts, *.spec.ts
---

# Writing frontend tests

Place tests in __tests__ folder in the module, e.g. tests for file `/features/workflows/model/useWorkflows.tsx` should be `/features/workflows/models/__tests__/useWorkflows.test.tsx`

# Running frontend tests

Please run tests with command: npm run test in keep-ui folder
For example: cd keep-ui && npm run test

---
> Source: [whitestack/keep](https://github.com/whitestack/keep) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-17 -->
