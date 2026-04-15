# useful-things

> description: Enforce java.time.Clock injection for time travel

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/useful-things/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

---
description: Enforce java.time.Clock injection for time travel
globs: *.java
---

# Clock Injection (Java)

## Description

To support deterministic backtesting ("Time Travel"), strict abstraction of the system clock is required.

## Rules

1.  **Forbidden Static Time**:

    - `System.currentTimeMillis()`, `Instant.now()`, `new Date()` are **STRICTLY FORBIDDEN**.

2.  **Injection Requirement**:

    - Time-sensitive Components must inject `private final Clock clock;`.

3.  **Usage**:

    - _Correct_: `Instant.now(clock)`.

4.  **Testing**:
    - Use `Clock.fixed()` in tests; `SimulatedClock` for backtesting.

---
> Converted and distributed by [TomeVault](https://tomevault.io/claim/rsqn)
> This is a context snippet only. You'll also want the standalone SKILL.md file — [download at TomeVault](https://tomevault.io/claim/rsqn)
<!-- tomevault:4.0:claude_md:2026-04-09 -->
