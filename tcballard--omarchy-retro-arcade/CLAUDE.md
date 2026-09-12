# omarchy-retro-arcade

> - One repository, one native app window, one desktop entry and one package/release. Keep games as ordinary subdirectories.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/omarchy-retro-arcade/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Omarchy Arcade

- One repository, one native app window, one desktop entry and one package/release. Keep games as ordinary subdirectories.
- Use Rust for new application code. Preserve the upstream C++ Pinball engine and approved artwork. Do not replace existing games with simplified rewrites.
- Existing save locations and character/deck choices must survive upgrades. Never delete user data during installation.
- Preserve imported history and per-game licences. Record material integration choices in DECISIONS.md.
- Use a feature branch and reviewable commits. Check workspace fmt, Clippy, game tests, native switching and packaging; report headless evidence separately from Omarchy desktop acceptance.

---
> Source: [tcballard/omarchy-retro-arcade](https://github.com/tcballard/omarchy-retro-arcade) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-12 -->
