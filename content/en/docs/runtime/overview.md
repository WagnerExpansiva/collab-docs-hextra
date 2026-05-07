---
title: "Runtime overview"
description: "Runtime is where generated software becomes a running application"
weight: 1
---

Runtime is the Collab.codes dimension that executes the generated application.

It sits between Creation and Build. Creation defines what the application should become. Build and publishing prepare it for distribution. Runtime is where the application actually runs.

## What Runtime includes

Runtime includes:

- the client project;
- common runtime contracts;
- master configuration;
- master frontend;
- master backend;
- BFF routines;
- SPA/PWA behavior;
- authentication;
- auditability;
- monitoring;
- persistence;
- deployment targets.

## Reference composition

The current reference example uses:

- a client project, represented by the petshop example;
- a common runtime shared by generated applications;
- Collab Aura as the opinionated master frontend;
- Collab Forge as the opinionated master backend.

Aura and Forge are defaults for this example. The larger platform concept is that master configuration, master frontend, and master backend can be customized.

## Why Runtime matters

Generating a screen is not the same as running an application.

Runtime gives generated software the structure it needs to load, communicate, execute routines, record events, observe failures, and evolve.

Without runtime, the customer still has to assemble the product foundation manually.

## Related reading

- [Why BFF Is Not Just Architecture](https://blog.collab.codes/blog/why-bff-is-not-just-architecture/)
- [Why Generating Code Is Not Enough](https://blog.collab.codes/blog/why-generating-code-is-not-enough/)

