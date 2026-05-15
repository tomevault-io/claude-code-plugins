# agentnoise

> This is a Rust CLI/daemon project.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/agentnoise/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# agentnoise

This is a Rust CLI/daemon project.

- Keep the trusted bridge path native: Rust plus the local launcher policy.
- Do not add Node, npm, bun, Electron, or Tauri to the daemon path.
- Agent execution must go through `bondage` profiles.
- Chat commands must map to structured argv arrays, never shell-concatenated strings.
- Treat White Noise as the transport/control channel; do not make this look like an official White Noise client.

---
> Source: [nvk/agentnoise](https://github.com/nvk/agentnoise) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-15 -->
