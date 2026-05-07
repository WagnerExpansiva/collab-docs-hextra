---
title: "BFF"
description: "Backend for Frontend as a contract between experience and execution"
weight: 3
---

BFF means Backend for Frontend.

In Collab.codes, it is more than an API pattern. It is a contract between user experience and backend execution.

## Why BFF matters

Business screens should not assemble too much operational reality in the browser.

Without BFF, a frontend may need to call multiple generic APIs, merge data, apply permissions, shape payloads, and repeat transformation logic.

BFF lets the frontend ask for something closer to the screen's intent.

## Example

Instead of asking for many generic resources, a product editor can ask for the product editor state for this user and context.

The backend can prepare:

- product data;
- permissions;
- available actions;
- validation hints;
- audit context;
- related status;
- next operation.

## Relationship with AI

AI-generated software benefits from explicit routines.

Named routines are easier to generate, test, monitor, audit, and evolve than scattered frontend orchestration.

## Related reading

- [Why BFF Is Not Just Architecture](https://blog.collab.codes/blog/why-bff-is-not-just-architecture/)

