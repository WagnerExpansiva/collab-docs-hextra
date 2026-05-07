---
title: "Runtime tradeoffs"
description: "What the architecture optimizes for, and what it asks from the team"
weight: 10
translationKey: "runtime-tradeoffs"
---

The Collab.codes runtime is designed to make business application delivery faster, more reusable, and easier to govern.

That architecture has tradeoffs. They should be explicit.

## What the runtime optimizes for

The runtime favors:

- faster creation of client applications;
- reuse of frontend and backend foundations;
- clear separation between platform and business rules;
- SPA and PWA-oriented delivery;
- BFF-oriented execution;
- route-level loading;
- customization without losing technical opinion.

## What it asks from the team

The model requires discipline.

Teams need to understand where a concern belongs: client project, common runtime, master frontend, master backend, platform service, or publication process.

## Main tradeoffs

Expect these costs:

- more configuration discipline;
- multiple projects and pinned dependencies;
- a higher initial learning curve;
- stronger boundaries between client logic and shared foundations;
- clearer ownership of product decisions.

## Good fit

The runtime is a good fit when the customer expects to create and evolve more than one business application, reuse patterns, keep governance visible, and avoid rebuilding the same foundation repeatedly.

## Poor fit

It is a weaker fit for one-off prototypes where the application will not evolve, will not need governance, and will not benefit from reusable runtime foundations.

## Related concepts

- [Master config](/docs/runtime/master-config/)
- [Architecture and composition](/docs/runtime/architecture-and-composition/)
- [No lock-in](/docs/platform/no-lock-in/)
