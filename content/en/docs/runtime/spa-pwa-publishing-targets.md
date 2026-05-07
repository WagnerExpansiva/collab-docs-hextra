---
title: "SPA, PWA, and publishing targets"
description: "How runtime output is prepared for modern delivery"
weight: 8
translationKey: "runtime-spa-pwa-publishing-targets"
---

The Collab.codes runtime is designed for modern application delivery: SPA-ready, PWA-oriented, route-aware, and prepared for local or CDN-oriented targets.

The point is not to generate static pages. The point is to deliver a business application that can feel fast, modular, and operationally controlled.

## SPA-ready

Single-page applications reduce unnecessary navigation and keep the user in a continuous workflow.

For business systems, this matters because users often move between records, filters, approvals, tasks, and operational views during the same work session.

## PWA-oriented

PWA capabilities can improve installability, caching, offline tolerance, and perceived performance.

Not every client application needs every PWA feature. The runtime should make the path available when the product requires it.

## Lazy loading by route

Runtime delivery should avoid loading everything upfront.

Route-level loading helps a generated application remain usable as more modules, screens, and business areas are added.

## Publishing targets

The build and publication layer can prepare different delivery targets, including local execution and CDN-oriented distribution.

Runtime documentation explains what is being executed. Build documentation should later explain how publication is configured and operated.

## Related concepts

- [Runtime overview](/docs/runtime/overview/)
- [BFF](/docs/runtime/bff/)
- [I18n by page](/docs/creation/i18n-by-page/)
