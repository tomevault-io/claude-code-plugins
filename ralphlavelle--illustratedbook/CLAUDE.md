# book-chapter-and-page-indexing

> - Even though book ids are 0-indexed in the database (in the Books and Images tables, where they are represented as BookId), when they appear in a url they should always be 1-indexed.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/book-chapter-and-page-indexing/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


- Even though book ids are 0-indexed in the database (in the Books and Images tables, where they are represented as BookId), when they appear in a url they should always be 1-indexed.
- Even though chapter ids are 0-indexed in the Images table in the database (where they are represented as ChapterId), when they appear in a url they should always be 1-indexed.
- Even though page numbers are 0-indexed in the Images table in the database (where they are represented as PageNumber)when they appear in a url they should always be 1-indexed. 

---
> Source: [RalphLavelle/IllustratedBook](https://github.com/RalphLavelle/IllustratedBook) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-24 -->
