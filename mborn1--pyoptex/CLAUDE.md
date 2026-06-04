# environment

> Known environment and dependency caveats

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/environment/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Environment caveats

- **kaleido** (plotly static export): can emit harmless dbus errors in headless/Cloud VM; safe to ignore.
- **numba** (~0.61): pulls in llvmlite; first import may have a short JIT compilation delay.

---
> Source: [mborn1/pyoptex](https://github.com/mborn1/pyoptex) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-04 -->
