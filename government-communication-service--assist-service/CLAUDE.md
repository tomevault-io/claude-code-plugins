# responses-in-the-service-layer-and-api-layer

> When creating a new function in the service layer, try to return simple data structures, rather than Pydantic models.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/responses-in-the-service-layer-and-api-layer/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

When creating a new function in the service layer, try to return simple data structures, rather than Pydantic models.

When creating a new API endpoint, the endpoint should receive simple data structures from the service layer, and then perform the tasks required to put the simple data into a Pydantic model for the response.

The reason for this is to keep the service layer functions simple, and to make it the sole responsibility of the API layer to make sure API responses are formatted correctly.

---
> Source: [Government-Communication-Service/assist_service](https://github.com/Government-Communication-Service/assist_service) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-21 -->
