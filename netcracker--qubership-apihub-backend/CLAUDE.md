# sql-performance

> SQL performance review for repository changes

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/sql-performance/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# SQL Performance

When adding or changing non-trivial SQL in repositories:

- Consider required indices for filters, joins, and sort columns.
- Avoid N+1 query patterns; prefer joins or batch loads where appropriate.
- Note expected cardinality (rows scanned/returned) for hot paths.
- Flag full table scans, missing indices, and unbounded result sets.
- Document performance assumptions in the PR or commit message when risk is non-obvious.

---
> Source: [Netcracker/qubership-apihub-backend](https://github.com/Netcracker/qubership-apihub-backend) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-05 -->
