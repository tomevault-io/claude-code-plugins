# playwright-smoke

> Guidelines for Playwright smoke tests and config in this project.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/playwright-smoke/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Playwright Smoke Guidelines

## When Editing Smoke Tests (`tests/smoke/**/*.ts`)
- Use `@smoke` grep tag for fast workflow validation
- Prefer functional assertions over screenshot/snapshot diff
- Keep deterministic: single worker, avoid timing-dependent checks

## When Editing Config (`playwright.config.ts`)
- Keep optimized for fast feedback:
  - Chromium-only by default
  - `trace: 'retain-on-failure'`, `screenshot: 'only-on-failure'`
  - `workers: 1` for deterministic workflow checks
- Avoid heavyweight defaults unless explicitly requested
- Use `PLAYWRIGHT_BASE_URL` env var for flexibility

---
> Source: [alvin19921008-arch/RBIP-web-app](https://github.com/alvin19921008-arch/RBIP-web-app) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-04-29 -->
