---
title: "Master config"
description: "How a client application chooses its runtime foundation"
weight: 3
translationKey: "runtime-master-config"
---

Master config is the composition layer that connects a client project to its runtime foundation.

It defines which master frontend, master backend, shared runtime modules, and application-specific modules participate in the client application.

## Why it matters

Collab.codes is opinionated, but it should not be rigid.

A customer can begin with a strong default foundation and still keep room to adapt the frontend, backend, modules, and operational boundaries when the product requires it.

## What master config controls

At a product level, master config can represent decisions such as:

- which frontend foundation the application uses;
- which backend foundation executes routines;
- which modules belong to the client application;
- which runtime capabilities are enabled;
- how the application composes shared and business-specific behavior.

## Reference example

In the current petshop reference, the client project uses Collab Aura as the master frontend and Collab Forge as the master backend.

Those are good defaults for the example. They are not meant to be the only possible choices.

## Customization principle

Customization should happen without losing the discipline of the platform.

The goal is to make the runtime flexible while keeping clear boundaries between client rules, common runtime, master frontend, and master backend.

## Related concepts

- [Architecture and composition](/docs/runtime/architecture-and-composition/)
- [Collab Aura](/docs/runtime/collab-aura/)
- [Collab Forge](/docs/runtime/collab-forge/)
- [No lock-in](/docs/platform/no-lock-in/)
