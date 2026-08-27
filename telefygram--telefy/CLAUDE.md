# telefy

> - Treat `tdlib/` as immutable and read-only.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/telefy/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Project Agent Instructions

## Immutable TDLib

- Treat `tdlib/` as immutable and read-only.
- Never create, edit, delete, format, regenerate, or revert any file inside `tdlib/`, including shell scripts, JavaScript, WebAssembly sources, configuration, generated files, and submodule metadata.
- Do not run commands that write into `tdlib/` or change its Git state.
- Preserve any existing user changes inside `tdlib/`.
- If a task appears to require changing `tdlib/`, stop that part of the work and explain that the change must be made outside `tdlib/` or explicitly approved by the user.
- Project integration files outside `tdlib/`, such as `scripts/`, `lib/`, `web/`, and `build/`, may be changed when required, but do not modify TDLib to make them work.

---
> Source: [TelefyGram/telefy](https://github.com/TelefyGram/telefy) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-27 -->
