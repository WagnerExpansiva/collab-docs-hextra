---
title: "Collab LLM"
description: "Proxy LLM gerenciado para custo, roteamento, observabilidade e flexibilidade de providers"
weight: 3
translationKey: "platform-llm"
---

Collab LLM é o proxy LLM gerenciado usado pelo Collab.codes para centralizar acesso a modelos, roteamento, monitoramento, billing, logs, cache, rate limits e controle de custo.

Ele permite que aplicações e agentes peçam uma capacidade em vez de codificar a escolha de provider em cada workflow.

## Aliases de capacidade

Agentes podem solicitar aliases como `code`, `fast` ou outra capacidade definida pelo produto.

O Collab LLM pode então decidir qual modelo encaixa melhor para aquela tarefa naquele momento, considerando qualidade, custo, disponibilidade do provider e política operacional.

## Flexibilidade de providers

Collab LLM pode rotear para providers como OpenAI, Anthropic, Grok, Azure e OpenRouter.

O conjunto exato de providers habilitados pode evoluir ao longo do tempo sem forçar cada aplicação a ser reescrita.

## Por que centralizar uso de LLM

A centralização ajuda com:

- monitoramento de uso;
- atribuição de custo;
- billing;
- rate limits;
- cache;
- logs;
- avaliação de qualidade;
- roteamento entre providers.

## Posição sem lock-in

Collab LLM usa um padrão de endpoint compatível com OpenAI.

Um cliente pode configurar outro endpoint compatível se sair do ecossistema Collab.codes. A maioria dos clientes pode preferir o serviço gerenciado porque ele entrega observabilidade, roteamento e otimização de custo.

## Conceitos relacionados

- [Custos centralizados](/pt/docs/plataforma/custos-centralizados/)
- [Sem lock-in](/pt/docs/plataforma/sem-lock-in/)
- [Tasks e workflows](/pt/docs/colaboracao/tasks-workflows/)
