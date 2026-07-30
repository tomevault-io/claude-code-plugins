# otel-arrow

> - Target a single-threaded async runtime

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/otel-arrow/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Design Principles

- Target a single-threaded async runtime
- Declare async traits as `?Send`, providing `!Send` implementations and futures whenever practical
- Avoid synchronization primitives as much as possible
- Optimize for performance
- Avoid unbounded channels and data structures
- Minimize dependencies

---
> Source: [open-telemetry/otel-arrow](https://github.com/open-telemetry/otel-arrow) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-27 -->
