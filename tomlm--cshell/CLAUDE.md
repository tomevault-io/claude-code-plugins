# cshell

> - Global helper methods should always delegate to `_shell` methods rather than calling framework APIs directly.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/cshell/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Copilot Instructions

## General Guidelines
- Global helper methods should always delegate to `_shell` methods rather than calling framework APIs directly.
- Use `print()` as an alias for `Console.Out.WriteLine()` and `error()` as an alias for `Console.Error.WriteLine()` on `CShell`.

## Code Style
- Follow specific formatting rules.
- Adhere to naming conventions.

---
> Source: [tomlm/CShell](https://github.com/tomlm/CShell) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-24 -->
