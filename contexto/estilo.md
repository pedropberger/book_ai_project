# Guia de Estilo e Voz

## Voz e pessoa

- **1ª pessoa do singular** para relatos de experiência real: "quando implementei", "no meu caso", "aprendi da pior forma que..."
- **1ª pessoa do plural** para afirmações técnicas gerais: "construímos", "vemos que", "precisamos garantir"
- **2ª pessoa** para instruções diretas ao leitor: "execute o script", "observe o output", "cuidado com esse ponto"
- Nunca voz passiva quando há alternativa ativa

## Tom

- Técnico e direto, sem ser frio
- Sem frases de efeito acadêmicas: ❌ "No contexto da transformação digital" ✅ "Quando comecei a automatizar triagens no MPES..."
- Pode ter humor seco e autoironia quando pertinente
- Pode e deve emitir opiniões sobre boas práticas — o livro toma posições

## Exemplos de abertura de seção

❌ Ruim: "Nesta seção, exploraremos o conceito de embedding e sua aplicação em sistemas de busca semântica."

✅ Bom: "Antes de existirem embeddings na nossa stack, a busca de jurisprudência era um pesadelo de palavras-chave. Um advogado que digitava 'rescisão indireta' não encontrava nada sobre 'justa causa do empregador' — mesmo sendo o mesmo conceito."

## Termos técnicos

- Primeiro uso: termo em inglês + tradução entre parênteses: `embedding (incorporação vetorial)`
- Usos seguintes: pode usar o termo em inglês sem tradução
- Nunca traduzir à força quando o termo em inglês é consagrado (ex: "token" não vira "ficha")
- Siglas do judiciário: escrever por extenso na primeira ocorrência (PJe — Processo Judicial eletrônico)

## Caixas de destaque

```markdown
> **Contexto judiciário:** Texto explicando como o conceito se aplica
> especificamente ao cenário do judiciário ou MPES.
```

```markdown
> ⚠️ **Armadilha comum:** Descrição do erro que Pedro ou outros cometeram
> e como evitar.
```

```markdown
> 💡 **Dica de implementação:** Atalho ou boa prática descoberta na prática.
```

## Código

- Sempre em arquivo separado em `codigo/cap-XX/`
- No texto, referenciar com: `(ver \`codigo/cap-05/rag_basico.py\`)`
- Mostrar apenas trechos relevantes inline, com `# ...` para indicar código omitido
- Todo código precisa ser executável e testado

## Comprimento de seção
- Seção: 800–2500 palavras
- Subseção (`###`): 200–800 palavras
- Nunca seção de menos de 400 palavras — se for curta, mesclar com outra

## O que evitar
- Listas de bullet points como substituto de argumentação
- Definições de dicionário no início de seção
- "Como veremos adiante" — mostre, não prometa
- Repetição de conceitos já explicados — referencie o capítulo
