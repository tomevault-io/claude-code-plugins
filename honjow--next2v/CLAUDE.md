# git-workflow

> Git commit and workflow conventions

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/git-workflow/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Git Workflow

## Commit Messages

- **English only** — never use Chinese in commit messages
- Format: `type: concise description`
- Types: `feat`, `fix`, `refactor`, `style`, `docs`, `chore`, `perf`
- Keep it brief; if multiple changes, use bullet list in body
- Don't turn commit messages into technical documentation

## Before Committing

- Don't commit unless explicitly asked
- Run `npx @ohos-rs/oxk format --quote-style single --semicolons as-needed` on changed `.ets` files
- Don't commit `oh-package-lock.json5` files unless dependency changes are intentional
- Don't commit `build-profile.json5` signing config changes

## Files to Ignore

- `**/oh-package-lock.json5` — lock files
- `**/build/` — build outputs
- `scripts/*.p12`, `scripts/*.cer`, `scripts/*.p7b` — signing credentials

---
> Source: [honjow/Next2V](https://github.com/honjow/Next2V) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-17 -->
