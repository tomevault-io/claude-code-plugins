# 040-testing

> Jest coverage and authorizer test expectations.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/040-testing/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Testing

Read `docs/TESTING.md`.

- Keep ≥80% coverage on branches, functions, lines, statements.
- Mock `jose`; do not call live Cognito in unit tests.
- Do not delete tests to greenwash coverage.
- Cover Bearer parsing, verify failures, token_use, scope, success policy.

---
> Source: [jessemull/100-letters-project-authorizer](https://github.com/jessemull/100-letters-project-authorizer) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-27 -->
