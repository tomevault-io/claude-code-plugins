# fis-inscriptions-web

> Chaque fois qu'un bouton utilisant Tailwind CSS est généré ou modifié dans le projet, il doit inclure la classe `cursor-pointer`.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/fis-inscriptions-web/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# Règle Cursor : Boutons Tailwind

Chaque fois qu'un bouton utilisant Tailwind CSS est généré ou modifié dans le projet, il doit inclure la classe `cursor-pointer`.

Cela s'applique à tous les composants Button, DialogTrigger, ou tout élément interactif qui agit comme un bouton (ex : `<button>`, `<Button>`, `<DialogTrigger asChild>`, etc.).

**Exemple :**
```tsx
<Button className="... cursor-pointer ...">Action</Button>
<button className="... cursor-pointer ...">Action</button>
```

**But :**
- Améliorer l'accessibilité et l'expérience utilisateur.
- Rendre explicite le caractère cliquable/interactif de l'élément.

**Référence :**
- [Tailwind CSS - cursor](mdc:https:/tailwindcss.com/docs/cursor)

---
> Converted and distributed by [TomeVault](https://tomevault.io/claim/tmn73) — claim your Tome and manage your conversions.
<!-- tomevault:4.0:claude_md:2026-04-10 -->
