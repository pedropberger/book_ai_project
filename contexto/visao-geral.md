# Visão Geral do Livro

## Título provisório
**Agentes de IA no Judiciário: Da Engenharia de Prompt à Orquestração Multi-Agente**

## Subtítulo provisório
*Técnicas aplicadas para construir sistemas inteligentes em instituições públicas*

## Autor
Pedro — Líder da UIS (Unidade de Inovação e Sustentabilidade) no MPES (Ministério Público do Espírito Santo)

## Tese central
É possível construir agentes de IA robustos e úteis para o judiciário brasileiro usando técnicas progressivas e bem fundamentadas — sem grandes orçamentos, sem equipes enormes, e com total controle sobre qualidade e governança.

## Público-alvo primário
- Servidores e gestores do judiciário com interesse em tecnologia e inovação
- Desenvolvedores de TI de órgãos públicos entrando em IA aplicada
- Analistas e engenheiros que já usam LLMs e querem ir além do ChatGPT

## Público-alvo secundário
- Estudantes e profissionais de IA interessados em aplicações no setor público
- Gestores de inovação de outras áreas do setor público

## Premissas
- O leitor não conhece ML profundo, mas tem raciocínio analítico
- Todos os exemplos são em Python e executáveis
- Os casos de uso são reais ou baseados em situações reais do MPES/judiciário
- O livro não é neutro: toma posição sobre boas práticas

## Diferencial
1. Progressão narrativa: o mesmo problema é resolvido com arquiteturas cada vez mais sofisticadas
2. Casos reais do judiciário: não são exemplos didáticos genéricos
3. Escrito por quem implementou, não por quem pesquisou
4. Cobre o ciclo completo: da ideia ao deploy, passando por governança

## Fio condutor
O caso de **triagem de petições iniciais** no MPES aparece em múltiplos capítulos, evoluindo conforme a arquitetura do agente:
- Cap 04: classificação simples com prompt + contexto
- Cap 05: enriquecimento com RAG (jurisprudência relevante)
- Cap 06: agente que lê o processo no PJe via API
- Cap 07: router que distribui por tipo de matéria para especialistas
- Cap 08: sistema multi-agente com revisor e escritor

## Formato de entrega
- Markdown puro, compilável via mdbook ou pandoc
- Código em Python, testado e versionado separadamente
- Estimativa: 250–350 páginas no formato final
