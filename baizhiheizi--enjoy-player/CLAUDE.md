# architecture

> Feature-first architecture boundaries for enjoy_player

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/architecture/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Architecture rules

- Organize code under `lib/features/<feature>/{application,data,domain,presentation}`.
- **Domain** models must stay UI-free (no `BuildContext`, no Flutter imports unless unavoidable).
- **Data** layer (`lib/data`) hosts Drift DB, subtitle parsers, file storage — no widget code.
- **Application** layer hosts Riverpod notifiers / repositories orchestration.
- Avoid **feature ↔ feature** imports when possible; lift shared code into `lib/core` or `lib/data`.
- Persist playback state through **`SessionDao`** — do not duplicate echo/progress logic in widgets.

---
> Source: [baizhiheizi/enjoy_player](https://github.com/baizhiheizi/enjoy_player) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-10 -->
