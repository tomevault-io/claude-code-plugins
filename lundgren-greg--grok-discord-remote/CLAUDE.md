# grok-discord-remote

> Read `PROJECT.md`, `CAPABILITY-MAP.md`, `docs/SPEC.md`.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/grok-discord-remote/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Agent instructions — grok-discord-remote

Read `PROJECT.md`, `CAPABILITY-MAP.md`, `docs/SPEC.md`.

This is a **Discord remote client for Grok Build**, like Copilot CLI on web/Android. One Grok session; Discord is a window.

## Product rules

- Grok Build is the brain. Not OpenClaw. Not grok.com. Not recap-bridge.
- DMs + allowlist only. Loopback ACP only.
- New Discord bot; do not use the OpenClaw bot token.
- Windows-first. TypeScript. Tests mock Discord and ACP.
- Never commit `.env` or tokens.

## Verify

```
npm test
npm run build
```

Update `PROJECT.md` when you stop. Open a PR (cloud agent) or commit on a branch. No force-push to `main`.

---
> Source: [lundgren-greg/grok-discord-remote](https://github.com/lundgren-greg/grok-discord-remote) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-03 -->
