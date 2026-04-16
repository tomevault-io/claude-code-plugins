# template-backend

> Convenções Prisma e PostgreSQL

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/template-backend/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Prisma e Database

- Ao realizar alterações no banco via prisma, utilizar o agent `prima-specialist.md`
- Schema em `prisma/schema.prisma` na raiz (convenção oficial)
- Models em camelCase (PascalCase para nomes de model)
- Usar singleton em `src/infrastructure/database/prisma.ts` — nunca instanciar PrismaClient diretamente
- Migrações: `npm run db:migrate` (não criar SQL manualmente; usar `prisma migrate dev`)
- Gerar client após alterar schema: `npm run db:generate`
- Referência: `prisma/schema.prisma` e modelo `HealthCheck`

---
> Converted and distributed by [TomeVault](https://tomevault.io/claim/ghastsantos) — claim your Tome and manage your conversions.
<!-- tomevault:4.0:claude_md:2026-04-09 -->
