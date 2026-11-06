# Hi, I'm Werner 👋

[🇧🇷 Versão em português](README.md)

**Full-stack developer** (Next.js + Java/Spring) based in Fortaleza, Brazil, focused on application security,
infrastructure and DevOps — from Hetzner VPS hosting to encrypted backups on Cloudflare R2 — and on products
that actually ship to production. At **Axyon**, I run 8 of the software house's projects almost single-handedly,
from architecture to deployment. I'm also a technical mentor for developers in training at **Code Plus** and
I consult for **Easy Prospect**.

> Most of my day-to-day work lives in Axyon's private repositories. Below you'll find what I did there, plus the public projects where you can read the code.

---

## 🧭 How I work

- **Security from the start:** cookie-based session auth, OTP and rate limiting; IDOR and XSS fixes; Postgres RLS; role-based access control with audit trails.
- **From data model to deployment:** APIs in Spring Boot and Next.js, versioned migrations (Flyway, Prisma) and CI/CD with tests and post-deploy smoke tests.
- **Running in production:** Hetzner VPS, automatic deploys from `main`, encrypted backups on Cloudflare R2 and monitoring with Sentry.
- **Cost and control:** I replaced Zoho (about R$ 150 per month) with an in-house CRM and cut the hosting bill for two products from US$ 50 to US$ 7 per month, with real-time backup and files in self-managed buckets.
- **Documented decisions:** every relevant change has a spec explaining the *why*, not just the *how*.

---

## 🏢 Highlights at Axyon

**🏥 Torino HMS** · [demo](https://torino-hms.vercel.app): multi-tenant SaaS for hospital and clinic management, modular by package.
Modules for patients, scheduling, prescriptions, beds and exams, clinical engineering, pharmacy, finance, insurance plans and billing for the SaaS itself, with per-tenant isolation through RLS and RLS/RBAC tests.
`Next.js` `Supabase (RLS)` `Vercel`

**🍔 Food Delivery Suite**: ordering platform with cart, payments, admin panel and subscriptions.
I closed IDOR and XSS issues in the payment flow, fixed refunds on charges with mismatched amounts, built the encrypted off-site backup (R2) and automatic disk cleanup on the VPS, and cut hosting costs from US$ 50 to US$ 7 per month.
`Java/Spring` `Next.js` `PostgreSQL` `Docker` `Hetzner`

**📚 Storyverse**: reading app with forum, rankings, gifts and an AI chat.
I implemented email-confirmed auth, server-controlled AI quotas (with metrics and caching), role-based moderation with audit trails, presence over SSE and offline-to-cloud sync with no data loss.
`Spring Boot` `Next.js` `Supabase` `SSE` `Hetzner`

**📈 Orbit CRM** · [demo](https://orbit-crm-jade.vercel.app): multi-tenant CRM with a client portal and SEO and social media modules.
I blocked self-promotion to super-admin, closed leaks in the portal, set up RLS validated in CI with automatic migrations (over 170 tests, unit and isolation) and built the SEO audit module with Playwright.
`Next.js` `Supabase (RLS)` `Playwright` `CI/CD`

---

## 🤝 Beyond Axyon

- **Easy Prospect** · [site](https://easyprospect.com.br): since 2020, a B2B marketplace and CRM aimed at the European market. I replaced Zoho with an in-house CRM that now runs pipelines with about 300 clients.
- **Code Plus**: technical mentoring for developers in training, and creator of the student portal, which centralizes course material and video lessons so students can learn at their own pace.

---

## 🔓 Public projects

| Project | What it is | Technical highlights |
|---|---|---|
| [**Book Inventory**](https://github.com/wernersaboia-code/library-next) · [demo](https://library-next-taupe.vercel.app) | Book catalog with an EPUB/PDF reader, Calibre import and offline use | Portuguese full-text search, **OPDS** catalog for reading apps, SHA-256/ISBN deduplication, per-user RLS, Vitest + Playwright tests in CI |
| [**EasyProspect**](https://easyprospect.com.br) · [code](https://github.com/wernersaboia-code/agencycrm) | B2B marketplace and CRM, in production | Next.js + Prisma, i18n, Sentry, Vitest |
| [**Projeto Zero**](https://github.com/wernersaboia-code/projeto-zero) | Hex-grid grand strategy game | Godot 4 / GDScript, because I also enjoy systems that aren't CRUD 🎲 |

### 👥 Other profiles

- **[@torinoorbit-dev](https://github.com/torinoorbit-dev)**: the account I use for Axyon work, with PR reviews and contributions across the software house's repositories.
- **[@wernersaboiacarvalho](https://github.com/wernersaboiacarvalho)**: my early personal projects.

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

## 📊 Stats

![Werner's GitHub stats](https://github-readme-stats-werner.vercel.app/api?username=wernersaboia-code&show_icons=true&hide_rank=false&count_private=true&private_contributions=true)
![Top Langs](https://github-readme-stats-werner.vercel.app/api/top-langs/?username=wernersaboia-code&layout=compact&theme=default)

> Most of my day-to-day work lives in Axyon's private repositories — the numbers above only tell part of the story.

---

## 📬 Contact

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/werner-saboia-carvalho-61a1143a1/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:wernersaboia@gmail.com)
[![EasyProspect](https://img.shields.io/badge/EasyProspect-easyprospect.com.br-0A66C2?style=flat&logo=googlechrome&logoColor=white)](https://easyprospect.com.br)
