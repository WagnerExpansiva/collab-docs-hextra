---
title: "Master config"
description: "Como uma aplicação cliente escolhe sua base de runtime"
weight: 3
translationKey: "runtime-master-config"
---

Master config é a camada de composição que conecta um projeto cliente à sua base de runtime.

Ela define quais master frontend, master backend, módulos de runtime comum e módulos específicos da aplicação participam da aplicação cliente.

## Por que isso importa

Collab.codes é opinado, mas não deve ser rígido.

Um cliente pode começar com uma base padrão forte e ainda manter espaço para adaptar frontend, backend, módulos e fronteiras operacionais quando o produto exigir.

## O que o master config controla

No nível de produto, o master config pode representar decisões como:

- qual base frontend a aplicação usa;
- qual base backend executa rotinas;
- quais módulos pertencem à aplicação cliente;
- quais capacidades de runtime estão habilitadas;
- como a aplicação compõe comportamento compartilhado e regra específica de negócio.

## Exemplo de referência

No exemplo atual do petshop, o projeto cliente usa Collab Aura como master frontend e Collab Forge como master backend.

Essas são boas escolhas padrão para o exemplo. Elas não devem ser apresentadas como as únicas escolhas possíveis.

## Princípio de customização

Customização deve acontecer sem perder a disciplina da plataforma.

O objetivo é tornar o runtime flexível mantendo fronteiras claras entre regra do cliente, common runtime, master frontend e master backend.

## Conceitos relacionados

- [Arquitetura e composição](/pt/docs/runtime/arquitetura-e-composicao/)
- [Collab Aura](/pt/docs/runtime/collab-aura/)
- [Collab Forge](/pt/docs/runtime/collab-forge/)
- [Sem lock-in](/pt/docs/plataforma/sem-lock-in/)
