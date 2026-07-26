# pwa-kit

> When accessibility is checked. Check if heading levels should increase sequentially for semantic structure

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/pwa-kit/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Rule: accessibility-heading-order

Heading levels should increase sequentially for semantic structure

## 🔍 Pattern

```regex
<h([3-6])>
```

## 📍 Examples

```tsx
// ❌ Bad
<h1>Main Title</h1>
<h4>Subsection</h4>
// ✅ Good
<h1>Main Title</h1>
<h2>Subsection</h2>
```

---
> Source: [SalesforceCommerceCloud/pwa-kit](https://github.com/SalesforceCommerceCloud/pwa-kit) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-26 -->
