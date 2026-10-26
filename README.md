<img src="banner.jpg" alt="Hernán David Cardona Becerra – Full Stack Developer" width="100%"/>

# 👋 Hi, I'm Hernán David Cardona

### Full Stack Developer · React · Next.js · NestJS · TypeScript

![Open to Work](https://img.shields.io/badge/Status-Open%20to%20Work-brightgreen?style=for-the-badge)

🇨🇴 Based in Colombia · Open to **remote roles across the Americas** (EST/CST overlap) · Spanish (native) / English (professional)

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/hern%C3%A1n-david-cardona-becerra/)
[![Portfolio](https://img.shields.io/badge/-Portfolio-000000?style=for-the-badge&logo=react&logoColor=white)](https://portfolio-hernan-cardona.vercel.app/)
[![Email](https://img.shields.io/badge/-Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:hdcardonab@gmail.com)

---

## About

I build and ship production-ready web applications end to end: database, API, UI, tests, CI/CD and cloud deployment. My recent freelance work covers a multi-tenant SaaS on AWS Lambda, an e-commerce platform with Stripe payments, and a real-time POS used daily by a restaurant.

I also bring **5+ years of client-facing work in English** with US companies in KPI-driven nearshore teams, so I'm comfortable communicating clearly, owning deliverables and working with distributed teams. I use AI-assisted development (GitHub Copilot / Claude) to move faster without lowering quality.

### Results from shipped work

- **80+ daily transactions** at peak hours on a restaurant POS I built and deployed on DigitalOcean.
- Order relay time cut from **~3 minutes to under 15 seconds**, and order errors reduced by **~35%**.
- **0 failed transactions across 150+ simulated orders** with secure Stripe webhook handling.
- Deploy time cut from **~20 to under 4 minutes**, and manual deploy steps from ~8 to 0, with GitHub Actions CI/CD.
- **~100 automated tests** (Vitest + Playwright E2E) behind a multi-tenant SaaS with fully segregated data across 3 organizations.

---

## Selected work

### FlyWorkFlow — Multi-tenant incident-management SaaS
Geolocated incident management where several organizations share one deployment with fully isolated data (role-based guards + org-scoping). Serverless backend on AWS Lambda via SAM, S3 presigned uploads, JWT refresh-token rotation, and an 11-widget analytics dashboard on Mapbox GL. Dual CI/CD pipelines with GitHub Actions (Vercel frontend, ECR → SAM backend).

![Next.js](https://img.shields.io/badge/-Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white) ![NestJS](https://img.shields.io/badge/-NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white) ![Prisma](https://img.shields.io/badge/-Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![AWS Lambda](https://img.shields.io/badge/-AWS%20Lambda-232F3E?style=flat-square&logo=amazonaws&logoColor=white) ![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

[Repository](https://github.com/hervid2/flyworkflowapp) · [Live demo](https://flyworkflowapp.vercel.app)

### Slicing Edge — E-commerce for premium kitchen knives
Type-safe Turborepo monorepo sharing packages between a Next.js storefront and a Fastify REST API, with a PostgreSQL schema for products, orders, users and inventory. Stripe checkout with secure webhooks, JWT auth, parameterized queries against SQL injection and an admin CRUD panel. Three Dockerized services with automated CI/CD.

![Next.js](https://img.shields.io/badge/-Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white) ![Fastify](https://img.shields.io/badge/-Fastify-000000?style=flat-square&logo=fastify&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![Stripe](https://img.shields.io/badge/-Stripe-635BFF?style=flat-square&logo=stripe&logoColor=white) ![Turborepo](https://img.shields.io/badge/-Turborepo-EF4444?style=flat-square&logo=turborepo&logoColor=white) ![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

[Repository](https://github.com/hervid2/Slicing-edge-e-commerce) · [Live demo](https://slicing-edge-e-commerce-web.vercel.app/)

### Sushi Burrito POS (Web) — Restaurant management system
Migrated a Java desktop POS to a web SPA for a real restaurant: JWT auth with role-based access, real-time order tracking and a kitchen display via WebSockets, PDF invoices by email and an admin dashboard with statistics.

![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white) ![Express](https://img.shields.io/badge/-Express-000000?style=flat-square&logo=express&logoColor=white) ![MySQL](https://img.shields.io/badge/-MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) ![Vite](https://img.shields.io/badge/-Vite-646CFF?style=flat-square&logo=vite&logoColor=white) ![JavaScript](https://img.shields.io/badge/-Vanilla%20JS-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![DigitalOcean](https://img.shields.io/badge/-DigitalOcean-0080FF?style=flat-square&logo=digitalocean&logoColor=white)

[Repository](https://github.com/hervid2/sushiBurritoJS) · [Live demo](https://sushi-burrito-final.vercel.app/#login)

### Sushi Burrito POS (Desktop) — Layered Java application
Role-based desktop POS built on a layered, SOLID-oriented architecture (Swing → Service → Spring Data JPA → MySQL), 3NF schema, Flyway migrations and PDF invoices. Core logic tested with JUnit 5 and Mockito, and shipped as native installers (.msi / .dmg) with jpackage. Used daily for 6+ months before the web migration.

![Java](https://img.shields.io/badge/-Java-007396?style=flat-square&logo=openjdk&logoColor=white) ![Spring Boot](https://img.shields.io/badge/-Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white) ![MySQL](https://img.shields.io/badge/-MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) ![JUnit](https://img.shields.io/badge/-JUnit%205-25A162?style=flat-square&logo=junit5&logoColor=white)

[Repository](https://github.com/hervid2/sushiBurritoJava)

### Portfolio
Personal site with a React frontend, REST API and persistent database layer. [Live site](https://portfolio-hernan-cardona.vercel.app/) · [Repository](https://github.com/hervid2/Portfolio)

---

## Tech stack

**Frontend** &nbsp; ![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black) ![Next.js](https://img.shields.io/badge/-Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white) ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![Tailwind CSS](https://img.shields.io/badge/-Tailwind%20CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white) ![Vite](https://img.shields.io/badge/-Vite-646CFF?style=flat-square&logo=vite&logoColor=white)

**Backend** &nbsp; ![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white) ![NestJS](https://img.shields.io/badge/-NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white) ![Fastify](https://img.shields.io/badge/-Fastify-000000?style=flat-square&logo=fastify&logoColor=white) ![Express](https://img.shields.io/badge/-Express-000000?style=flat-square&logo=express&logoColor=white) ![Java](https://img.shields.io/badge/-Java-007396?style=flat-square&logo=openjdk&logoColor=white) ![Spring Boot](https://img.shields.io/badge/-Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)

**Databases & ORMs** &nbsp; ![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![MySQL](https://img.shields.io/badge/-MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) ![Prisma](https://img.shields.io/badge/-Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white) ![Sequelize](https://img.shields.io/badge/-Sequelize-52B0E7?style=flat-square&logo=sequelize&logoColor=white)

**Cloud & DevOps** &nbsp; ![AWS](https://img.shields.io/badge/-AWS%20(Lambda%2C%20S3%2C%20API%20Gateway)-232F3E?style=flat-square&logo=amazonaws&logoColor=white) ![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/-GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) ![Vercel](https://img.shields.io/badge/-Vercel-000000?style=flat-square&logo=vercel&logoColor=white) ![DigitalOcean](https://img.shields.io/badge/-DigitalOcean-0080FF?style=flat-square&logo=digitalocean&logoColor=white)

**Testing & tools** &nbsp; ![Vitest](https://img.shields.io/badge/-Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white) ![Playwright](https://img.shields.io/badge/-Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white) ![Jest](https://img.shields.io/badge/-Jest-C21325?style=flat-square&logo=jest&logoColor=white) ![Git](https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white) ![Postman](https://img.shields.io/badge/-Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)

**Integrations** &nbsp; ![Stripe](https://img.shields.io/badge/-Stripe-635BFF?style=flat-square&logo=stripe&logoColor=white) ![Mapbox](https://img.shields.io/badge/-Mapbox%20GL-000000?style=flat-square&logo=mapbox&logoColor=white)

Also familiar with: Python, WebSockets, JWT + RBAC, multi-tenancy, SOLID and clean/layered architecture.

---

## Ask me about

TypeScript · React / Next.js · Node.js / NestJS · multi-tenant SaaS architecture · REST API design · SOLID principles · spec-driven development · shipping with CI/CD

## Education

**Software Engineering** (in progress, 6th semester), Politécnico Grancolombiano · expected 2027
**Technologist in Software Analysis and Development (ADSO, Full Stack focus)**, SENA · 2023 – 2026

---

## Let's connect

I'm looking to join a development team where I can contribute from day one and keep growing. If you think I could be a fit, I'd love to talk.

[![LinkedIn](https://img.shields.io/badge/-Connect%20on%20LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/hern%C3%A1n-david-cardona-becerra/)
[![Email](https://img.shields.io/badge/-Send%20me%20an%20email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:hdcardonab@gmail.com)
[![Portfolio](https://img.shields.io/badge/-Visit%20my%20portfolio-000000?style=for-the-badge&logo=react&logoColor=white)](https://portfolio-hernan-cardona.vercel.app/)
