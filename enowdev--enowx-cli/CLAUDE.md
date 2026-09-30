# enowx-cli

> Delegation is allowed. When work splits into genuinely independent parts —

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/enowx-cli/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Agent Execution Policy

Delegation is allowed. When work splits into genuinely independent parts —
different files, no shared state — running them in parallel is fine.

What still holds:

- The primary agent owns the result. A subagent's report is a claim, not a
  verification: check the tests and the code yourself before believing it.
- Parts that depend on each other are not independent. Two agents editing one
  file will clobber each other's work regardless of how the task was described.
- Every part still has to be verified the same way: tests run, lints clean, and
  a failure reported as a failure.

---
> Source: [enowdev/enowx-cli](https://github.com/enowdev/enowx-cli) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-30 -->
