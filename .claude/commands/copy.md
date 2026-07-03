---
description: Escreve ou reescreve a copy da página de vendas (etapa 6)
argument-hint: [opcional, ajuste desejado]
---

O aluno quer a copy da página, avulsa ou reescrita.

Pedido informado: $ARGUMENTS

1. Verifique o insumo: `producao/05-concepcao.md`.
2. Se não existir, colete o mínimo em UMA rodada de perguntas: o produto, a
   promessa (resultado em uma frase), para quem é e o preço. Salve como
   `producao/05-concepcao.md` marcado como versão express.
3. Se `producao/06-copy.md` já existe e o pedido é ajuste, despache o agente
   `copywriter-da-pagina` com a instrução exata do ajuste, deixando claro que
   o resto do texto aprovado não muda.
4. Se é copy nova, despache o agente `copywriter-da-pagina` normalmente.
5. Apresente a copy completa e aplique o gate: peça aprovação explícita antes
   de qualquer página. Aprovada, sugira `/pagina`.

Siga `conhecimento/_regras-globais.md` em tudo que escrever.
