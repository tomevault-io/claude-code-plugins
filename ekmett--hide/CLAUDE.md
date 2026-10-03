# hide

> Never compare whole desktops, buffer contents, or undo histories to decide whether

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/hide/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Working on hide

## Interaction performance

Never compare whole desktops, buffer contents, or undo histories to decide whether
an interaction or redraw needs work. Use explicit small UI-state keys and stable
identities or revisions for immutable payloads. Keep full-text processing on its
owning background worker. A new Desktop field must not silently add deep work to
the render loop; retain regression tests that reject forcing large payloads.

---
> Source: [ekmett/hide](https://github.com/ekmett/hide) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-10-03 -->
