# functional

> Use pure functions wherever possible. Functions should return new values without side effects. Avoid mutation of shared state; use immutability and persistent data structures.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/functional/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

Use pure functions wherever possible. Functions should return new values without side effects. Avoid mutation of shared state; use immutability and persistent data structures.
Represent operations as small composable functions. Use higher‑order functions and avoid nested callbacks. In React, use async/await rather than callbacks to avoid callback hell.
Follow the RO‑RO (Receive Object, Return Object) pattern: functions accept an object argument and return an object. This makes parameters and return values explicit and easy to extend.
Use default parameter values and destructuring for readability.
Prefer composition over inheritance; avoid using classes in GraphQL resolvers.

---
> Source: [ClaudiuBogdan/hack-for-facts-eb-client](https://github.com/ClaudiuBogdan/hack-for-facts-eb-client) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-18 -->
