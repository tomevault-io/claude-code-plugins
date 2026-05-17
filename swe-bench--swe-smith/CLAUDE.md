# swe-smith

> Always prefix Python commands with `uv run`

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/swe-smith/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

Always prefix Python commands with `uv run`

Generate bugs with: `PYTHONUNBUFFERED=1 stdbuf -oL -eL uv run modal run --detach scripts/bug_gen.py --language javascript 2>&1 | tee validation.log`

---
> Source: [SWE-bench/SWE-smith](https://github.com/SWE-bench/SWE-smith) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-17 -->
