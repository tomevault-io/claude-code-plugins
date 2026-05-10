# project-role-architecture

> Project role, Flutter+Rust architecture, and Nostr conventions

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/project-role-architecture/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Role & Project Conventions

## Role

Act as a **senior Flutter engineer**. All descriptions and documentation must be in **English**.

## Architecture

- **Stack**: Flutter + Rust. Call Rust bridge code via **async** APIs where possible.
- **Structure**: Modular design; place modules under the **packages** directory.

## Project (Nostr)

This is a **Nostr-based** project. When you need **NIP (Nostr Improvement Proposal) definitions**:

- Prefer the Nostr MCP server **user-flutter-nostr-dev** (tools/resources) when available.
- Otherwise refer to official NIP specs (e.g. github.com/nostr-protocol/nips) or project docs.

---
> Source: [sanah9/noscall](https://github.com/sanah9/noscall) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-05 -->
