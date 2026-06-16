# temper-skill-context-engineering

> Hierarchical context loading for AI coding agents — load what you need, defer what you don't

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/temper-skill-context-engineering/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Context Engineering

Load the right information, in the right order, at the right time. Maximize signal per token.

For the full context loading strategy, apply the `.claude/skills/context-engineering/SKILL.md` definitions:
- Priority: rules -> arch -> source -> errors -> conversation
- Budget: under 2K lines per task
- 6-step process: determine scope -> load rules -> load architecture -> load source -> load errors -> defer everything else

Apply these rules at the start of every Temper stage.

---
> Source: [galando/temper](https://github.com/galando/temper) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-16 -->
