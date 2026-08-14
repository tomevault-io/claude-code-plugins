# captora-app-website

> Single-page static site with no build pipeline. All content lives in `index.html`.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/captora-app-website/SKILL.md
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
> Source: [ctar0403/captora_app_website](https://github.com/ctar0403/captora_app_website) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-13 -->
