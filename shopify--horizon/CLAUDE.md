# assets

> Static files (css, js, and images) for theme templates

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/assets/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Assets

The assets directory contains any assets that need to be referenced within a `.liquid` file, usually using the [asset_url](mdc:https:/shopify.dev/docs/api/liquid/filters/asset_url) Liquid filter.

Assets is a flat directory, it may not contain subdirectories.

Any images that are required in the code, including icons, may be stored within assets.  Icons can be used in `.liquid` files via the [inline_asset_content](mdc:https:/shopify.dev/docs/api/liquid/filters/inline_asset_content) Liquid filter.

---
> Source: [Shopify/horizon](https://github.com/Shopify/horizon) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-04 -->
