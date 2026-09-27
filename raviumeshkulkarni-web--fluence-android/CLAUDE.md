# fluence-android

> This repository contains canonical documentation under `/docs`.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/fluence-android/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Fluence Android — Engineering Guidance

## Repository Documentation

This repository contains canonical documentation under `/docs`.

Agents must consult the relevant document before modifying a subsystem.

Examples:
- "E:\App dev" Gradle is installed here, you will never clutter system directory
- docs/RELEASE_PIPELINE.md
- docs/ARCHITECTURE.md
- docs/SYNC.md
- docs/DESIGN_SYSTEM.md

Do not duplicate documentation inside AGENTS.md.

## Release Pipeline

The Android release pipeline is considered **frozen**.

Do not modify signing, GitHub Actions release logic, or release infrastructure unless fixing a verified production issue.

See: [docs/RELEASE_PIPELINE.md](docs/RELEASE_PIPELINE.md)

---
> Source: [raviumeshkulkarni-web/Fluence-Android](https://github.com/raviumeshkulkarni-web/Fluence-Android) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-23 -->
