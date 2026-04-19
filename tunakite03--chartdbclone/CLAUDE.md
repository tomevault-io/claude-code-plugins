# chartdbclone

> Performance guidelines

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/chartdbclone/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Performance

- Correctness first. Optimize only when measured to be slow.
- Avoid N+1 queries. Batch database operations.
- Paginate list responses. No unbounded result sets.
- Lazy load routes and heavy components.
- Debounce user input handlers.
- Use connection pooling for databases.
- Stream large responses instead of buffering.

---
> Converted and distributed by [TomeVault](https://tomevault.io/claim/Tunakite03) — claim your Tome and manage your conversions.
<!-- tomevault:4.0:claude_md:2026-04-09 -->
