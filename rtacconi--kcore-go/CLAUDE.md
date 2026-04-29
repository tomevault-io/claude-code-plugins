# kcore-go

> Shell script standards — avoid AI-generated patterns

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/kcore-go/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Shell Script Standards

## No emoji in echo/printf output

```bash
# BAD
echo "🚀 Starting build..."
echo "✅ Build complete"
echo "❌ Build failed"

# GOOD
echo "Starting build..."
echo "Build complete"
echo "Build failed"
```

## No over-decorated output

Keep script output informative and scannable. Avoid ASCII art banners, box-drawing characters around status messages, or multi-line success celebrations.

## Error handling over decoration

Spend effort on `set -euo pipefail`, proper error messages with context, and cleanup traps — not on making echo output colorful.

---
> Converted and distributed by [TomeVault](https://tomevault.io/claim/rtacconi) — claim your Tome and manage your conversions.
<!-- tomevault:4.0:claude_md:2026-04-10 -->
