# Olá, eu sou o Werner 👋

**Desenvolvedor backend & full-stack** focado em sistemas seguros, observáveis e bem arquitetados.
Trabalho com projetos autorais e com uma software house (Axyon), tratando cada linha de código
com o rigor de ambiente corporativo — segurança, testes, CI/CD, infraestrutura e documentação.

> 🔐 Segurança · 📊 Observabilidade · ⚙️ Backend Java/Spring & Next.js · 🖥️ DevOps em VPS

---

## 🚀 O que eu construo

Atuo no ciclo completo de produtos web — da modelagem de dados ao deploy em produção — com ênfase em:

- **Segurança aplicada**: hardening de autenticação (sessão por cookie, OTP, rate limit),
  mitigação de IDOR/XSS, headers, auditoria e controle de acesso por papéis.
- **Backend robusto**: APIs em **Java + Spring Boot**, com Flyway, cache, cotas e integração com IA.
- **Front-end moderno**: aplicações em **Next.js / React / TypeScript**.
- **Observabilidade e operação**: Sentry (API e front), backups cifrados no Cloudflare R2,
  limpeza automatizada de disco, smoke tests pós-deploy.
- **DevOps na prática**: provisionamento e operação de **VPS (Hetzner)**, deploy automatizado
  via CI/CD, volumes de mídia, persistência de estado e recuperação de desastres com backup externo.
- **CI/CD**: pipelines com cache, retry de Playwright, migrations automáticas e preview/produção.

---

## 🧪 Projetos em destaque

### 🍔 Food Delivery Suite — plataforma de pedidos (multi-repo)
- **O que é:** suíte de delivery com carrinho, pagamentos, painel admin e assinaturas.
- **Meu papel:** hardening de segurança (auth, sessão, OTP, headers, dependências),
  correções de concorrência em pagamentos, observabilidade com Sentry e **operação em VPS**.
- **Stack:** Java/Spring, Node, PostgreSQL, Docker, **Next.js**, **Hetzner (VPS)**, **Cloudflare R2**.
- **Desafios:** eliminar IDOR e XSS em fluxo de pagamento; garantir estorno correto em cobranças
  com valor divergente; **backup externo cifrado no Cloudflare R2** e limpeza automática de disco
  na VPS a cada 2 dias.

### 📚 Storyverse — leitura + comunidade + IA (web / api)
- **O que é:** app de leitura com fórum, ranking, presentes (diamantes) e chat com IA.
- **Meu papel:** auth com confirmação de e-mail e recuperação de senha; cota de IA no servidor;
  endpoints de fórum e moderação; SSE de presença; pacotes de créditos; **deploy automatizado em VPS
  a partir da main**.
- **Stack:** Spring Boot, TypeScript/React, **Next.js**, Supabase, SSE, **Hetzner (VPS)**.
- **Desafios:** sincronização offline→nuvem sem perda de dados; cota de IA server-side com métricas
  e cache; moderação com papéis e auditoria; **persistência do SHA da API no .env da VPS** e
  volume de mídia dedicado.

### 📈 Orbit CRM — CRM com portal e auditoria SEO
- **O que é:** CRM multi-tenant com portal do cliente e módulos de SEO/social media.
- **Meu papel:** hardening crítico (impedir auto-promoção a super-admin), RLS no CI,
  rate limit no login, módulo de auditoria SEO com Playwright.
- **Stack:** **Next.js**, PostgreSQL, Supabase (RLS), Playwright, CI/CD.
- **Desafios:** fechar vazamentos do portal e hardening P1; RLS no CI com migrations automáticas.

---

## 🛠️ Tecnologias e ferramentas

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat&logo=spring&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Hetzner](https://img.shields.io/badge/Hetzner-D50C2D?style=flat&logo=hetzner&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat&logo=cloudflare&logoColor=white)
![Sentry](https://img.shields.io/badge/Sentry-362D59?style=flat&logo=sentry&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white)

**Práticas:** Conventional Commits · code review · hardening de segurança · RLS ·
observabilidade · backups cifrados · deploy em VPS · smoke tests pós-deploy.

## 🖥️ Infraestrutura que eu opero

- **VPS Hetzner**: provisionamento, deploy automatizado a partir da `main`, volumes de mídia e persistência de estado.
- **Cloudflare R2**: backups externos cifrados, com rotina de limpeza automatizada.
- **Observabilidade**: Sentry na API e no front, com smoke tests pós-deploy no pipeline.

---

## 📊 Estatísticas

![Werner's GitHub stats](https://github-readme-stats.vercel.app/api?username=wernersaboia-code&show_icons=true&theme=default&hide=issues)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=wernersaboia-code&layout=compact)

> Boa parte do meu trabalho está em repositórios privados da software house —
> por isso as contribuições acima não contam a história toda. 🙂

---

## 📬 Conecte-se comigo

- 💼 LinkedIn: [werner-saboia-carvalho](https://www.linkedin.com/in/werner-saboia-carvalho-61a1143a1/)
- 📧 E-mail: wernersaboiacarvalho@gmail.com
