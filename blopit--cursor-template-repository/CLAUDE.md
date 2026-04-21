# cursor-template-repository

> Guidelines for model-driven development workflow

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/cursor-template-repository/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Model-Driven Development Guidelines

## Workflow
1. Edit JSON model definitions in model_definitions/
2. Run sync_models.sh to generate code
3. Never modify generated files directly
4. Add custom routes in src/custom_routes/

## Model Definition Standards
- Use snake_case for all fields
- Include clear field descriptions
- Define relationships explicitly
- Specify validation rules
- Document API endpoints

## Generated Code
- Models: src/models/
- Schemas: src/schemas/
- Routes: src/routes/
- Never edit generated files

## Testing
- Validate model definitions
- Test generated endpoints
- Verify relationships
- Check database migrations

---
> Converted and distributed by [TomeVault](https://tomevault.io/claim/blopit) — claim your Tome and manage your conversions.
<!-- tomevault:4.0:claude_md:2026-04-09 -->
