# openeval

> - Keep SDK use cases in `packages/openeval/src/app` and mechanics in `src/infra`.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/openeval/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# OpenEval

- Keep SDK use cases in `packages/openeval/src/app` and mechanics in `src/infra`.
- Keep the reusable CLI in `packages/openeval/src/cli.ts` and viewer source in `packages/viewer`.
- Benchmark clients supply their own declarations, prompts, rubrics, and fixtures.
- Never import private benchmark content or maintenance code into this repository.
- Preserve finalized EvalRun and JudgeRun evidence; update active scores through selections.
- Use Benchmark, BenchmarkRun, Eval, EvalRun, and JudgeRun terminology.
- Candidate containers contain no evaluator code, judge inputs, or evidence storage.
- Verify changes with `bun run typecheck` and `bun test`; unit tests must not call live models.
- Verify release archives with `bun run release:pack` and `bun run release:verify`.

---
> Source: [Hona/openeval](https://github.com/Hona/openeval) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-11 -->
