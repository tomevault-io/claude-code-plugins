# kart

> Best practices for using Redis in applications

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/kart/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

---
name: redis-best-practices.mdc
description: Best practices for using Redis in applications
globs: **/*.{ts,js}
---

- Use Redis hashes to store driver scores and details efficiently.
- Implement expiration for temporary data to manage memory usage.
- Use transactions (MULTI/EXEC) for atomic updates when adding points.
- Leverage Redis Pub/Sub for real-time leaderboard updates.

---
> Converted and distributed by [TomeVault](https://tomevault.io/claim/federicofanini)
> This is a context snippet only. You'll also want the standalone SKILL.md file — [download at TomeVault](https://tomevault.io/claim/federicofanini)
<!-- tomevault:4.0:claude_md:2026-04-08 -->
