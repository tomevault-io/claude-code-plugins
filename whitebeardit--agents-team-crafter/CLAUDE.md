# second-brain-commit-push

> Ao alterar o vault Whitebeard (second-brain), commit e push obrigatórios no fim da tarefa.

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/second-brain-commit-push/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:


# Second-brain (vault): commit e push

Raiz Git do vault Whitebeard: **`/home/whitebeard/DEV/OBSIDIAN/WhitebeardKnowledgeBaseAI`** (remote típico: `second-brain`).

Depois de criar, editar ou apagar ficheiros nesse repo, **antes de concluir a tarefa**: `git status` → `git add` (só o que esta sessão alterou para o pedido) → `git commit` (mensagem clara; prefixo `docs`/`vault` se aplicável) → `git push` no branch actual (normalmente `main`). Não deixar alterações só no working tree.

**Excepção:** o utilizador pede explicitamente não commitar ou rever primeiro.

---
> Source: [whitebeardit/agents-team-crafter](https://github.com/whitebeardit/agents-team-crafter) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-06-25 -->
