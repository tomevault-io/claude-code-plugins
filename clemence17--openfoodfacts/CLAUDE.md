# openfoodfacts

> - Projet: cache local OpenFoodFacts + app Streamlit

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/openfoodfacts/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

- Projet: cache local OpenFoodFacts + app Streamlit
- Objectif: maintenir un cache local (SQLite) mis à jour régulièrement, puis afficher des métriques/calculs via Streamlit.
- Contraintes:
  - Éviter de télécharger des dumps complets par défaut (trop volumineux) ; préférer une synchronisation "recent" et paramétrable.
  - Stockage local: SQLite dans `data/off_cache.sqlite`.
  - Les scripts doivent fonctionner sous Windows (PowerShell) et être planifiables via Task Scheduler.

---
> Converted and distributed by [TomeVault](https://tomevault.io/claim/clemence17) — claim your Tome and manage your conversions.
<!-- tomevault:4.0:claude_md:2026-04-10 -->
