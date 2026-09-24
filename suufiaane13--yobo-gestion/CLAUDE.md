# yobo-frontend-ts

> TypeScript src — lib, store .ts, pas les tests

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/yobo-frontend-ts/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Fichiers `src/lib/`

- Logique **pure** de préférence ; exports via `src/lib/index.ts` quand c’est déjà le pattern du projet.
- **Ne pas** importer le store dans les utilitaires bas niveau (éviter les cycles).

# Store (`yobo-store.ts`)

- Nouvelles actions : suivre le style existant (`get()`, `set`, `invoke`, `client`, `logDevError`).
- `persist` Zustand : ne persister que le **thème** (ne pas ajouter PIN / données sensibles).

# Fichiers de tests

- Les `*.test.ts` ont une règle dédiée ; ici, ne pas les traiter comme du code prod.

---
> Source: [suufiaane13/yobo-gestion](https://github.com/suufiaane13/yobo-gestion) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-24 -->
