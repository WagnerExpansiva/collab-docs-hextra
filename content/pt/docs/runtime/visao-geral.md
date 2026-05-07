---
title: "Visão geral do Runtime"
description: "Runtime é onde o software gerado vira uma aplicação em execução"
weight: 1
---

Runtime é a dimensão do Collab.codes que executa a aplicação gerada.

Ele fica entre Criação e Build. Criação define o que a aplicação deve se tornar. Build e publicação preparam a distribuição. Runtime é onde a aplicação realmente roda.

## O que o Runtime inclui

Runtime inclui:

- projeto client;
- contratos de runtime comum;
- master config;
- master frontend;
- master backend;
- rotinas BFF;
- comportamento SPA/PWA;
- autenticação;
- auditoria;
- monitoramento;
- persistência;
- targets de publicação.

## Composição de referência

O exemplo de referência atual usa:

- um projeto client, representado pelo exemplo petshop;
- um runtime comum compartilhado por aplicações geradas;
- Collab Aura como master frontend opinado;
- Collab Forge como master backend opinado.

Aura e Forge são padrões para este exemplo. O conceito maior da plataforma é que master config, master frontend e master backend podem ser customizados.

## Por que Runtime importa

Gerar uma tela não é o mesmo que executar uma aplicação.

Runtime dá ao software gerado a estrutura necessária para carregar, comunicar, executar rotinas, registrar eventos, observar falhas e evoluir.

Sem runtime, o cliente ainda precisa montar manualmente a fundação do produto.

## Leitura relacionada

- [Por que BFF não é só arquitetura](https://blog.collab.codes/pt/blog/por-que-bff-nao-e-so-arquitetura/)
- [Por que gerar código não basta](https://blog.collab.codes/pt/blog/por-que-gerar-codigo-nao-basta/)

