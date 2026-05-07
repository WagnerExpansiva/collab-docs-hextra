---
title: "Collab LLM"
description: "A managed LLM proxy for cost, routing, observability, and provider flexibility"
weight: 3
translationKey: "platform-llm"
---

Collab LLM is the managed LLM proxy used by Collab.codes to centralize model access, routing, monitoring, billing, logs, cache, rate limits, and cost control.

It lets applications and agents ask for a capability instead of hardcoding a provider choice into every workflow.

## Capability aliases

Agents can request aliases such as `code`, `fast`, or another product-defined capability.

Collab LLM can then decide which model is the best fit for that task at that moment, considering quality, cost, provider availability, and operational policy.

## Provider flexibility

Collab LLM can route to providers such as OpenAI, Anthropic, Grok, Azure, and OpenRouter.

The exact set of enabled providers can evolve over time without forcing every application to be rewritten.

## Why centralize LLM usage

Centralization helps with:

- usage monitoring;
- cost attribution;
- billing;
- rate limits;
- caching;
- logs;
- quality evaluation;
- provider routing.

## No lock-in position

Collab LLM uses an OpenAI-compatible endpoint pattern.

A customer can configure a different compatible endpoint if leaving the Collab.codes ecosystem. Most customers may prefer the managed service because it provides observability, routing, and cost optimization.

## Related concepts

- [Centralized costs](/docs/platform/centralized-costs/)
- [No lock-in](/docs/platform/no-lock-in/)
- [Tasks and workflows](/docs/collaboration/tasks-workflows/)
