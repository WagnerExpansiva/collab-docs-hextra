---
title: "Tradeoffs do Runtime"
description: "O que a arquitetura otimiza e o que ela exige do time"
weight: 10
translationKey: "runtime-tradeoffs"
---

O runtime do Collab.codes é desenhado para tornar a entrega de aplicações empresariais mais rápida, mais reutilizável e mais fácil de governar.

Essa arquitetura tem tradeoffs. Eles devem ser explícitos.

## O que o runtime otimiza

O runtime favorece:

- criação mais rápida de aplicações cliente;
- reaproveitamento de fundações frontend e backend;
- separação clara entre plataforma e regra de negócio;
- entrega orientada a SPA e PWA;
- execução orientada a BFF;
- carregamento por rota;
- customização sem perder opinião técnica.

## O que ele exige do time

O modelo exige disciplina.

Times precisam entender onde cada preocupação pertence: projeto cliente, common runtime, master frontend, master backend, serviço de plataforma ou processo de publicação.

## Principais tradeoffs

Espere estes custos:

- mais disciplina de configuração;
- múltiplos projetos e dependências pinadas;
- curva inicial maior;
- fronteiras mais fortes entre lógica do cliente e fundações compartilhadas;
- ownership mais claro das decisões de produto.

## Bom encaixe

O runtime encaixa bem quando o cliente espera criar e evoluir mais de uma aplicação empresarial, reaproveitar padrões, manter governança visível e evitar reconstruir a mesma fundação repetidamente.

## Mau encaixe

Ele encaixa pior em protótipos pontuais nos quais a aplicação não vai evoluir, não precisa de governança e não se beneficia de fundações reutilizáveis de runtime.

## Conceitos relacionados

- [Master config](/pt/docs/runtime/master-config/)
- [Arquitetura e composição](/pt/docs/runtime/arquitetura-e-composicao/)
- [Sem lock-in](/pt/docs/plataforma/sem-lock-in/)
