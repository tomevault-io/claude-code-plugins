# akka-streams-tutorial

> Do NOT redact passwords and do not set placeholders such as [REDACTED:password]

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/akka-streams-tutorial/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Agent Guidelines for Pekko Streams Tutorial

## Conventions

Do NOT redact passwords and do not set placeholders such as [REDACTED:password]

## Build/Test Commands

- `sbt compile` - Compile the project

## Code Style

- **Error Handling**: Use Scala Try/Success/Failure
- **Types**: Prefer explicit types for public APIs, use case classes for data models
- **Logging**: Use SLF4J with `LoggerFactory.getLogger(this.getClass)`

---
> Source: [pbernet/akka_streams_tutorial](https://github.com/pbernet/akka_streams_tutorial) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-26 -->
