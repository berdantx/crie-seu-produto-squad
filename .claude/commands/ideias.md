---
description: Gera as 20 ideias de produto (etapa 3) a partir da pesquisa
argument-hint: [opcional, direcionamento]
---

O aluno quer gerar as 20 ideias de produto avulsas.

Direcionamento informado: $ARGUMENTS

1. Verifique os insumos: `producao/01-especialidade.md` e
   `producao/02-pesquisa.md`.
2. Se a pesquisa não existir, avise em uma linha e ofereça rodar `/pesquisa`
   primeiro (as ideias sem pesquisa saem genéricas). Se o aluno insistir em
   seguir sem, colete o nicho, salve `producao/01-especialidade.md` e siga
   avisando a limitação.
3. Despache o agente `gerador-de-ideias` (inclua o direcionamento do aluno
   no prompt, se veio).
4. Apresente a lista numerada e peça o número da escolhida. Quando o aluno
   escolher, registre na seção `## Escolhida` de `producao/03-ideias.md` e
   sugira `/oferta` como próximo passo.

Siga `conhecimento/_regras-globais.md` em tudo que escrever.
