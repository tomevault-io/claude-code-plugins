# i18n

> Internationalisation rules for SOGo. Apply when creating or editing React components, forms, or any UI text.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/i18n/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# i18n Conventions — SOGo

## Hard rule
NEVER hardcode strings in JSX. ESLint rule `react/jsx-no-literals` will fail the build.

## Correct pattern
```tsx
const t = useTranslations('NAMESPACE')
return <span>{t('MY_KEY')}</span>

---
> Source: [Alinto/SOGo6-UI](https://github.com/Alinto/SOGo6-UI) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-03 -->
