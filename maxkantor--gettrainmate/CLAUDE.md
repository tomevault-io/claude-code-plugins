# frontend-ts-push

> After editing the Vite web app (TS/TSX), commit and push to origin.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/frontend-ts-push/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Frontend changes → commit and push

When you change any `*.ts` / `*.tsx` under `apps/web/` (including tests; `*.ts*` covers both):

1. Run **`npm run web:build`** from the repo root if the change affects production bundles (skip only for comment-only or trivial edits).
2. **`git add`** only paths under `apps/web/` (and `package-lock.json` if npm changed it for the web workspace). Do not stage unrelated root zips (`*.zip`) unless the user asked.
3. **`git commit`** with a clear message (e.g. `fix(web): …` or `feat(web): …`).
4. **`git push`** to the tracked upstream (e.g. `origin` + current branch).

If the working tree has no staged diff after add, do not create an empty commit. If push fails (auth/network), report the error and stop.

---
> Source: [maxkantor/GetTrainMate](https://github.com/maxkantor/GetTrainMate) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-04-19 -->
