# titanclip-cursor-adapter

> Cursor local adapter — CLI integration and skills sync

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/titanclip-cursor-adapter/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Cursor local adapter (`@titanclip/adapter-cursor-local`)

- Integrates with **Cursor CLI / home layout** (e.g. skills under `~/.cursor/skills`). Preserve **backward compatibility** for paths and config expectations used by Paperclip/TitanClip.
- Prefer extending existing tests under this package; add Vitest coverage when behavior or filesystem contracts change.
- Do not assume a single OS: keep path handling via `node:path` / `os.homedir()` patterns consistent with the rest of the adapter.

---
> Source: [CES-Ltd/TitanClip](https://github.com/CES-Ltd/TitanClip) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-14 -->
