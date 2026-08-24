# pen-extension-resilience

> Extension isolation and resilience for extension package work

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/pen-extension-resilience/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Extension Resilience

- Keep extensions isolated: one failing extension must not break core editor behavior.
- Prefer diagnostics and graceful degradation over throwing from extension hooks.
- Treat `observe()` and `decorations()` as best-effort hooks; guard unsafe assumptions.
- Keep extension state explicit and namespaced; avoid hidden cross-extension coupling.
- Preserve schema validation at boundaries: reject or sanitize malformed extension/tool payloads before writes.
- For AI/collab/streaming flows, favor recoverable behavior (abort/cleanup/retry path) over hard failure.

---
> Source: [input-systems/pen](https://github.com/input-systems/pen) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-22 -->
