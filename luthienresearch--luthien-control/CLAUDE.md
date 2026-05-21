# code-modification-principles

> Guiding principles for modifying code (refactoring, cleanup, imports, comments).

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/code-modification-principles/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Code Modification Principles


**MANDATORY. FOLLOW THESE RULES.**

1. **Use standard solutions** before custom code.
2. **Create abstractions only when:** code repeats 2+ times, complex logic requires it, or user requests it.
3. **Solve the current problem only.** NO future features.
4. **FIX BUGS DIRECTLY. DO NOT REDESIGN. STAY WITHIN SCOPE. DO NOT OVERENGINEER**

---
> Source: [LuthienResearch/luthien_control](https://github.com/LuthienResearch/luthien_control) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-20 -->
