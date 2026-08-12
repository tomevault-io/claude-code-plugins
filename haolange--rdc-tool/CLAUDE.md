# rdc-tool

> Scope: this file governs the `rdx-tools` CLI project (`rdx/`, `cli/`, `docs/`, `scripts/`, `tests/`, `spec/`).

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/rdc-tool/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

﻿# AGENTS.md

Scope: this file governs the `rdx-tools` CLI project (`rdx/`, `cli/`, `docs/`, `scripts/`, `tests/`, `spec/`).

`rdx-tools` is CLI-only. Use `rdx` as the public user command; keep `rdx.bat`, `bin/rdx`, and `python cli/run_cli.py` as package launcher files.

## Conflict policy:

If CLI docs, catalog, or tests disagree, fix the implementation and the docs together. Check these files when session, remote, preview, or smoke behavior changes:

- docs/session-model.md
- docs/agent-model.md
- docs/troubleshooting.md
- docs/doc-governance.md
- docs/android-remote-cli-smoke-prompt.md

Remote self-tests should cover `rd.remote.connect`, `rd.remote.ping`, and `rd.capture.open_replay`.

## preview / 几何观察面改动

涉及 preview / 几何观察面改动时，必须同步检查 `rd.session.open_preview`、`preview.display`、`preview_geometry_smoke.py` 与 CLI 文档。

---
> Source: [haolange/RDC-Tool](https://github.com/haolange/RDC-Tool) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-11 -->
