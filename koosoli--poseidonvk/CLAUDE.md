# poseidonvk

> - Identify the reference implementation and the required data flow, resources, synchronization, and validation before editing.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/poseidonvk/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

- Identify the reference implementation and the required data flow, resources, synchronization, and validation before editing.
- Do not present a visual approximation as completion when it cannot satisfy the agreed behavior.
- Use temporary fallbacks only to keep the build runnable or when the user explicitly requests an experiment; label them clearly and schedule their removal.
- Batch related subsystem work into complete milestones. Do not ask for a manual smoke test after minor intermediate edits.
- Before a milestone smoke test, provide an exact launch command and a concise checklist covering the intended behavior and likely regressions.
- When a reference renderer uses a larger architecture, port the necessary architecture instead of attempting to imitate its result with isolated shader tweaks.

---
> Source: [koosoli/PoseidonVK](https://github.com/koosoli/PoseidonVK) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-07 -->
