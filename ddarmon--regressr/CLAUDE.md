# regressr

> This repository provides utilities for regression testing across commit SHAs of

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/regressr/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

This repository provides utilities for regression testing across commit SHAs of
R packages.

# Contribution Guidelines

-   **Style**: Follow the [tidyverse style guide](https://style.tidyverse.org/).
    Use `snake_case` for object names and put spaces around assignment operators
    (`<-`). Keep lines under 80 characters where possible.

-   **Documentation**: Document exported functions with `roxygen2` comments so
    `roxygen2::roxygenise()` can generate the `NAMESPACE` and man pages.

-   **Purpose**: The package is intended for comparing SHA snapshots of packages
    to ensure no behavioral changes across exhaustive sets of files. All
    changes should preserve existing input/output behaviour unless explicitly
    intended.

---
> Source: [ddarmon/regressr](https://github.com/ddarmon/regressr) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-30 -->
