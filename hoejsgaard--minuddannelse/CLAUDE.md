# minuddannelse

> description: Logging standards and best practices

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/minuddannelse/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

---
description: Logging standards and best practices
globs: "**/*.cs"
alwaysApply: false
---
# Logging Rules

- Remove LogDebug calls - use LogInformation or higher
- Remove try/catch->log patterns - let middleware handle exceptions  

- Use ILoggerFactory injection, not ILogger<T> in constructors

---
> Converted and distributed by [TomeVault](https://tomevault.io/claim/Hoejsgaard) — claim your Tome and manage your conversions.
<!-- tomevault:4.0:claude_md:2026-04-09 -->
