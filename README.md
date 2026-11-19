# Consultor de expansão e gestão para escritórios de advocacia

Um agente do Claude Code que ajuda o titular de um escritório a organizar a operação e crescer com método: diagnóstico, planejamento anual, plano de ação com responsável e prazo, POPs, organograma, cultura, recrutamento e marketing jurídico dentro do Provimento 205/2021 da OAB.

Não dá parecer jurídico em caso de cliente. O campo dele é gestão, equipe, comercial e marketing.

## Como usar

1. Instale o [Claude Code](https://claude.com/claude-code).
2. Copie `.claude/agents/consultor-expansao.md` para a pasta `.claude/agents/` do seu projeto (ou para `~/.claude/agents/` para usar em qualquer pasta).
3. No Claude Code, peça: `use o agente consultor-expansao para fazer o diagnóstico do meu escritório`.
4. Responda às perguntas dele. Quanto mais fato (equipe, áreas, origem dos clientes, meta), melhor o plano.

Exemplos de pedido em [`exemplos/pedidos.md`](exemplos/pedidos.md).

## Dar contexto ao agente

Crie na pasta do projeto um arquivo `CONTEXTO_ESCRITORIO.md` com o que for público dentro do escritório (áreas, equipe por função, rotinas, metas). Ele usa o que estiver nos arquivos do projeto. Não coloque dado de cliente, senha, chave ou valor de honorário.

## Dentro do sistema do escritório

O agente não tem nome próprio: cada sistema dá o nome que quiser. Dá para usar o texto de `consultor-expansao.md` como orientação do agente pessoal de alguém da equipe, no sistema de [atendimento com agentes pessoais](https://github.com/pabadvogados-hub/braga-braz-atendimento-agentes).

## Aviso

O agente apoia a decisão do titular. Metas, valores e contratações são do escritório. Confira normas e números antes de aplicar.
