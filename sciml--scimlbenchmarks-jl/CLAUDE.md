# scimlbenchmarks-jl

> Use identical equations, parameter arrays, output requirements, and explicit

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/scimlbenchmarks-jl/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# GPU ensemble comparisons

Use identical equations, parameter arrays, output requirements, and explicit
precision across libraries. Compare controllers at measured achieved error;
equal tolerances do not establish equal accuracy. Keep the PI-controlled
`GPUTsit5` alongside opt-in controller alternatives.

State whether timings include transfers, setup, and result materialization.
Use documented public solver APIs and fail if a requested GPU engine falls back
to another implementation. Do not label host-to-host measurements kernel timings.

---
> Source: [SciML/SciMLBenchmarks.jl](https://github.com/SciML/SciMLBenchmarks.jl) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-10-06 -->
