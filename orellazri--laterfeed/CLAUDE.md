# laterfeed

> Laterfeed is an application that serves as a "read-it-later" and "watch-it-later" saver and serves them as an Atom feed to be used in RSS clients.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/laterfeed/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Laterfeed

Laterfeed is an application that serves as a "read-it-later" and "watch-it-later" saver and serves them as an Atom feed to be used in RSS clients.

Tech Stack: Rust, Axum, SQLx (SQLite), Utoipa (OpenAPI)

Chrome extension lives under `extension/chrome`. Firefox extension lives under `extension/firefox`.

## Important Notes

- When adding dependencies, use `cargo add` to get the latest versions. Do not update `Cargo.toml` manually.
- After making changes, run `cargo clippy` and fix any issues.
- After making chages, run the tests using `just test`.
- To create database migrations, just `just migrate-create <name>`.
- When updating code in one extension (Chrome/Firefox), make sure to also make the same changes in the other extesnsion so they're aligned.

---
> Source: [orellazri/laterfeed](https://github.com/orellazri/laterfeed) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-02 -->
