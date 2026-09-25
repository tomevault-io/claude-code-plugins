# pi-agenticoding

> **Never use `console.debug/warn/error/log`** — writes to stdout/stderr corrupt pi's TUI ANSI rendering. Extension host runs in the same process.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/pi-agenticoding/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# TUI Safety

**Never use `console.debug/warn/error/log`** — writes to stdout/stderr corrupt pi's TUI ANSI rendering. Extension host runs in the same process.

Use `ctx.ui.notify()` / `setStatus()` / `setWidget()` instead. For diagnostics, remove entirely.

---
> Source: [agenticoding/pi-agenticoding](https://github.com/agenticoding/pi-agenticoding) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-24 -->
