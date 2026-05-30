# 03-data-storage

> Interacting with the database, storing data, and retrieving data

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/03-data-storage/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Data Storage

The application uses Isar as its local database solution.

## Service Configuration
- [lib/services/isar_service.dart](mdc:lib/services/isar_service.dart) - Contains the Isar database initialization and management logic

## Data Flow
1. The database is initialized in [main.dart](mdc:lib/main.dart)
2. Feature repositories (like [lib/features/track/repositories/routine_repository.dart](mdc:lib/features/track/repositories/routine_repository.dart)) interact with the database through the IsarService
3. Models are used to represent the data schema and are typically stored in the `models` directory of each feature

## Working with Data
- When adding a new data model, make sure to update the IsarService
- Repositories should handle all database operations
- Use the repository pattern to abstract database operations from the UI layer

---
> Source: [shareefhadid/traak](https://github.com/shareefhadid/traak) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-30 -->
