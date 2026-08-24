# tech-stack

> Keep docs/TECH_STACK.md updated when stack-related changes are made

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/tech-stack/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Tech stack documentation

Canonical reference: [`docs/TECH_STACK.md`](../../docs/TECH_STACK.md)

When adding or changing stack-related items, update that file in the same change:

- New or removed **npm dependencies** (especially runtime deps)
- **Supabase** migrations, Edge Functions, secrets, or env vars
- **EAS** build profiles, Expo plugins, or native modules
- **External services** (OpenAI, Google Places, RevenueCat, Sentry, etc.)
- **Build / CI / deploy** tooling

Add a row to the **Changelog** section with the date and a one-line summary.

---
> Source: [cameronconspm/Listio](https://github.com/cameronconspm/Listio) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-22 -->
