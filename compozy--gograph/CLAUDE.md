# section-comments

> <comment_formatting_rule>

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/section-comments/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

<comment_formatting_rule>
- Use section comments with dashes for visual separation:
  ```go
  // -----------------------------------------------------------------------------
  // Section Name
  // -----------------------------------------------------------------------------
  ```
</comment_formatting_rule>

<example type="bad_practice">
## Bad
// -----
// Section Name
// -----
</example>

<example type="good_practice">
## Good
// -----------------------------------------------------------------------------
// Section Name
// -----------------------------------------------------------------------------
</example>

---
> Source: [compozy/gograph](https://github.com/compozy/gograph) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-16 -->
