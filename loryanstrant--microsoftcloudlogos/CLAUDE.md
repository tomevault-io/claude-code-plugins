# microsoftcloudlogos

> generates logo-data from them. Not a Home Assistant component, not an app.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/microsoftcloudlogos/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Copilot instructions — MicrosoftCloudLogos

> Canonical standards live in the `dev-standards` repo on SOUNDWAVE/Gitea.

## What this repo is

An **asset collection** of Microsoft Cloud logos/icons, plus a Python script that
generates logo-data from them. Not a Home Assistant component, not an app.

## Repo shape

- `logos/` + `icons/` — the image assets (the actual deliverable).
- `generate-logo-data.py` — a generator script (produces logo-data, e.g. an
  index/manifest from the assets).
- `docs/`, `README.md`, `reorganisation_guidance.md`, `.devcontainer/`,
  `.github/`.

## Conventions

- Primarily an asset repo: the images are the content; `generate-logo-data.py` is
  the one piece of editable code.
- Re-run the generator after adding/reorganising assets rather than hand-editing
  any generated data files.
- Microsoft logos are **trademarked** — usage is governed by Microsoft's brand
  guidelines; this repo just collects them. Don't alter the marks themselves.

## Never

- Don't commit secrets. Don't modify the trademarked logos.

---
> Source: [loryanstrant/MicrosoftCloudLogos](https://github.com/loryanstrant/MicrosoftCloudLogos) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-01 -->
