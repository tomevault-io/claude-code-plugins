# perf-version-record

> Every new gcry version must refresh % of Boehm in docs/PERF.md for / and /json

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/perf-version-record/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Version performance recording

When preparing or cutting a **new version** (CHANGELOG / `shard.yml` / `Gcry::VERSION` bump):

1. Same-host wrk for **both** paths vs **Boehm** (`wrk -c 100 -d 30`, fresh process per path).
2. Update the **% of Boehm** table in [docs/PERF.md](docs/PERF.md) (`/` and `/json`; note chunk-release if measured).
3. CHANGELOG: cite **% of Boehm** for both paths, link `docs/PERF.md`.
4. Refresh the README Performance table from PERF.md (do not invent numbers).
5. Prefer **`/json`** when summarizing “did GC get better?”; keep `/` as idle-path sanity.

Fixed load: `bench/kemal` release + `-Dgc_none` (Boehm: omit flag). See PERF.md.

---
> Source: [sdogruyol/gcry](https://github.com/sdogruyol/gcry) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-07-24 -->
