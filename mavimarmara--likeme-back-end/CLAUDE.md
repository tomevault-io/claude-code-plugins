# likeme-back-end

> Hooks com dependências corretas e sem “memoização por memoização”

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/likeme-back-end/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Regra de hooks (useCallback/useMemo)

- Use `useCallback`/`useMemo` somente quando houver ganho real (evitar re-renders ou custo elevado); não como padrão automático.
- Garanta dependências corretas: se o callback/memo usa um valor, ele precisa aparecer nas dependências.
- Evite criar lógica pesada no corpo do render; prefira helper/mapeamento fora do componente quando possível.

---
> Converted and distributed by [TomeVault](https://tomevault.io/claim/Mavimarmara)
> This is a context snippet only. You'll also want the standalone SKILL.md file — [download at TomeVault](https://tomevault.io/claim/Mavimarmara)
<!-- tomevault:4.0:claude_md:2026-04-09 -->
