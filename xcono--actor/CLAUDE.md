# actor

> - @.cursor/rules/go/go_base.mdc

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/actor/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Concurrency patterns (context, cancellation, workers)

References
- @.cursor/rules/go/go_base.mdc

Guidelines
- Use context for cancellation; select on ctx.Done().
- Keep goroutines short-lived; avoid leaks.
- Use buffered channels deliberately; document buffer rationale.

Acceptance checklist
- Examples compile; vet is clean.

---
> Converted and distributed by [TomeVault](https://tomevault.io/claim/xcono) — claim your Tome and manage your conversions.
<!-- tomevault:4.0:claude_md:2026-04-09 -->
