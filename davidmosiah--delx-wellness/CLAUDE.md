# delx-wellness

> This repo is the public Delx Wellness registry and documentation source of truth. It is docs/metadata only; connector code lives in separate repos.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/delx-wellness/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Agent Development Notes

## Scope

This repo is the public Delx Wellness registry and documentation source of truth. It is docs/metadata only; connector code lives in separate repos.

## Commands

- Validate registry JSON: `python3 -m json.tool registry.json >/dev/null`
- Inspect connector status: `sed -n '1,220p' docs/provider-status.md`
- Search registry/docs: `rg "<provider-or-package>"`

## Rules

- Keep `registry.json`, `docs/provider-status.md`, connector tables, and website-facing copy in sync.
- Do not commit real user health data, OAuth tokens, API secrets, private hub code, billing logic, or token-vault details.
- Keep the open-source boundary explicit: local connectors public, hosted hub/token vault private unless intentionally released.
- Maintain the disclaimer: not a medical device and not medical advice.

---
> Source: [davidmosiah/delx-wellness](https://github.com/davidmosiah/delx-wellness) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-13 -->
