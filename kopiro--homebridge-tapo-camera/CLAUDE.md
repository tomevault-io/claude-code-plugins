# homebridge-tapo-camera

> **homebridge-tapo-camera** is a Homebridge plugin designed to integrate TP-Link TAPO security cameras into the Apple HomeKit ecosystem.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/homebridge-tapo-camera/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# AGENTS.md

## Project Info
**homebridge-tapo-camera** is a Homebridge plugin designed to integrate TP-Link TAPO security cameras into the Apple HomeKit ecosystem.

## Development & Publishing
- The project is written in TypeScript and uses `npm`.
- **Publishing to npm:** Do NOT run `npm publish` locally. The project uses a GitHub Actions workflow (`.github/workflows/publish.yml`) that automatically publishes to npm via OIDC when a new version tag (e.g., `v2.9.0`) is pushed to GitHub. 
- To release a new version, simply use `npm version <major|minor|patch>` and push the resulting commit and tag to GitHub (`git push --follow-tags`).

---
> Source: [kopiro/homebridge-tapo-camera](https://github.com/kopiro/homebridge-tapo-camera) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-29 -->
