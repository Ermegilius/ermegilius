# Hi, I'm Vladimir 👋

Full-stack engineer and co-founder of two Finnish startups, based in Espoo, Finland.

I build products end to end and run them in production: TypeScript across React/Next.js and NestJS, PostgreSQL, CI/CD and cloud deployment. AI tools are a big part of how I work, and I set up how a team works with them, so that AI-assisted work stays reviewable and verified, not just fast.

Before software, I spent 15 years in engineering and project management for nuclear power plant construction.

> _Master once, skip the hundred fixes._

---

## 🚀 What I'm building

### BLOMR · co-founder, lead developer

Multi-tenant SaaS platform for gyms, sports centres and activity organisers: a public site, a discovery and ventures flow, a member area and a role-based gym console.

- Lead developer: about 90% of the commits across the NestJS backend and the React web app.
- Tenant subscription billing on Stripe, from checkout to the billing page in the gym console.
- Authorisation moved to a tenant-scoped role model on the live production database, covered by 460 unit and 48 E2E tests.
- Secure real-time data ingestion (HMAC-signed webhooks, replay protection), analytics and member risk scoring.
- Production on UpCloud: PM2, Caddy, webhook deploys, deploy alerts, secrets in Infisical.

The repositories are private. 🌐 [Project overview](https://www.blomr.fi/about)

### Marbly · co-founder, Engineering & Architecture, AI Tooling

Two-sided marketplace for event services in Finland: people planning a wedding, a graduation or a birthday find and book caterers, photographers, venues and performers.

- Designed the system: Next.js web, NestJS API, Supabase Postgres with RLS as a backstop, a shared Zod contract package, Google Cloud Run.
- Set the technical standards and quality gates: Playwright E2E, Lighthouse checks, pre-push hooks.
- As the team's "AI Shepherd", wrote our AI policy and built the shared Claude Code setup every developer runs: MCP integrations, permission rules, review and planning agents.

The repositories are private. 🌐 [marbly.fi](https://marbly.fi)

---

## 🧰 Open source

| Project | What it is |
| --- | --- |
| [supaWake](https://github.com/Ermegilius/supaWake) · [live](https://supa-wake.netlify.app) | Keeps Supabase free-tier projects from auto-pausing, with zero setup inside the project. Week-long live tests showed that only Postgres writes count as activity, and the README documents the whole investigation. React, Vite, Netlify scheduled functions. |
| [yMusic playlist importer](https://github.com/Ermegilius/yMusic_playlist_importer) | Zero-dependency Python script that exports liked tracks and playlists from Yandex Music to CSV, built for a friend who wanted to leave the platform. |
| [Harakka](https://github.com/con2/harakka) · [demo](https://harakka.netlify.app/) | Multi-tenant storage and booking app, built in my internship team at Illusia ry: database, JWT role-based auth, NestJS APIs, React UI, Cypress tests, Azure deployment. |
| [Nest + Supabase + React template](https://github.com/Ermegilius/nest-supabase-react-tailwind-TEMPLATE) | Starter template for full-stack apps: NestJS, Supabase, React with TypeScript and Tailwind CSS. |

---

## 🛠️ Technologies & Tools

<!-- Core Stack -->

![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/-Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![NestJS](https://img.shields.io/badge/-NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![Express](https://img.shields.io/badge/-Express-000000?style=flat-square&logo=express&logoColor=white)
![Vite](https://img.shields.io/badge/-Vite-646cff?style=flat-square&logo=vite&logoColor=white)

<!-- Data -->

![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/-Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white)
![TypeORM](https://img.shields.io/badge/-TypeORM-000000?style=flat-square&logo=typeorm&logoColor=white)
![Zod](https://img.shields.io/badge/-Zod-3E67B1?style=flat-square&logo=zod&logoColor=white)

<!-- Frontend & UI -->

![Tailwind CSS](https://img.shields.io/badge/-Tailwind_CSS-06B6D4?style=flat-square&logo=tailwind-css&logoColor=white)
![Shadcn/UI](https://img.shields.io/badge/-Shadcn_UI-000000?style=flat-square&logo=shadcnui&logoColor=white)
![Redux](https://img.shields.io/badge/-Redux-764ABC?style=flat-square&logo=redux&logoColor=white)

<!-- Cloud & DevOps -->

![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/-GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)
![Google Cloud](https://img.shields.io/badge/-Google_Cloud-4285F4?style=flat-square&logo=google-cloud&logoColor=white)
![UpCloud](https://img.shields.io/badge/-UpCloud-7B00FF?style=flat-square)
![Azure](https://img.shields.io/badge/-Azure-0078D4?style=flat-square&logo=microsoft-azure&logoColor=white)
![AWS](https://img.shields.io/badge/-AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white)
![Stripe](https://img.shields.io/badge/-Stripe-635BFF?style=flat-square&logo=stripe&logoColor=white)

<!-- Testing -->

![Jest](https://img.shields.io/badge/-Jest-C21325?style=flat-square&logo=jest&logoColor=white)
![Vitest](https://img.shields.io/badge/-Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white)
![Playwright](https://img.shields.io/badge/-Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)
![Cypress](https://img.shields.io/badge/-Cypress-17202C?style=flat-square&logo=cypress&logoColor=white)

<!-- AI tooling -->

![Claude Code](https://img.shields.io/badge/-Claude_Code-D97757?style=flat-square&logo=claude&logoColor=white)
![MCP](https://img.shields.io/badge/-MCP-000000?style=flat-square)
![GitHub Copilot](https://img.shields.io/badge/-GitHub_Copilot-000000?style=flat-square&logo=githubcopilot&logoColor=white)

---

## 📫 Contact

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vladimir-beliakov/)
[![Discord](<https://img.shields.io/badge/-Discord(@ermegilius)-5865F2?style=for-the-badge&logo=discord&logoColor=white>)](https://discordapp.com/users/Ermegilius)

You will often find me at Helsinki tech meetups: HelsinkiJS, React Helsinki, Future Frontend.

![github-contribution-grid-snake.gif](https://raw.githubusercontent.com/Ermegilius/ermegilius/refs/heads/output/github-contribution-grid-snake-dark.svg?palette=github-dark)
