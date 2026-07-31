# repository-class-conventions

> Governs the structure and functionality of repository classes, emphasizing the use of JpaRepository, JPQL queries, and EntityGraphs to prevent N+1 problems.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/repository-class-conventions/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

- Must annotate repository classes with @Repository.
- Repository classes must be of type interface.
- Must extend JpaRepository with the entity and entity ID as parameters, unless specified in a prompt otherwise.
- Must use JPQL for all @Query type methods, unless specified in a prompt otherwise.
- Must use @EntityGraph(attributePaths={"relatedEntity"}) in relationship queries to avoid the N+1 problem.
- Must use a DTO as The data container for multi-join queries with @Query.

---
> Source: [NguyenMinh1912/ai-agent-demo](https://github.com/NguyenMinh1912/ai-agent-demo) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-31 -->
