# cyder-wine-engine

> Wine engine work lives in cyder-wine-engine — read its guides first

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/cyder-wine-engine/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Cyder Wine engine (sibling repo)

This CyderBits repo is the application layer. The Wine engine that actually
runs `.exe` files is [cyder-wine-engine](https://github.com/dspp779/cyder-wine-engine)
(`../cyder-wine-engine` or `/Users/jjc/cyder-wine-engine`).

Before engine / wineserver / ntdll / pack work:

1. Prefer operating in the `cyder-wine-engine` checkout.
2. Read `cyder-wine-engine/AGENTS.md` and
   `cyder-wine-engine/docs/incremental-build-and-patches.md`.
3. Do not ad-hoc rebuild host Mach-O without that repo’s `.env` / minOS 10.15
   rules.

---
> Source: [dspp779/CyderBits](https://github.com/dspp779/CyderBits) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-31 -->
