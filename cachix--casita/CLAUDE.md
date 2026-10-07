# casita

> Read `../BRANDING.md` before changing the docs' visual identity. The user

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/casita/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Documentation design

Read `../BRANDING.md` before changing the docs' visual identity. The user
approved the Casita companion logo from the Obrador repository, with the
Rust-orange Root House and lowercase wordmark. Reuse the
canonical SVGs in `public/brand/` and the shared `BrandLogo` component.

Preserve the existing Astro/Starlight and site-kit integration and the
Cloudflare Workers deployment flow. Validate changes with `npm run validate`
from this directory (or `devenv shell -- npm --prefix docs run validate`
from the repository root).

---
> Source: [cachix/casita](https://github.com/cachix/casita) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-10-06 -->
