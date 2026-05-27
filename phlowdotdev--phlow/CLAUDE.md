# phlow

> Este repositorio contem o runtime Phlow escrito em Rust, com modulos em `modules/`

## Usage

Add this to your project's CLAUDE.md to activate this skill:

```
Read and follow the instructions in .claude/skills/phlow/SKILL.md
```

Or copy the instructions below directly into your CLAUDE.md:

# AGENTS

Este repositorio contem o runtime Phlow escrito em Rust, com modulos em `modules/`
e o runtime principal em `phlow-runtime/`. Use `rg` para buscas.

Comandos comuns (raiz do repo):
- Build do runtime: `cargo build --release -p phlow-runtime`
- Rodar exemplo: `cargo run -p phlow-runtime -- examples/<caminho>.phlow`
- Empacotar modulos: `./scripts/packages.sh`

Estrutura relevante:
- `phlow-runtime/`: runtime principal
- `modules/`: modulos locais
- `phlow-sdk/`: SDKs
- `examples/`: fluxos de exemplo
- `scripts/`: scripts auxiliares

Regra:
- Analisar de concluir a tarefa, testar localmente os fluxos alterados.
- Quando uma tarefa for concluida e testada, comitar as mudancas.
- Documente todas as features novas ou alteracoes significativas com rustdoc.
- Sempre escreva testes para novas funcionalidades.

---
> Source: [phlowdotdev/phlow](https://github.com/phlowdotdev/phlow) — distributed by [TomeVault](https://tomevault.io).
<!-- tomevault:4.0:claude_md:2026-05-27 -->
