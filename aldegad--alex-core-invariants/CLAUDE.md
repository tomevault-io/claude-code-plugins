# alex-core-invariants

> - Use [Alex Core Invariants](https://github.com/aldegad/alex-core-invariants) as the canonical policy reference.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/alex-core-invariants/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Policy Reference

- Use [Alex Core Invariants](https://github.com/aldegad/alex-core-invariants) as the canonical policy reference.
- Keep the invariant text linked instead of copied wherever possible.
- Flag silent fallback, dual-write, legacy shadow paths, shared-state races, retry damage, and broken ownership boundaries before implementation.
- Explicit failover is allowed only when it is observable and does not mutate canonical truth.

---
> Source: [aldegad/alex-core-invariants](https://github.com/aldegad/alex-core-invariants) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-22 -->
