# apas-verus

> Do not add sequential/parallel threshold checks; this is a textbook

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/apas-verus/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# No Thread Threshold Optimization

APAS-VERUS is a textbook implementation. Do not add threshold checks to switch between parallel and sequential execution for small inputs.

In production code you would add:
```rust
if n < THRESHOLD { sequential() } else { parallel() }
```

We don't do this here. The code demonstrates the parallel algorithm structure, not production-optimized performance.

---
> Converted and distributed by [TomeVault](https://tomevault.io/claim/briangmilnes) — claim your Tome and manage your conversions.
<!-- tomevault:4.0:claude_md:2026-04-09 -->
