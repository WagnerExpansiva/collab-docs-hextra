---
title: "SPA, PWA e targets de publicação"
description: "Como o output do runtime é preparado para entrega moderna"
weight: 8
translationKey: "runtime-spa-pwa-publishing-targets"
---

O runtime do Collab.codes é desenhado para entrega moderna de aplicações: pronto para SPA, orientado a PWA, consciente de rotas e preparado para targets locais ou orientados a CDN.

O objetivo não é gerar páginas estáticas. O objetivo é entregar uma aplicação empresarial que possa ser rápida, modular e operacionalmente controlada.

## SPA-ready

Aplicações single-page reduzem navegação desnecessária e mantêm o usuário em um fluxo contínuo.

Para sistemas empresariais, isso importa porque usuários normalmente alternam entre registros, filtros, aprovações, tarefas e visões operacionais durante a mesma sessão de trabalho.

## PWA-oriented

Capacidades de PWA podem melhorar instalabilidade, cache, tolerância offline e percepção de performance.

Nem toda aplicação cliente precisa de todos os recursos de PWA. O runtime deve deixar esse caminho disponível quando o produto exigir.

## Lazy loading por rota

A entrega do runtime deve evitar carregar tudo logo no início.

Carregamento por rota ajuda uma aplicação gerada a continuar utilizável conforme mais módulos, telas e áreas de negócio são adicionados.

## Targets de publicação

A camada de build e publicação pode preparar diferentes targets de entrega, incluindo execução local e distribuição orientada a CDN.

A documentação de runtime explica o que está sendo executado. A documentação de Build deve explicar depois como a publicação é configurada e operada.

## Conceitos relacionados

- [Visão geral do Runtime](/pt/docs/runtime/visao-geral/)
- [BFF](/pt/docs/runtime/bff/)
- [I18n por página](/pt/docs/criacao/i18n-por-pagina/)
