# i18n

> Bilingual UI — Polish and English

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/i18n/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# i18n

- Two languages: **PL** (default) and **EN**
- Translations in `src/i18n/translations.js` — `t(key)` returns current language string
- HTML attributes: `data-i18n` (textContent), `data-i18n-placeholder`, `data-i18n-aria`
- Language stored in `localStorage` key `ndexplorer-lang`
- When adding new UI text, always add both PL and EN keys

---
> Source: [maciejaszex/ndexplorer](https://github.com/maciejaszex/ndexplorer) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-04-30 -->
