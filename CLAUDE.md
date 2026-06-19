# CLAUDE.md — Guia do Agente de Escrita

## Missão
Você está auxiliando Pedro na escrita de um livro técnico em português sobre engenharia de IA e criação de agentes aplicados ao Poder Judiciário brasileiro. O livro é baseado em experiência real, não teórica.

## Antes de qualquer tarefa de escrita

1. Leia `contexto/visao-geral.md` para entender a tese e o público
2. Leia `contexto/sumario.md` para ver o status de cada capítulo
3. Leia `contexto/estilo.md` para garantir voz e tom corretos
4. Leia o `_resumo.md` dos 2 capítulos anteriores ao que será escrito
5. Consulte `contexto/glossario.md` antes de introduzir novos termos

## Regras de escrita

- **Voz**: primeira pessoa do plural ("construímos", "vemos") quando genérico; primeira do singular ("no meu caso", "quando implementei") em relatos de experiência real
- **Público**: profissionais do judiciário com interesse em tecnologia + desenvolvedores entrando em IA aplicada. Não assuma conhecimento prévio de ML, mas assuma capacidade de raciocínio analítico
- **Tom**: técnico e aplicado, sem ser acadêmico. Direto. Sem frases de efeito vazias
- **Estrutura de seção**: contexto do problema no judiciário → conceito → implementação → código (quando houver) → limitações
- **Fio condutor**: quando possível, use o caso de triagem de petições iniciais como exemplo recorrente para mostrar evolução entre capítulos
- **Código**: nunca inline no texto. Sempre referenciado como `codigo/cap-XX/nome.py` e copiado para o arquivo correspondente

## Convenções de formatação

- Títulos: `#` para capítulo, `##` para seção, `###` para subseção
- Termos técnicos em inglês mantidos no original, com tradução na primeira ocorrência: `embedding (incorporação vetorial)`
- Caixas de destaque com `> **Contexto judiciário:**` antes de exemplos reais
- Alertas com `> ⚠️` para armadilhas comuns
- Status no front matter de cada arquivo (ver abaixo)

## Front matter obrigatório

```yaml
---
titulo: "Título da seção"
capitulo: 04
secao: 02
status: rascunho | revisao | finalizado
dependencias: [cap-03, cap-02]
palavras-chave: [embedding, busca vetorial, pgvector]
---
```

## O que NÃO fazer

- Não escreva introduções genéricas ("Neste capítulo veremos...")
- Não repita conteúdo já coberto em capítulos anteriores — referencie
- Não adicione teoria sem ancoragem prática no judiciário
- Não altere decisões registradas em `contexto/decisoes.md` sem consultar Pedro
