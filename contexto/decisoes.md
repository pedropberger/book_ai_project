# Log de Decisões Editoriais

> Decisões importantes sobre escopo, estrutura ou abordagem. Não alterar sem consultar Pedro.

---

## 2025 — Estrutura e escopo

### DEC-001 — Python como linguagem dos exemplos
**Data:** início do projeto
**Decisão:** Todos os exemplos de código serão em Python.
**Motivo:** É a linguagem dominante no ecossistema de IA; a maioria das bibliotecas (LangChain, LlamaIndex, Anthropic SDK, sentence-transformers) tem suporte nativo.
**Consequência:** Instalação de Python vai para Apêndice A1, não para o corpo do livro.

### DEC-002 — Instalação de ambiente no apêndice
**Data:** início do projeto
**Decisão:** Não haverá capítulo de setup no corpo principal. Vai para Apêndice A1.
**Motivo:** Quebra o ritmo para leitores que já sabem. Leitores iniciantes consultam quando necessário.

### DEC-003 — Progressão de níveis como espinha dorsal
**Data:** início do projeto
**Decisão:** A Parte IV organiza os agentes em níveis progressivos (0→4), usando o mesmo caso de uso (triagem de petições) como fio condutor.
**Motivo:** Dá narrativa ao livro. O leitor vê evolução, não um catálogo.

### DEC-004 — Casos reais do MPES
**Data:** início do projeto
**Decisão:** Sempre que possível, exemplos são baseados em implementações reais do MPES/UIS, com anonimização quando necessário.
**Motivo:** É o diferencial do livro. Exemplos inventados tiram credibilidade.

### DEC-005 — Livro toma posições
**Data:** início do projeto
**Decisão:** O livro não é neutro. Pedro emite opiniões sobre boas práticas, anti-padrões e escolhas de arquitetura.
**Motivo:** Livros que tentam cobrir "todos os lados" ficam sem utilidade prática. Quem está implementando precisa de recomendações.

---

## Como adicionar uma decisão

```
### DEC-XXX — Título curto
**Data:** AAAA-MM-DD
**Decisão:** O que foi decidido.
**Motivo:** Por que foi decidido assim.
**Consequência:** O que muda na estrutura ou no texto.
```
