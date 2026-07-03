# Crie Seu Produto · Squad

Versão **Claude Code** do Assistente de Criação de Produto da Primia: um squad
de agentes que conduz você da pergunta "no que eu sou bom?" até uma **página de
vendas publicada**, com anúncios de bônus e projeção financeira no fechamento.

Guia completo, com a jornada e os dois modos de uso:
**[primia-como-usar.vercel.app](https://primia-como-usar.vercel.app)**

> Prefere usar no claude.ai, sem instalar nada? Use o pacote irmão:
> [crie-seu-produto-primia](https://github.com/berdantx/crie-seu-produto-primia)

## Como usar

1. Tenha o [Claude Code](https://claude.com/claude-code) instalado.
2. Clone este repositório e abra a pasta no terminal:

```bash
git clone https://github.com/berdantx/crie-seu-produto-squad.git
cd crie-seu-produto-squad
claude
```

3. Diga `oi`. O assistente assume e conduz, uma etapa por vez.

## O que tem dentro

| Pasta ou arquivo | O que é |
|---|---|
| `CLAUDE.md` | O condutor: conversa com você, aplica os gates, despacha o squad |
| `.claude/agents/` | 8 especialistas (pesquisa, ideias, oferta, copy, página, anúncios, VSL, projeção) |
| `.claude/commands/` | Atalhos de entrada direta: `/pesquisa`, `/ideias`, `/oferta`, `/copy`, `/pagina`, `/anuncios`, `/vsl`, `/projecao` |
| `conhecimento/` | Os manuais de cada etapa da jornada |
| `producao/` | Criada durante a sua jornada: cada entrega vira arquivo seu (não sobe pro git) |

## Entradas diretas

Não precisa refazer a jornada para mexer numa peça:

```
/pesquisa marmitas fit      só a pesquisa de mercado
/copy                       escreve ou ajusta a copy
/pagina                     constrói a página (aceita copy colada)
/anuncios mais 3 stories    variações de criativos
```

Cada comando verifica o que já existe em `producao/`, pergunta só o que faltar
e despacha o especialista certo.

## Se a conversa cair

Abra a pasta de novo e rode `claude`. A jornada está salva em `producao/`, o
assistente continua de onde parou.

---

Primia. Da ideia à página de vendas no ar, numa conversa só.
