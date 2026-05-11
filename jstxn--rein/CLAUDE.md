# rein-retro

> Use after a miss, regression, or suspicious shortcut. Captures what failed and what rule should change.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/rein-retro/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# rein-retro

Use this after a miss, failed check, or suspicious shortcut.

## Steps

1. State what failed.
2. Identify the false assumption or missed search step.
3. Classify the miss:
   - bluffing
   - incomplete search
   - insufficient verification
   - reward hacking
   - other
4. State what evidence would have prevented the miss.
5. Propose one concrete protocol improvement.

## Output

Emit a short retro note with:

- failure
- root assumption
- miss classification
- missing evidence
- rule or prompt update to add back into the harness

---
> Source: [jstxn/rein](https://github.com/jstxn/rein) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-09 -->
