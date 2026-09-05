# management-web-form-eyebrow

> Management-web field labels use control eyebrows, not freestanding Label

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/management-web-form-eyebrow/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Management Web: Form Field Labels (Eyebrow)

When labeling inputs, selects, and grouped checkbox lists on **`apps/management-web`** pages:

## Do

- Use **`eyebrow`** on **`TextInput`**, **`FormDropdown`**, and **`CheckboxFieldList`** from **`@podverse/ui`** so the title sits inside the shared field chrome (same pattern as web login and management settings).
- For lookup rows with **`LookupFieldGrid`**, use **`variant="inlineEyebrow"`** when each column uses in-field eyebrows so the primary action column aligns to the control baseline.

## Do not

- Do **not** stack **`Label`** (from **`@podverse/ui`**) above **`TextInput`**, **`FormDropdown`**, or **`CheckboxFieldList`** for ordinary field titles — that duplicates the eyebrow pattern and breaks toolbar alignment.

## Exceptions

- **Section/page titles** (**`SectionHeading`**, **`ManagementPageShell`** **`title`**) and **read-only** **`DescriptionList`** **`dt`/`dd`** rows are not single-field labels.
- **`Fieldset`** **`legend`** for grouped matrices (e.g. permission grids) is group chrome, not a per-control eyebrow.

---
> Source: [podverse/podverse](https://github.com/podverse/podverse) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-09-05 -->
