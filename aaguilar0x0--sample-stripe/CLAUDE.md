# sample-stripe

> Project database context and data type and data flow

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/sample-stripe/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

This project is using supabase and there is a file [database.types.ts](mdc:src/lib/extern/db/supabase/database.types.ts) that describes the database schema.

It is then decoupled and abstracted as Data Transfer Object (DTO) for the architecture, and is using zod for schema validation

each entity has a DTO file in `src/lib/core/dtos` directory.

---
> Converted and distributed by [TomeVault](https://tomevault.io/claim/AAguilar0x0)
> This is a context snippet only. You'll also want the standalone SKILL.md file — [download at TomeVault](https://tomevault.io/claim/AAguilar0x0)
<!-- tomevault:4.0:claude_md:2026-04-08 -->
