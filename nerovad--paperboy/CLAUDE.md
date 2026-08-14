# paperboy

> - Generated Ruby conforms to `.rubocop.yml`.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/paperboy/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# AI Instructions

- Generated Ruby conforms to `.rubocop.yml`.
- CI Pipeline requirements:
  * bundle exec rubocop
  * bundle exec brakeman
  * bundle exec bundle-audit check
  * bundle exec rake test
- Propose git commit message.
  * Prose limited to 72 characters
  * Blank Line
  * Description lines limited to 80 characters
- Git
  * use git mv when moving files

---
> Source: [nerovad/Paperboy](https://github.com/nerovad/Paperboy) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-13 -->
