# Cauã

**Júnior fullstack TypeScript** · Brasil · aberto a oportunidades

Construo produto de ponta a ponta: interface em React/Next.js, API em Node, banco com Prisma e PostgreSQL, autenticação e pagamento. Procuro a primeira vaga como **desenvolvedor júnior fullstack** — o tipo de papel em que eu entrego feature, não só tela.

## Projeto em destaque

### [OdontoPRO](https://github.com/CauaFCamargo/odontoPRO) — SaaS de clínicas e agendamento

Plataforma para profissionais de saúde: o paciente encontra a clínica, escolhe serviço, data e horário; o profissional gerencia agenda, serviços, perfil e assinatura.

O que o código mostra na prática:

- Next.js 16 + TypeScript no App Router
- PostgreSQL + Prisma (agendamentos, serviços, lembretes, assinatura)
- Login com Google e GitHub (NextAuth)
- Stripe (planos Basic / Profissional, webhook, portal do cliente)
- Upload de foto com Cloudinary
- Regras de plano (limite de serviços, trial, relatórios)

[Abrir o app](https://odontopro-hazel.vercel.app) · [Ver o repositório](https://github.com/CauaFCamargo/odontoPRO)

## Também vale olhar

| Projeto | O que é | Stack |
| --- | --- | --- |
| [Val Salgados](https://github.com/CauaFCamargo/val-salgados-front) | Cardápio e pedidos de uma microempresa real — [site](https://val-salgados-front.vercel.app) | React, Vite, TypeScript |
| [val-salgados-api](https://github.com/CauaFCamargo/val-salgados-api) | API do mesmo produto: pedidos, JWT, token público anti-IDOR, testes | Express, Prisma, Zod, Vitest |
| [Júnior Ready](https://github.com/CauaFCamargo/prep) | Trilha + simulador de entrevista da stack que as vagas júnior pedem | Next.js, TypeScript |
| [API de entregas](https://github.com/CauaFCamargo/Api-sistema-de-entregas) | REST com papéis, JWT, Prisma e testes de integração | Express, Jest, Supertest |

## Stack que uso de verdade

Não é lista de curso. É o que aparece nos repositórios acima.

**Front:** TypeScript, React, Next.js, Tailwind, formulários com validação  
**Back:** Node.js, Express, REST, JWT, NextAuth (OAuth)  
**Dados:** PostgreSQL, Prisma, modelagem e migrations  
**Qualidade:** Zod, testes (Jest / Vitest / Supertest), TypeScript strict  
**Produto:** Stripe, Cloudinary, deploy na Vercel

Estou aprofundando o que as vagas júnior pedem além do que já entreguei: NestJS, testes com mais cobertura, SQL no dia a dia, e o básico de AWS / filas.

## Como eu trabalho

- Prefiro um projeto completo e explicável a dez tutoriais abandonados.
- README descreve o problema, a stack, como rodar e as decisões — não o template do `create-next-app`.
- Backend sem `eval` de input: schema (Zod), auth no middleware, e teste no caminho feliz e no erro.
- Quando o produto é de outra pessoa (Val Salgados), o código respeita o negócio: token de acompanhamento em vez de ID sequencial, impressão só quando a loja pede, PIX vs dinheiro.

## Contato

O jeito mais rápido é pelo GitHub: [@CauaFCamargo](https://github.com/CauaFCamargo).

Se você está recrutando para júnior fullstack TypeScript, comece pelo [OdontoPRO](https://odontopro-hazel.vercel.app) e pelo [código](https://github.com/CauaFCamargo/odontoPRO).
