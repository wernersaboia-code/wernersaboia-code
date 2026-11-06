# Olá, eu sou o Werner 👋

[🇺🇸 English version](README.en.md)

**Desenvolvedor full-stack** (Next.js + Java/Spring) em Fortaleza, focado em segurança de aplicações,
infraestrutura e DevOps — de VPS na Hetzner a backups cifrados no Cloudflare R2 — e em produtos
que vão para produção de verdade. Na **Axyon**, toco 8 projetos da software house praticamente sozinho,
da arquitetura ao deploy. Também sou mentor técnico de devs em formação na **Code Plus** e presto
consultoria para a **Easy Prospect**.

> A maior parte do meu trabalho diário está em repositórios privados da Axyon. Abaixo estão o que eu fiz lá e os projetos públicos onde dá para ver o código.

---

## 🧭 Como eu trabalho

- **Segurança desde o início:** autenticação com sessão por cookie, OTP e rate limit; correção de IDOR e XSS; RLS no Postgres; controle de acesso por papéis com auditoria.
- **Do modelo de dados ao deploy:** APIs em Spring Boot e Next.js, migrations versionadas (Flyway, Prisma) e CI/CD com testes e smoke tests após o deploy.
- **Operação em produção:** VPS na Hetzner, deploy automático a partir da `main`, backups cifrados no Cloudflare R2 e monitoramento com Sentry.
- **Custo e controle:** troquei a Zoho (cerca de R$ 150 por mês) por um CRM próprio e levei a hospedagem de dois produtos de US$ 50 para US$ 7 por mês, com backup em tempo real e arquivos em buckets próprios.
- **Decisões documentadas:** cada mudança relevante tem uma spec explicando o *porquê*, não só o *como*.

---

## 🏢 Destaques na Axyon

**🏥 Torino HMS** · [demo](https://torino-hms.vercel.app): SaaS multi-tenant de gestão hospitalar e clínica, modular por pacotes.
Módulos de pacientes, agenda, prescrição, leitos e exames, engenharia clínica, farmácia, financeiro, convênios e billing do próprio SaaS, com isolamento por tenant via RLS e testes de RLS/RBAC.
`Next.js` `Supabase (RLS)` `Vercel`

**🍔 Food Delivery Suite**: plataforma de pedidos com carrinho, pagamentos, painel admin e assinaturas.
Fechei IDOR e XSS no fluxo de pagamento, corrigi o estorno em cobranças com valor divergente, montei o backup externo cifrado (R2) e a limpeza automática de disco na VPS, e reduzi o custo de hospedagem de US$ 50 para US$ 7 por mês.
`Java/Spring` `Next.js` `PostgreSQL` `Docker` `Hetzner`

**📚 Storyverse**: app de leitura com fórum, ranking, presentes e chat com IA.
Implementei auth com confirmação de e-mail, cota de IA controlada no servidor (com métricas e cache), moderação com papéis e auditoria, presença via SSE e sincronização offline→nuvem sem perda de dados.
`Spring Boot` `Next.js` `Supabase` `SSE` `Hetzner`

**📈 Orbit CRM** · [demo](https://orbit-crm-jade.vercel.app): CRM multi-tenant com portal do cliente e módulos de SEO e social media.
Bloqueei a auto-promoção a super-admin, fechei vazamentos no portal, coloquei RLS validada no CI com migrations automáticas (mais de 170 testes, entre unitários e de isolamento) e construí o módulo de auditoria SEO com Playwright.
`Next.js` `Supabase (RLS)` `Playwright` `CI/CD`

---

## 🤝 Além da Axyon

- **Easy Prospect** · [site](https://easyprospect.com.br): desde 2020, marketplace e CRM B2B voltados ao mercado europeu. Substituí a Zoho por um CRM próprio que hoje sustenta pipelines com cerca de 300 clientes.
- **Code Plus**: mentoria técnica de devs em formação e criação do portal do aluno, que centraliza material e videoaulas para o aluno aprender no próprio ritmo.

---

## 🔓 Projetos públicos

| Projeto | O que é | Destaques técnicos |
|---|---|---|
| [**Book Inventory**](https://github.com/wernersaboia-code/library-next) · [demo](https://library-next-taupe.vercel.app) | Catálogo de livros com leitor EPUB/PDF, importação do Calibre e uso offline | Busca full-text em PT, catálogo **OPDS** para apps de leitura, deduplicação por SHA-256/ISBN, RLS por usuário, testes Vitest + Playwright no CI |
| [**EasyProspect**](https://easyprospect.com.br) · [código](https://github.com/wernersaboia-code/agencycrm) | Marketplace e CRM B2B, em produção | Next.js + Prisma, i18n, Sentry, Vitest |
| [**Projeto Zero**](https://github.com/wernersaboia-code/projeto-zero) | Jogo de grande estratégia em grid hexagonal | Godot 4 / GDScript, porque eu também gosto de sistemas que não são CRUD 🎲 |

### 👥 Outros perfis

- **[@torinoorbit-dev](https://github.com/torinoorbit-dev)**: conta que uso para o trabalho na Axyon, com revisão de PRs e contribuições em múltiplos repositórios da software house.
- **[@wernersaboiacarvalho](https://github.com/wernersaboiacarvalho)**: projetos pessoais iniciais.

---

## 🛠️ Stack

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat&logo=spring&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat&logo=supabase&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat&logo=prisma&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat&logo=tailwindcss&logoColor=white)
![shadcn/ui](https://img.shields.io/badge/shadcn%2Fui-000000?style=flat&logo=shadcnui&logoColor=white)

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Hetzner](https://img.shields.io/badge/Hetzner-D50C2D?style=flat&logo=hetzner&logoColor=white)
![Cloudflare R2](https://img.shields.io/badge/Cloudflare_R2-F38020?style=flat&logo=cloudflare&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat&logo=vercel&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![Sentry](https://img.shields.io/badge/Sentry-362D59?style=flat&logo=sentry&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=flat&logo=vitest&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat&logo=playwright&logoColor=white)
![Godot](https://img.shields.io/badge/Godot-478CBF?style=flat&logo=godotengine&logoColor=white)

---

## 📊 Estatísticas

![Werner's GitHub stats](https://github-readme-stats-werner.vercel.app/api?username=wernersaboia-code&show_icons=true&hide_rank=false&count_private=true&private_contributions=true)
![Top Langs](https://github-readme-stats-werner.vercel.app/api/top-langs/?username=wernersaboia-code&layout=compact&theme=default)

> A maior parte do meu trabalho diário está em repositórios privados da Axyon — os números acima contam só parte da história.

---

## 📬 Contato

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/werner-saboia-carvalho-61a1143a1/)
[![E-mail](https://img.shields.io/badge/E--mail-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:wernersaboia@gmail.com)
[![EasyProspect](https://img.shields.io/badge/EasyProspect-easyprospect.com.br-0A66C2?style=flat&logo=googlechrome&logoColor=white)](https://easyprospect.com.br)
