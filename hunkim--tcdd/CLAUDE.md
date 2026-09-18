# tcdd

> This repository is a **drop-in TCDD skill pack**.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/tcdd/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Agent instructions

This repository is a **drop-in TCDD skill pack**.

1. Install skills: `bash scripts/install_skill.sh`
2. Before every Freebuff review: `python3 scripts/set_freebuff_solar_pro4.py && python3 scripts/verify_freebuff_solar_pro4.py`
3. Follow [`SKILL.md`](./SKILL.md) end-to-end. Never declare DONE without Solar Pro 4 Freebuff for the current batch.

Primary skill: `SKILL.md`  
Companion: `skills/freebuff-post-change-review/SKILL.md`

---
> Source: [hunkim/TCDD](https://github.com/hunkim/TCDD) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-18 -->
