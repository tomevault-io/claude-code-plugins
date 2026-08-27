# connector-duplicates

> Collapse synonym connectors like Gmail and email into one brand name

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/connector-duplicates/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# One connector per service

Connectors render as chips with a brand mark. Different labels that map to the same mark are duplicates.

- Keep **one name per service**. Prefer the brand: `Gmail` not `email`, `Chrome` not `browser`, `X` not `Twitter`, `Calendar` not `gcal`.
- Do not list both `Gmail` and `email`, `Chrome` and `browser`, `Calendar` and `gcal`, `GitHub` and `gh`.
- Case-only repeats (`Slack` / `slack`) are the same connector.
- Distinct services stay distinct (`Gmail` and `Calendar` are fine).

When extracting, patching, or QA-ing a filing, collapse synonyms in `connectors` before writing.

---
> Source: [travisrr/really.bot](https://github.com/travisrr/really.bot) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-27 -->
