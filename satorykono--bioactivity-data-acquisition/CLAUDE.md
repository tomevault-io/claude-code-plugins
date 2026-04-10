# bioactivity-data-acquisition

> USE WHEN implementing pipelines; follow standard contract stages

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/bioactivity-data-acquisition/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


Pipelines contract stages

> Scope:
> - USE WHEN implementing pipelines; follow standard contract stages
> - Use when editing files matching: `src/bioetl/pipelines/**/*.py`, `docs/etl_contract/**/*.md`
# MANDATORY
- Implement the standard ETL sequence: `extract → transform → validate → export`.

# GOOD
Each pipeline class provides these stage methods; validation precedes export.

# REFERENCE
See ../../docs/styleguide/08-etl-architecture.md

---
> Converted and distributed by [TomeVault](https://tomevault.io/claim/SatoryKono) — claim your Tome and manage your conversions.
<!-- tomevault:4.0:claude_md:2026-04-09 -->
