# workflow-runtime-updates

> - Aggregator, Compiler, and Autonomous Research are mutually exclusive runtime modes. Only one workflow mode may be active at a time, and starting any mode while another is running must be blocked.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/workflow-runtime-updates/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


## Workflow Runtime Updates

- Aggregator, Compiler, and Autonomous Research are mutually exclusive runtime modes. Only one workflow mode may be active at a time, and starting any mode while another is running must be blocked.
- This rule explicitly supersedes any older wording in `part-1-and-part-2-cointeraction-architecture.mdc` that describes Aggregator and Compiler as concurrently runnable.

- Compiler critique skip and autonomous critique skip both support pre-emptive use during active paper-writing. If critique is already active, the skip happens immediately. If critique has not started yet, the skip is queued and auto-applies when critique is reached.
- This rule explicitly supersedes any older wording in `part-2-compiler-tool-design-specification.mdc` that describes compiler critique skip as active-critique-only.

---
> Source: [Intrafere/MOTO-Autonomous-ASI](https://github.com/Intrafere/MOTO-Autonomous-ASI) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-04-24 -->
