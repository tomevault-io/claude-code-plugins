# go-migrations

> SQL migration numbering and file conventions

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/go-migrations/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Database Migrations

- Use the next unused numeric prefix (check the migrations directory for the current highest).
- **Never** reuse or duplicate migration numbers.
- Provide paired `.up.sql` and `.down.sql` files when rollback is required.
- After adding migrations, run the repository's migration validation script if one is provided (see the repo-specific developer skill).

---
> Source: [Netcracker/qubership-apihub-backend](https://github.com/Netcracker/qubership-apihub-backend) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-05 -->
