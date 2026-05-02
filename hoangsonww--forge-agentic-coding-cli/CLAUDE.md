# testing

> Testing rules for vitest suite

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/testing/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Testing rules

- Runner: **vitest**. Run one file:
  `npx vitest run test/unit/<file>.test.ts`.
- 249 tests across 43 files must remain 100% green. Never `.only`,
  skip, or comment out a test to make the suite pass.
- **Never** make real network calls in unit tests. Mock with
  `vi.mock`. See `test/unit/executor-loop.test.ts` for the
  `callModel` stub and `test/unit/adapter.test.ts` for the
  provider stub.
- Use tempdirs (`os.tmpdir()` + `fs.mkdtempSync`) for disk writes;
  clean up in `afterEach`. See `test/unit/validation-gate.test.ts`.
- Test names describe behaviour: "should reject task when provider is
  unreachable", not "calls provider.ping once".
- New logic in `src/core`, `src/agents`, or `src/tools` **requires**
  a unit test — not optional.

---
> Source: [hoangsonww/Forge-Agentic-Coding-CLI](https://github.com/hoangsonww/Forge-Agentic-Coding-CLI) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-04-23 -->
