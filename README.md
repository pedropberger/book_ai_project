# Agentes de IA no Judiciário

**Livro técnico em escrita** — Pedro, UIS/MPES

> Técnicas de engenharia de IA e criação de agentes aplicadas ao Poder Judiciário brasileiro

---

## Estrutura do repositório

```
.
├── CLAUDE.md              ← leia primeiro se você é um agente de IA
├── contexto/              ← visão geral, sumário, estilo, glossário, decisões
├── manuscrito/            ← texto do livro, organizado por capítulo
│   └── XX-nome/
│       ├── 01-secao.md    ← seções individuais
│       └── _resumo.md     ← sinopse para manutenção de contexto
├── codigo/                ← exemplos executáveis, por capítulo
└── build/                 ← outputs gerados (PDF, epub)
```

## Status geral

Ver [`contexto/sumario.md`](contexto/sumario.md) para status detalhado por seção.

## Para escrever com Claude Code

1. Abra o repositório com `claude` na raiz
2. O agente lerá `CLAUDE.md` automaticamente
3. Peça para escrever uma seção específica: *"Escreva `manuscrito/04-agentes-nivel-0/02-prompt-e-contexto.md`"*
4. O agente carregará os `_resumo.md` relevantes para manter coerência
5. Após cada sessão, peça para atualizar o `_resumo.md` do capítulo

## Compilar o livro

```bash
# PDF via pandoc
pandoc manuscrito/**/*.md -o build/livro.pdf

# Site navegável via mdbook
mdbook build
```

## Convenções

- Front matter YAML em todos os arquivos de manuscrito
- Status: `rascunho` → `revisao` → `finalizado`
- Commits: `cap-04: rascunho seção 02 - engenharia de prompt`
- Código em `codigo/cap-XX/` nunca inline no texto
