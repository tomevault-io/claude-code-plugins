# cli

> - Migration functions must print a message only if they performed changes.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/cli/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Migration Guidelines

- Migration functions must print a message only if they performed changes.
- Use `internal.ChangeFileContent`, which returns a boolean, and print the message only when it is `true`.

---
> Source: [gofiber/cli](https://github.com/gofiber/cli) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-22 -->
