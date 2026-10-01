# specjudge

> The append-only record of every observation recorded at a trial site. It is the

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/specjudge/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# AGENTS.md — ledger

The append-only record of every observation recorded at a trial site. It is the
regulatory artifact: what this package writes is what an auditor reads years later.

- Nothing here is ever updated or deleted. A correction is a new entry that
  references the one it corrects, and both stay visible forever.
- Ordering is per site and per subject, not global. Two sites recording at the
  same instant is normal and must not be resolved by inventing a total order.
- Every write is signed with the site key. An entry that cannot be attributed to
  a site is a data integrity incident, not a bug to patch quietly.

---
> Source: [JoaquinRuiz/SpecJudge](https://github.com/JoaquinRuiz/SpecJudge) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-30 -->
