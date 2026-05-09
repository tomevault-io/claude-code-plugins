# theme-settings

> Guidelines and examples for organizing and structuring the Shopify theme settings schema.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/theme-settings/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Settings Schema Standards

## Settings Schema Structure

```json
{
  "name": "theme_info",
  "theme_name": "Theme Name",
  "theme_version": "1.0.0",
  "theme_author": "Author Name",
  "theme_documentation_url": "https://...",
  "theme_support_url": "https://..."
},
{
  "name": "Colors",
  "settings": [
    {
      "type": "header",
      "content": "Brand Colors"
    },
    {
      "type": "color",
      "id": "color_primary",
      "label": "Primary",
      "default": "#121212"
    }
  ]
}
```

## Setting Categories

**Typography:**
- `font_picker` for font selections
- `range` for font sizes (12-72px)
- `select` for font weights

**Layout:**
- `range` for spacing (0-100px)
- `select` for layout options
- `checkbox` for feature toggles

**Performance:**
- `checkbox` for lazy loading
- `select` for image quality
- `number` for pagination limits

---
> Source: [Shopify/horizon](https://github.com/Shopify/horizon) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-04 -->
