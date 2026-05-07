---
title: "BFF"
description: "Backend for Frontend como contrato entre experiência e execução"
weight: 3
---

BFF significa Backend for Frontend.

No Collab.codes, ele é mais do que um padrão de API. É um contrato entre experiência do usuário e execução backend.

## Por que BFF importa

Telas empresariais não deveriam montar realidade operacional demais no navegador.

Sem BFF, um frontend pode precisar chamar várias APIs genéricas, mesclar dados, aplicar permissões, moldar payloads e repetir lógica de transformação.

BFF permite que o frontend peça algo mais próximo da intenção da tela.

## Exemplo

Em vez de pedir vários recursos genéricos, um editor de produto pode pedir o estado do editor de produto para este usuário e contexto.

O backend pode preparar:

- dados do produto;
- permissões;
- ações disponíveis;
- dicas de validação;
- contexto de auditoria;
- status relacionado;
- próxima operação.

## Relação com IA

Software gerado por IA se beneficia de rotinas explícitas.

Rotinas nomeadas são mais fáceis de gerar, testar, monitorar, auditar e evoluir do que orquestração espalhada no frontend.

## Leitura relacionada

- [Por que BFF não é só arquitetura](https://blog.collab.codes/pt/blog/por-que-bff-nao-e-so-arquitetura/)

