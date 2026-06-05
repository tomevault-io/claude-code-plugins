# backend-db-migrations

> Backend SQL migration path and validation script

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/backend-db-migrations/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Backend Database Migrations

- Migrations live in `qubership-apihub-service/resources/migrations/`.
- Use the next unused numeric prefix (current highest is visible in that directory).
- **Never** reuse or duplicate migration numbers.
- Provide paired `.up.sql` and `.down.sql` files when rollback is required.
- After adding migrations, run from repo root:
  - Linux / WSL / Git Bash: `bash .cursor/skills/apihub-backend-developer/scripts/check_migration_numbers.sh`
  - Windows PowerShell: `powershell -File .cursor/skills/apihub-backend-developer/scripts/check_migration_numbers.ps1`

---
> Source: [Netcracker/qubership-apihub-backend](https://github.com/Netcracker/qubership-apihub-backend) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-05 -->
