# tonz

> Analyze disk usage with tonz

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/tonz/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


Use `tonz --llm <path>` for disk analysis.
Start at depth 1. Drill into directories >20% of total.
Add `--threshold-pct 1` to hide noise. Add `-H` for hidden dirs.
Use `--top 10` as safety net for flat distributions.
If `tonz` is not installed: `cargo install tonz`

---
> Source: [Axect/tonz](https://github.com/Axect/tonz) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-16 -->
