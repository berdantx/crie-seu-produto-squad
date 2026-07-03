---
description: Constrói a página de vendas HTML (etapa 8, o momento uau)
argument-hint: [opcional, preferências visuais]
---

O aluno quer construir ou reconstruir a página de vendas.

Preferências informadas: $ARGUMENTS

1. Verifique o insumo: `producao/06-copy.md`. Sem copy não há página.
   - Se não existir e o aluno tiver uma copy própria, peça para colar e salve
     em `producao/06-copy.md`.
   - Se não existir e ele não tiver, ofereça `/copy` primeiro.
2. Confirme que a copy foi aprovada pelo aluno (gate). Se ele nunca viu,
   mostre e peça o sim antes de seguir.
3. Colete as preferências visuais que faltarem, uma pergunta por vez: nome ou
   logo no topo, cor, foto e referência (todas têm saída para quem não tem).
4. Despache o agente `construtor-da-pagina` com as preferências no prompt.
5. Abra `producao/pagina.html` no navegador do aluno e celebre com peso, sem
   exclamação. Ofereça publicar com `npx vercel producao/`. Depois sugira
   `/anuncios` como bônus.

Siga `conhecimento/_regras-globais.md` em tudo que escrever.
