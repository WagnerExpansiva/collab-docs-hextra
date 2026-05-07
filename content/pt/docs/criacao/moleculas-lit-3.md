---
title: "Moléculas Lit 3"
description: "Contratos de componentes reutilizáveis para telas de negócio"
weight: 5
translationKey: "creation-molecules-lit-3"
---

Moléculas são componentes frontend reutilizáveis usados pelo Collab Aura para manter telas de negócio adaptáveis sem reescrever a página sempre que a interface muda.

A ideia não é apenas reaproveitamento visual. Uma molécula representa um contrato: que tipo de valor ela recebe, como se comporta e o que a página pode esperar dela.

## Por que isso importa

Aplicações empresariais precisam de variação.

O mesmo campo de negócio pode ser exibido como dropdown, grupo de rádio, nuvem de tags, seletor em popup ou outro padrão de interação. Se a página depende de um contrato estável de componente, a interface pode evoluir sem quebrar a intenção de negócio.

## Como pensar em moléculas

Use moléculas para separar:

- o significado de negócio de um campo;
- o padrão de interação usado pelo usuário;
- a implementação visual;
- o contrato da página;
- a preferência do cliente.

## Exemplo conceitual

Um seletor de preferência de pets pode manter a mesma finalidade de negócio enquanto muda sua apresentação.

Um cliente pode preferir um dropdown compacto. Outro pode preferir seleção por tags. A página não deveria precisar ser reescrita apenas porque o padrão de interação mudou.

## Relação com o Studio

O Studio pode usar os contratos das moléculas para ajudar usuários e agentes de IA a sugerirem mudanças no nível correto.

Em vez de reescrever uma página inteira, uma mudança pode mirar o componente que representa a interação de negócio.

## Conceitos relacionados

- [Collab Aura](/pt/docs/runtime/collab-aura/)
- [Page Genome](/pt/docs/criacao/page-genome/)
- [Studio](/pt/docs/criacao/studio/)
