# Ben: consultor de expansão e gestão para escritórios de advocacia

Um agente do Claude Code que ajuda o titular de um escritório a organizar a operação e crescer com método: diagnóstico, planejamento anual, plano de ação com responsável e prazo, POPs, organograma, cultura, recrutamento e marketing jurídico dentro do Provimento 205/2021 da OAB.

Não dá parecer jurídico em caso de cliente. O campo dele é gestão, equipe, comercial e marketing.

## Como usar

1. Instale o [Claude Code](https://claude.com/claude-code).
2. Copie `.claude/agents/ben.md` para a pasta `.claude/agents/` do seu projeto (ou para `~/.claude/agents/` para usar em qualquer pasta).
3. No Claude Code, peça: `use o agente ben para fazer o diagnóstico do meu escritório`.
4. Responda às perguntas dele. Quanto mais fato (equipe, áreas, origem dos clientes, meta), melhor o plano.

Exemplos de pedido em [`exemplos/pedidos.md`](exemplos/pedidos.md).

## Dar contexto ao Ben

Crie na pasta do projeto um arquivo `CONTEXTO_ESCRITORIO.md` com o que for público dentro do escritório (áreas, equipe por função, rotinas, metas). O Ben usa o que estiver nos arquivos do projeto. Não coloque dado de cliente, senha, chave ou valor de honorário.

## Quer o Ben dentro do sistema do escritório?

Dá para rodar o mesmo texto como agente pessoal de uma pessoa da equipe (por exemplo, o titular ou o gestor), usando o conteúdo de `ben.md` como prompt do agente. Para o sistema de atendimento com agentes pessoais, veja o repositório [braga-braz-atendimento-agentes](https://github.com/pabadvogados-hub/braga-braz-atendimento-agentes) e cole o texto do Ben no campo "foco" e na orientação do agente.

## Aviso

O Ben apoia a decisão do titular. Metas, valores e contratações são do escritório. Confira normas e números antes de aplicar.
