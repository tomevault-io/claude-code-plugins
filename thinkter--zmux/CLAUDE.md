# zmux

> - Keep `gpui_platform` dependencies target-specific in `Cargo.toml`.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/zmux/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Repository guidance

## Platform dependencies

- Keep `gpui_platform` dependencies target-specific in `Cargo.toml`.
- On macOS, `gpui_platform` must enable the `font-kit` feature so fonts render correctly.
- On Windows, keep `gpui_platform` enabled without `font-kit`.
- On Linux and FreeBSD, keep the existing `font-kit`, `wayland`, and `x11` features.
- Do not combine the macOS and Windows dependency sections unless their distinct feature sets are preserved.

---
> Source: [thinkter/zmux](https://github.com/thinkter/zmux) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-09 -->
