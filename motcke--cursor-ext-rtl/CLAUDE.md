# build-and-package

> Build and packaging instructions for the Cursor RTL extension

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/build-and-package/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Build & Package

- Always use `npm run package` to create a VSIX. It runs build + packaging in one step.
- Never run `vsce package` directly — the `package` script ensures the dist is rebuilt first and uses `--no-dependencies` since all deps are bundled via esbuild.

---
> Source: [motcke/cursor-ext-rtl](https://github.com/motcke/cursor-ext-rtl) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-04-23 -->
