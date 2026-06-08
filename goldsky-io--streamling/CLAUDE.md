# tests

> Prefer unit tests for quick iteration. E2E tests (just e2e-test) may be run when needed; they require env-setup first (just env-setup) for k3s, Kafka, etc.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/tests/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


Prefer unit tests for quick iteration. E2E tests (just e2e-test) may be run when needed; they require env-setup first (just env-setup) for k3s, Kafka, etc.

After each task, check code by running just fix, followed by just lint.

When fixing an issue, try to write a unit test for the issue first, watch it fail, then fix it, making the change as easy to understand as possible.

---
> Source: [goldsky-io/streamling](https://github.com/goldsky-io/streamling) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-08 -->
