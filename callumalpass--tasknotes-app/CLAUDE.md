# tasknotes-app

> Read `PRODUCT.md` and `DESIGN.md` before changing user-facing behaviour or

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/tasknotes-app/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# TaskNotes app

Read `PRODUCT.md` and `DESIGN.md` before changing user-facing behaviour or
visuals. The application is web-first and packaged for Android and iOS through
Capacitor.

All durable collection access goes through the provider-neutral mdbase
`TaskRepository`. UI and application code must not branch on hosted versus
connected-computer storage. TaskNotes does not open device folders and does not
maintain an IndexedDB task replica; IndexedDB is permitted only for bounded
application state such as a delayed deletion's undo window.

---
> Source: [callumalpass/tasknotes-app](https://github.com/callumalpass/tasknotes-app) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-16 -->
