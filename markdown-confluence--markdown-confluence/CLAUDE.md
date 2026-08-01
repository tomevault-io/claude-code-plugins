# markdown-confluence

> - Use Node.js `24.15.0` for local parity with CI.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/markdown-confluence/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Repository Guidelines

## Tooling Decisions

- Use Node.js `24.15.0` for local parity with CI.
- Use `pnpm` for package management. Do not add `package-lock.json` or Yarn lockfiles; `pnpm-lock.yaml` is the authoritative lockfile.
- Use Vite+ (`vp`) for formatting, linting, tests, checks, builds, and workspace task execution.
- GitHub Actions should use `voidzero-dev/setup-vp` with Node.js `24.15.0`.
- In CI and release scripts, invoke the same Vite+ commands that the GitHub workflows run, for example:
    - `vp install --frozen-lockfile`
    - `vp run check`
    - `vp run fmt:check`
    - `vp test run`
    - `vp run build`
    - `vp run -r build:docker`
- Avoid adding direct ESLint, Prettier, or Jest commands for repo workflows. When touching legacy tooling paths, migrate them to `vp`.
- Local `pnpm run ...` is fine for interactive work, but committed GitHub Actions should follow the checked-in Vite+ workflow pattern above.

---
> Source: [markdown-confluence/markdown-confluence](https://github.com/markdown-confluence/markdown-confluence) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-22 -->
