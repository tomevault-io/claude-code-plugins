# 04-database

> The application uses Drizzle ORM for database operations.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/04-database/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Database Structure

The application uses Drizzle ORM for database operations.

## Database Schema and Configuration
- [app/db/schema.ts](mdc:app/db/schema.ts): Database schema definitions
- [app/db/index.ts](mdc:app/db/index.ts): Database connection setup
- [app/db/relations.ts](mdc:app/db/relations.ts): Relationship definitions between models
- [drizzle.config.ts](mdc:drizzle.config.ts): Drizzle ORM configuration

## Seed Data
The application includes seed data for initial database setup:
- [app/db/modelSeed.ts](mdc:app/db/modelSeed.ts): Seed data for AI models
- [app/db/providerSeed.ts](mdc:app/db/providerSeed.ts): Seed data for providers
- [app/db/groupSeed.ts](mdc:app/db/groupSeed.ts): Seed data for groups
- [app/db/botSeed.ts](mdc:app/db/botSeed.ts): Seed data for bots

---
> Source: [HiveNexus/HiveChat](https://github.com/HiveNexus/HiveChat) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-18 -->
