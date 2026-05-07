---
title: "Collab Auth"
description: "Identidade gerenciada para a aplicação cliente e serviços Collab.codes"
weight: 2
translationKey: "platform-auth"
---

Collab Auth é o serviço gerenciado de autenticação e autorização usado pela aplicação cliente e pelos serviços Collab.codes.

Ele existe porque uma aplicação empresarial moderna não é mais um site isolado. Ela pode envolver aplicação runtime, Studio, Collab Messages, billing, suporte e integrações externas.

## O que oferece

Collab Auth pode oferecer:

- usuários e grupos;
- permissões e regras de acesso;
- login social e SSO;
- identidade compartilhada entre serviços Collab.codes;
- integração com a aplicação runtime;
- integração com Studio e Collab Messages.

## Por que identidade gerenciada importa

Identidade fica frágil quando cada módulo implementa seu próprio login e modelo de permissão.

Collab Auth dá à plataforma um lugar comum para controlar acesso, preservando a capacidade de integração com políticas do cliente.

## Flexibilidade do cliente

Collab Auth é o padrão gerenciado do Collab.codes.

O cliente ainda deve ter um caminho real de saída. Se sair do ecossistema, a identidade pode ser movida para outro serviço de autenticação ou provedor controlado pelo cliente.

## Integrações futuras

Provedores empresariais de identidade de terceiros, como Okta ou Auth0, devem ser tratados como integrações possíveis conforme o produto evolui.

## Conceitos relacionados

- [Collab Messages](/pt/docs/colaboracao/messages/)
- [Studio](/pt/docs/criacao/studio/)
- [Sem lock-in](/pt/docs/plataforma/sem-lock-in/)
