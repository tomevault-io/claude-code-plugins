# wisegold-front-v2

> - /customers/:accountId

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/wisegold-front-v2/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Definicios de acceso a rutas segun el tipo de usuario:

- **ADMIN**:
  - /
  - /customers
  - /customers/:accountId
  - /accounts/:accountId
  - /holdig/details/:customer_id
- **CLIENT**:
  - /
  - /create-account
- **BROKER**:
  - /
  - /customers
  - /customers/:accountId
  - /holdig/details/:customer_id
- **AGENT**:
  - /
  - /customers
  - /customers/:accountId
  - /holdig/details/:customer_id

# Archivo de enrutamiento

- `src/routes/hooks/useAppRoutes.tsx`

---
> Converted and distributed by [TomeVault](https://tomevault.io/claim/kikedevelopers) — claim your Tome and manage your conversions.
<!-- tomevault:4.0:claude_md:2026-04-13 -->
