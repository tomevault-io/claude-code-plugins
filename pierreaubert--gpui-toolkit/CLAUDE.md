# gpui-toolkit

> **Vendored 3rd-party crate** -- Zed's fork of [font-kit](https://github.com/servo/font-kit).

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/gpui-toolkit/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# zed-font-kit (lib: `zed_font_kit`)

**Vendored 3rd-party crate** -- Zed's fork of [font-kit](https://github.com/servo/font-kit).

Cross-platform font loading library. Provides font discovery, loading, and rasterization using platform-native backends (CoreText on macOS/iOS, DirectWrite on Windows, FreeType on Linux).

## Important Notes

- This is a vendored upstream crate -- minimize modifications
- Platform backends: CoreText (macOS/iOS/tvOS), DirectWrite (Windows), FreeType (Linux)
- Used by GPUI for font rendering

---
> Source: [pierreaubert/gpui-toolkit](https://github.com/pierreaubert/gpui-toolkit) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-24 -->
