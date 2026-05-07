---
title: "Arquitetura e composição"
description: "Como o runtime é composto por client, common runtime, master frontend e master backend"
weight: 2
---

O runtime do Collab.codes é composto por múltiplos projetos e responsabilidades.

Essa estrutura permite que uma aplicação cliente reutilize uma fundação de runtime mantendo comportamento específico de negócio no lugar correto.

## Partes principais

A composição de referência inclui:

- projeto client;
- common runtime;
- master frontend;
- master backend;
- master config conectando essas peças.

## Projeto client

O projeto client contém o módulo específico da aplicação e o contexto de negócio.

No exemplo atual, isso é representado pela aplicação petshop.

## Common runtime

O common runtime fornece contratos, utilitários e primitivas compartilhadas que devem permanecer neutras em relação às regras de negócio do cliente.

## Master frontend

O master frontend fornece a fundação frontend opinada.

No exemplo de referência, isso é o Collab Aura.

## Master backend

O master backend fornece a fundação backend opinada.

No exemplo de referência, isso é o Collab Forge.

## Princípio de customização

Aura e Forge são escolhas padrão, não obrigatórias.

A plataforma deve permitir que master config, master frontend e master backend sejam customizados quando o cliente precisar de outra fundação.

