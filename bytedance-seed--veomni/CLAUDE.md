# no-section-divider-comments

> Do not use decorative section divider comments in Python code

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/no-section-divider-comments/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# No Section Divider Comments

Do NOT add decorative section-divider comments like:

```python
# ---------------------------------------------------------------------------
# Some Section Name
# ---------------------------------------------------------------------------
```

or

```python
# ------------------------------------------------------------------
# Some Section Name
# ------------------------------------------------------------------
```

These add visual noise without value. If code needs grouping, use module-level or class-level docstrings, or simply rely on class/function structure.

---
> Source: [ByteDance-Seed/VeOmni](https://github.com/ByteDance-Seed/VeOmni) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-17 -->
