# donecheck

> Before claiming a coding task is done:

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/donecheck/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# DoneCheck Agent Rule

Before claiming a coding task is done:

1. Run `python donecheck.py --cmd "<project test command>"`.
2. If it fails, fix the work and rerun it.
3. Mention the `DONECHECK.md` status in the final answer.

Never use DoneCheck as a replacement for real tests or human review.

---
> Source: [AtharvaMaik/donecheck](https://github.com/AtharvaMaik/donecheck) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-22 -->
