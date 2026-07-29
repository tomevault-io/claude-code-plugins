# egolens

> When working on performance issues:

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/egolens/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Project Conventions

## Performance Optimization Process
When working on performance issues:
1. Always measure before fixing — use chrome-devtools-mcp for profiling
2. Document every optimization in docs/PERFORMANCE_OPTIMIZATION.md
3. Follow the OPT-NNN format (see that file for structure)
4. Include: problem, alternatives with tradeoffs, decision rationale, before/after measurements
5. If profiling shows an issue is within frame budget (16.6ms), move it to Rejected/Deferred
6. Commit optimization code and doc update together

## Commit Conventions
- perf: prefix for performance changes
- fix: prefix for bug fixes
- Include measurable results in commit body when applicable

---
> Source: [egolens/egolens](https://github.com/egolens/egolens) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-26 -->
