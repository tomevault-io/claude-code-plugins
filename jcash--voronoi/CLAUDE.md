# voronoi

> - Use simple Markdown tables with rows for 10k, 100k, and issue48.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/voronoi/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Performance reporting

- Use simple Markdown tables with rows for 10k, 100k, and issue48.
- Diagram generation: `Case | Dev | Current | Boost | Current/Boost`.
- Unique-vertex gathering: `Case | Dev | Current | Boost`; exclude diagram generation and output allocation from the timing.
- Memory: `Case | Dev | Current | Boost | Current/Boost`; include peak bytes and allocation counts.
- Keep diagram generation, unique-vertex gathering, and memory in separate tables.

---
> Source: [JCash/voronoi](https://github.com/JCash/voronoi) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-08 -->
