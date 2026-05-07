---
title: "Conceptual architecture"
description: "A high-level view of how Collab.codes parts relate"
weight: 2
translationKey: "reference-architecture"
---

Collab.codes can be understood as a set of product layers around a generated business application.

```mermaid
flowchart TD
    A["Creation"] --> B["Runtime"]
    B --> C["Customer application"]
    D["Collaboration"] --> C
    E["Managed platform"] --> B
    E --> D
    A --> F["Studio"]
    F --> C
    B --> G["Collab Aura"]
    B --> H["Collab Forge"]
    E --> I["Collab Auth"]
    E --> J["Collab LLM"]
```

## How to read the diagram

Creation defines and evolves the application.

Runtime executes the generated application.

Collaboration keeps communication, tasks, agents, and contextual tools close to the business workflow.

Managed platform services provide identity, LLM access, cost control, and operational support.

## Product boundary

Studio, Build, and publication deserve dedicated documentation.

This reference page only shows how the major concepts relate.
