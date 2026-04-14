# stock-market-platform

> always_complete_requests = true

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/stock-market-platform/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

[general]
always_complete_requests = true

[completion]
complete_entire_task_unless_user_says_otherwise = true

[output]
no_extra_comments = true
response_format = only_sql_query         ; Kullanıcı çıktısı sadece SQL sorgusu olmalı

[cursor_ai]
priority_1 = connect_to_db_with_mcp      ; 1. Adım: MCP ile bağlan
priority_2 = read_table_and_column_names ; 2. Adım: Tablo/sütun oku
priority_3 = write_sql_query             ; 3. Adım: SQL sorgusu yaz

[context]
database = mysql                         ; Veritabanı: MySQL
date_format = YYYY-MM-DD                 ; Tarih formatı

---
> Converted and distributed by [TomeVault](https://tomevault.io/claim/atillakesicioglu) — claim your Tome and manage your conversions.
<!-- tomevault:4.0:claude_md:2026-04-09 -->
