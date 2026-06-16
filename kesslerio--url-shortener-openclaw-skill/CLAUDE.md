# url-shortener-openclaw-skill

> URL shortening via is.gd (no auth required, permanent links). Use when: 'shorten this URL', 'short link', 'make URL shorter', 'create short link'. Simple, fast, no tracking. NOT for branded short links or analytics (no custom domains supported). NOT for YOURLS links (use shapescale-tools for YOURLS).

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/url-shortener-openclaw-skill/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Shorten

Quickly shorten URLs using the [is.gd](https://is.gd) service. No API key or account required.

## Usage

```bash
shorten "https://example.com/very/long/url"
```

## Examples

**Standard usage:**
```bash
shorten "https://google.com"
# Output: https://is.gd/O5d2Xq
```

## Notes
- Links are permanent.
- No analytics dashboard (simple redirect).
- Rate limits apply (be reasonable).

---
> Source: [kesslerio/url-shortener-openclaw-skill](https://github.com/kesslerio/url-shortener-openclaw-skill) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-16 -->
