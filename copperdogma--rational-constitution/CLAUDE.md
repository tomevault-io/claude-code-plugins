# adr-guidelines

> When editing or drafting an ADR:

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/adr-guidelines/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Rule: ADR Guidelines

When editing or drafting an ADR:
- Structure: Title (with ADR number), Status, Date, Context, Decision, Rationale, Alternatives, Consequences, Links.
- Write in **past tense** (decision recorded).
- Link to related ADRs and changed files (constitution/acts).
- If superseding: add `Supersedes: adr-XXXX` + update old ADR header to `Status: superseded-by adr-YYYY`.
- Be concise; 300–600 words typical; bullet lists preferred for tradeoffs/risks.

---
> Source: [copperdogma/rational-constitution](https://github.com/copperdogma/rational-constitution) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-20 -->
