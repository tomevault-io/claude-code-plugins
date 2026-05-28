# trustee

> - Use English for code comments.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/trustee/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Cursor Rules

- Use English for code comments.
- When wrapping errors, preserve and surface the original error details.
  Prefer patterns like `map_err(|e| anyhow!("context: {e}"))` over
  `map_err(|_| anyhow!("context"))`.

---
> Source: [openanolis/trustee](https://github.com/openanolis/trustee) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-28 -->
