# coagenthub

> For Drizzle ORM, follow:

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/coagenthub/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

For Drizzle ORM, follow:
1. Import schema tables with a `Table` suffix alias, e.g.
   `import { user as userTable } from "@laizhixingxingdeli/database/schema";`
2. Use the Drizzle callback query syntax, e.g.
   `await db.query.user.findFirst({ where: (t, { eq }) => eq(t.role, "admin") });`

For the backend, follow:
1. Define API routes and schemas with Hono OpenAPI (describeRoute).
2. Validate request bodies with Hono Zod Validator.
3. Report errors through BizError/BizCodeEnum from @laizhixingxingdeli/error.
4. Route handlers stay thin; shared write paths live in lib/.

---
> Source: [laizhixingxingdeli/CoAgentHub](https://github.com/laizhixingxingdeli/CoAgentHub) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-08-18 -->
