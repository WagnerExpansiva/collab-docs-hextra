---
title: "Architecture and composition"
description: "How the runtime is composed from client, common runtime, master frontend, and master backend"
weight: 2
---

The Collab.codes runtime is composed from multiple projects and responsibilities.

This structure allows a client application to reuse a runtime foundation while keeping business-specific behavior in the right place.

## Main parts

The reference composition includes:

- a client project;
- a common runtime;
- a master frontend;
- a master backend;
- a master configuration connecting those pieces.

## Client project

The client project contains the application-specific module and business context.

In the current example, this is represented by the petshop application.

## Common runtime

The common runtime provides shared contracts, utilities, and runtime primitives that should remain neutral from customer business rules.

## Master frontend

The master frontend provides the opinionated frontend foundation.

In the reference example, this is Collab Aura.

## Master backend

The master backend provides the opinionated backend foundation.

In the reference example, this is Collab Forge.

## Customization principle

Aura and Forge are default choices, not mandatory choices.

The platform should allow master configuration, master frontend, and master backend to be customized when the customer needs a different foundation.

