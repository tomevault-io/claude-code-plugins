# state-sandbox

> This is a React Next.js project with a FastAPI Python backend.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/state-sandbox/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

This is a React Next.js project with a FastAPI Python backend.

Frontend (/frontend):

- Use .js for JSX files
- Use 'next/navigation' for all navigation/routing
- Use frontend/src/lib/api.js for all API calls
- Prefer shadcn/ui for components
- `DialogContent` requires a `DialogTitle` for the component to be accessible for screen reader users.
- It's `import { useToast } from '@/hooks/use-toast';` for toasts

Backend (/backend):

- Use pydantic for all data models
- Use backend/db/models.py for all database models
- Use backend/routers/schemas.py for all routes input/output pydantic models
- Use backend/routers/{table}.py for all routes for that table/model

---
> Source: [sshh12/state-sandbox](https://github.com/sshh12/state-sandbox) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-27 -->
