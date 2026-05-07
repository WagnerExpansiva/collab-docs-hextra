---
title: "Collab Auth"
description: "Managed identity for the customer application and Collab.codes services"
weight: 2
translationKey: "platform-auth"
---

Collab Auth is the managed authentication and authorization service used across the customer application and Collab.codes services.

It exists because a modern business application is no longer a single isolated website. It may involve the runtime application, Studio, Collab Messages, billing, support, and external integrations.

## What it provides

Collab Auth can provide:

- users and groups;
- permissions and access rules;
- social login and SSO;
- shared identity across Collab.codes services;
- integration with the runtime application;
- integration with Studio and Collab Messages.

## Why managed identity matters

Identity becomes fragile when every module implements its own login and permission model.

Collab Auth gives the platform a common place to control access while preserving the ability to integrate with customer policies.

## Customer flexibility

Collab Auth is the managed default for Collab.codes.

The customer should still have a real exit path. If a customer leaves the ecosystem, identity can be moved to another authentication service or customer-controlled provider.

## Future integrations

Third-party enterprise identity providers, such as Okta or Auth0, should be treated as possible integrations as the product evolves.

## Related concepts

- [Collab Messages](/docs/collaboration/messages/)
- [Studio](/docs/creation/studio/)
- [No lock-in](/docs/platform/no-lock-in/)
