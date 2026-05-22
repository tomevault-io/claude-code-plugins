# data-layer-patterns

> The data source management follows a CRUD pattern implemented in [source_service.py](mdc:observer/cortex/cortex/core/data/db/source_service.py).

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/data-layer-patterns/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Data Layer Patterns

## Data Source Management
The data source management follows a CRUD pattern implemented in [source_service.py](mdc:observer/cortex/cortex/core/data/db/source_service.py).

### Key Components:
- `DataSourceCRUD`: Main service class for data source operations
- `DataSourceORM`: SQLAlchemy ORM model for data sources
- `DataSource`: Pydantic model for data validation

### Best Practices:
1. Always use session management with try/finally blocks:
```python
db_session = LocalSession().get_session()
try:
    # Database operations
    db_session.commit()  # If writing data
finally:
    db_session.close()
```

2. Handle transactions properly:
- Use `db_session.commit()` after successful operations
- Use `db_session.rollback()` in exception handlers
- Always close sessions in finally blocks

3. Error Handling:
- `DataSourceAlreadyExistsError`: When creating duplicate sources
- `DataSourceDoesNotExistError`: When accessing non-existent sources
- Handle `IntegrityError` for database constraints

4. Data Validation:
- Use Pydantic models for input validation
- Convert between ORM and Pydantic models using `model_validate`
- Include proper type hints for all methods

---
> Source: [TelescopeAI/cortex](https://github.com/TelescopeAI/cortex) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-21 -->
