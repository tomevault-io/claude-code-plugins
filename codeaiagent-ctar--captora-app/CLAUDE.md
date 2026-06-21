# captora-app

> Single-page static site with no build pipeline. All content lives in `index.html`.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/captora-app/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Captora Website — Agent Guide

## Architecture

Single-page static site with no build pipeline. All content lives in `index.html`.

## Key files

| File | Purpose |
|------|---------|
| `index.html` | Full website — ~49 KB self-contained HTML |
| `logo_*.png` | Logos at 64 / 128 / 250 px sizes |
| `netlify.toml` | Security headers config |

## Conventions

- No framework, no dependencies, no node_modules needed for the site itself
- Edits go directly into `index.html`
- Images are served from the repo root alongside `index.html`

---
> Source: [CodeAIAgent-ctar/captora_app](https://github.com/CodeAIAgent-ctar/captora_app) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-21 -->
