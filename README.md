# Campaign OS — Assistente de Planejamento de Campanhas com IA

> Sistema de planejamento assistido por IA criado por **Lucas Oliveira Soares de Freitas** para o contexto da **Agência Escala Pro**.

## Visão geral

O Campaign OS transforma um objetivo de marketing em um plano executável, uma rotina semanal, um mapa de obstáculos e ciclos de revisão. A proposta combina um Planner no Notion com habilidades reutilizáveis para reduzir a distância entre intenção e execução.

O projeto foi desenvolvido como entrega final de curso e também como uma peça de portfólio profissional. O caso demonstrativo utiliza dados fictícios e não expõe informações pessoais ou confidenciais.

## Caso demonstrativo

**Objetivo:** estruturar uma campanha de 30 dias para gerar 20 leads qualificados para uma consultoria de marketing digital, utilizando conteúdo orgânico, página de captura e acompanhamento semanal.

## O problema que o projeto resolve

Planejamentos tradicionais costumam produzir listas estáticas de tarefas. O Campaign OS acrescenta contexto operacional: cada ação está vinculada a um objetivo, possui critério de conclusão, considera obstáculos e é revisada com base no que realmente aconteceu.

## Diferencial

O sistema não tenta substituir a decisão humana. Ele organiza o raciocínio, explicita premissas e sugere próximos passos verificáveis. Assim, o planejamento permanece útil quando surgem atrasos, restrições de tempo ou mudanças no cenário.

## Componentes

- **Planner no Notion:** objetivos, plano de ação, obstáculos e revisões relacionadas.
- **Seis habilidades reutilizáveis:** da clarificação do objetivo ao planejamento da próxima semana.
- **Documentação:** método, estrutura de dados, instruções e limitações.
- **Demonstração:** exemplo completo com objetivo, ações, riscos e revisão semanal.

## Estrutura do repositório

```text
├── README.md
├── docs/
│   ├── metodologia.md
│   ├── estrutura-do-planner.md
│   ├── habilidades.md
│   ├── demonstracao.md
│   └── limitacoes-e-evolucoes.md
├── prompts/
│   ├── 01-clarificar-objetivo.md
│   ├── 02-construir-plano-de-acao.md
│   ├── 03-adaptar-a-rotina.md
│   ├── 04-mapear-obstaculos.md
│   ├── 05-revisar-progresso.md
│   └── 06-planejar-proxima-semana.md
└── examples/
    ├── objetivo-de-exemplo.md
    ├── plano-de-acao-exemplo.md
    └── revisao-semanal-exemplo.md
```

## Como reproduzir

1. Crie uma página no Notion para o Campaign OS.
2. Configure as quatro bases descritas em [`docs/estrutura-do-planner.md`](docs/estrutura-do-planner.md).
3. Cadastre o objetivo de exemplo.
4. Use as habilidades na ordem indicada em [`docs/habilidades.md`](docs/habilidades.md).
5. Compare as respostas da IA com a realidade da operação antes de aceitar qualquer sugestão.
6. Faça uma revisão semanal e registre a decisão para o próximo ciclo.

## Tecnologias e ferramentas

- Notion — Planner e bases relacionadas;
- IA generativa — execução das habilidades de planejamento;
- Markdown — documentação e versionamento;
- GitHub — publicação e apresentação do projeto.

## Autor

**Lucas Oliveira Soares de Freitas**  
Projeto: **Agência Escala Pro**  
Data da entrega: **24/11/2026**

## Nota de transparência

Os dados do caso demonstrativo são fictícios, conforme orientação do desafio. O projeto não contém chaves, tokens, credenciais ou informações confidenciais.

## Templates para o Notion

A pasta [`notion/`](notion/) contém quatro arquivos CSV prontos para importação como bases iniciais no Notion, além de instruções para criar as relações entre elas.
