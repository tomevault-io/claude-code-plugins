# postmortem

> Lessons learned from debugging test failures to avoid future mistakes.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/postmortem/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Test Failure Debugging
Check test fixtures for missing files if tests fail locally but pass in CI.
Verify assumptions made by tests about fixture contents (e.g., expected files).

# Specific Test Execution
Add specific pnpm scripts to run individual test files/suites for easier debugging.
Example: `test:ignore-flag`: `pnpm build && vitest run test/ignore-flag.test.ts`

# `ignore-test` Fixture Issue
`test/cli.test.ts` and `test/ignore-flag.test.ts` failed because `test/fixtures/ignore-test/ignored.js` was missing.
Creating the empty `ignored.js` file fixed the tests.

---
> Source: [johnlindquist/file-forge](https://github.com/johnlindquist/file-forge) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-21 -->
