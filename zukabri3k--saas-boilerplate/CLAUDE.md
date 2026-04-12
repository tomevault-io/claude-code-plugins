# saas-boilerplate

> Règles TypeScript pour le backend NestJS

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/saas-boilerplate/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Règles TypeScript - Backend NestJS

## Conventions de code
- Utiliser des **semicolons** à la fin de chaque instruction
- Utiliser des **guillemets doubles** pour les strings
- Préférer `const` et `let` plutôt que `var`
- Utiliser des **interfaces** plutôt que des types pour les objets complexes

## Structure NestJS
- Controllers dans `src/controllers/`
- Services dans `src/services/`
- Modules dans `src/modules/`
- DTOs dans `src/dto/`
- Entities dans `src/entities/`

## Prisma
- Schéma dans [apps/backend/prisma/schema.prisma](mdc:apps/backend/prisma/schema.prisma)
- Client généré dans `apps/backend/generated/prisma`
- Toujours utiliser `DATABASE_URL` dans les variables d'environnement

## Imports
- Imports relatifs pour les fichiers du projet
- Imports absolus pour les packages npm
- Grouper les imports: Node.js, packages externes, fichiers locaux

## Tests
- Fichiers de test avec extension `.spec.ts`
- Utiliser Jest pour les tests unitaires
- Tests e2e dans le dossier `test/`

---
> Converted and distributed by [TomeVault](https://tomevault.io/claim/ZukaBri3k)
> This is a context snippet only. You'll also want the standalone SKILL.md file — [download at TomeVault](https://tomevault.io/claim/ZukaBri3k)
<!-- tomevault:4.0:claude_md:2026-04-08 -->
