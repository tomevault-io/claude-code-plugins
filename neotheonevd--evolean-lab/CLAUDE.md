# evolean-lab

> - Never report a conjecture as proved unless its exact formal statement passes Lean without `sorry` or new unsound axioms.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/evolean-lab/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# EvoLean Lab working agreement

- Never report a conjecture as proved unless its exact formal statement passes Lean without `sorry` or new unsound axioms.
- Keep the original problem statement immutable. Store special cases, weakenings, and strengthened hypotheses as separate candidates with explicit parent links.
- Preserve provenance for literature claims, generated ideas, computational evidence, counterexamples, and formal artifacts.
- Use `VERIFIED`, `REFUTED`, `PARTIAL_PROGRESS`, or `UNRESOLVED` precisely.
- Treat model scores as search heuristics, never as mathematical evidence.
- Add tests for changes to selection, mutation, persistence, or verification behavior.

---
> Source: [Neotheonevd/evolean-lab](https://github.com/Neotheonevd/evolean-lab) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-28 -->
