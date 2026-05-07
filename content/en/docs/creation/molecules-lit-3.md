---
title: "Lit 3 molecules"
description: "Reusable component contracts for business screens"
weight: 5
translationKey: "creation-molecules-lit-3"
---

Molecules are reusable frontend components used by Collab Aura to keep business screens adaptable without rewriting the page every time the interface changes.

The idea is not only visual reuse. A molecule represents a contract: what kind of value it receives, how it behaves, and what the page can expect from it.

## Why it matters

Business applications need variation.

The same business field can be rendered as a dropdown, radio group, tag cloud, popup selector, or another interaction pattern. If the page depends on a stable component contract, the interface can evolve without breaking the business intent.

## How to think about molecules

Use molecules to separate:

- the business meaning of a field;
- the interaction pattern used by the user;
- the visual implementation;
- the page contract;
- the customer preference.

## Example concept

A pet preference selector can keep the same business purpose while changing its presentation.

One customer may prefer a compact dropdown. Another may prefer a tag-based selector. The page should not need to be rewritten just because the interaction pattern changes.

## Relationship with Studio

Studio can use molecule contracts to help users and AI agents suggest interface changes at the right level.

Instead of rewriting a full page, a change can target the component that represents the business interaction.

## Related concepts

- [Collab Aura](/docs/runtime/collab-aura/)
- [Page Genome](/docs/creation/page-genome/)
- [Studio](/docs/creation/studio/)
