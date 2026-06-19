# skill-deck

> This is a Tauri v2 + Svelte 5 + Tailwind CSS v4 desktop app.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/skill-deck/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

This is a Tauri v2 + Svelte 5 + Tailwind CSS v4 desktop app.

Backend (Rust): src-tauri/src/ — models, parsers, agents, commands, detection
Frontend (Svelte 5): src/ — uses runes ($state, $derived, $effect), NOT legacy Svelte 4 syntax

Key architecture: Adapter pattern. agents/registry.rs defines all 15+ supported coding agents with their file paths and formats. parsers/frontmatter.rs is the universal Markdown+YAML parser. Everything normalizes to models/skill.rs.

Build: pnpm install && pnpm tauri dev
Test: cd src-tauri && cargo test

See AGENTS.md for complete architecture docs.

---
> Source: [OthmanAdi/skill-deck](https://github.com/OthmanAdi/skill-deck) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-19 -->
