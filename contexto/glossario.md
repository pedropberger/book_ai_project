# Glossário

> Adicione novos termos conforme aparecem no manuscrito. O agente deve consultar este arquivo antes de introduzir qualquer termo técnico.

## A

**Alucinação (hallucination)** — Quando um LLM gera informação factualmente incorreta com aparente confiança. Não é um bug: é consequência da forma como modelos de linguagem funcionam.

**Agente** — Sistema que usa um LLM como núcleo de raciocínio para tomar decisões, executar ações e iterar com base em resultados, em ciclos autônomos.

## B

**BM25** — Algoritmo de busca textual baseado em frequência de termos. Padrão do Elasticsearch e Solr. Ainda supera embeddings em buscas exatas por termos específicos.

**Banco vetorial (vector store)** — Banco de dados otimizado para armazenar e buscar embeddings por similaridade. Exemplos: Qdrant, pgvector, Weaviate, Pinecone.

## C

**Chunking** — Divisão de documentos longos em pedaços menores para indexação em RAG. A estratégia de chunking afeta diretamente a qualidade da recuperação.

**Contexto (context window)** — Quantidade máxima de tokens que um LLM processa em uma única interação (prompt + resposta).

## E

**Embedding (incorporação vetorial)** — Representação numérica de um texto como vetor em espaço de alta dimensão. Textos semanticamente similares ficam próximos nesse espaço.

**Eval** — Processo de avaliação sistemática da qualidade de um agente ou pipeline, podendo ser automatizado, manual ou híbrido.

## F

**Faithfulness** — Métrica de RAG: o quanto a resposta gerada é fiel ao contexto recuperado (ausência de alucinações sobre o contexto).

**Few-shot** — Técnica de prompt que inclui exemplos de entrada/saída para guiar o comportamento do modelo.

## H

**HyDE (Hypothetical Document Embeddings)** — Técnica de RAG: gerar um documento hipotético com o LLM e usar seu embedding para busca, em vez do embedding da pergunta original.

**Human-in-the-loop** — Ponto no pipeline onde um humano revisa ou aprova antes de prosseguir.

## L

**LLM (Large Language Model)** — Modelo de linguagem de grande escala treinado em enormes volumes de texto. Exemplos: Claude, GPT-4, Gemini, Llama.

## O

**Orquestração** — Coordenação de múltiplos agentes ou componentes de um pipeline, definindo fluxo, dependências e tratamento de erros.

## P

**Prompt** — Texto enviado ao LLM como instrução. Inclui system prompt (instrução de comportamento) e user prompt (mensagem do usuário).

**Pipeline** — Sequência de etapas de processamento, onde o output de uma etapa alimenta a próxima.

**PJe** — Processo Judicial eletrônico. Sistema do CNJ usado por grande parte do judiciário brasileiro.

## R

**RAG (Retrieval-Augmented Generation)** — Técnica que combina recuperação de documentos relevantes com geração de resposta pelo LLM, enriquecendo o contexto com informação externa.

**Reranking** — Etapa pós-recuperação que reordena resultados usando um modelo mais preciso (mas mais lento) para melhorar a relevância.

**Router** — Agente ou componente responsável por classificar uma entrada e direcioná-la para o especialista correto.

## S

**SEI** — Sistema Eletrônico de Informações. Plataforma de gestão de documentos e processos administrativos usada por órgãos públicos.

**System prompt** — Instrução fixa enviada ao LLM antes da conversa, definindo papel, comportamento e restrições.

## T

**Token** — Unidade básica de processamento de LLMs. Aproximadamente 0,75 palavras em português. Preço e limite de contexto são medidos em tokens.

**Tool calling (chamada de ferramenta)** — Capacidade do LLM de invocar funções externas estruturadas (buscar na web, consultar API, calcular) e incorporar o resultado no raciocínio.

## V

**Vector search (busca vetorial)** — Busca por similaridade semântica usando embeddings, em vez de correspondência exata de palavras-chave.
