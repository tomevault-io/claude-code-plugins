# html-and-css

> When embedding variables within the HTML files, always include as variables (never functions). For example, if you need to display a name that requires formatting, include {{formatted_name}} rather than {{formatName(unformatted_name)}}.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/html-and-css/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


When embedding variables within the HTML files, always include as variables (never functions). For example, if you need to display a name that requires formatting, include {{formatted_name}} rather than {{formatName(unformatted_name)}}. 

Prefer to use Angular's @for syntax rather than *ngFor. 

Do not use 'id' fields unless that id will be explicitly referenced within the code.

Use snake-case for CSS class and style names

When styling elements that are drawn from the Angular Material library, we angular materials default styling as much as possible. Do not use ::ng-deep to override styles. 

---
> Source: [UnstableDesign/AdaCAD](https://github.com/UnstableDesign/AdaCAD) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-10-07 -->
