<div align="center">

# Jabir Mahmud
### Full-Stack Software Engineer · AI Systems · Production-Grade SaaS

[![Portfolio](https://img.shields.io/badge/Portfolio-jabirr.vercel.app-black?style=flat-square&logo=vercel)](https://jabirr.vercel.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-jabirmahmud0-0A66C2?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/jabirmahmud0/)
[![Email](https://img.shields.io/badge/Email-jaabirmahmud01@gmail.com-EA4335?style=flat-square&logo=gmail)](mailto:jaabirmahmud01@gmail.com)
[![Location](https://img.shields.io/badge/Dhaka,_Bangladesh-GMT+6-lightgrey?style=flat-square&logo=googlemaps)](https://maps.google.com/?q=Dhaka,Bangladesh)

</div>

---

Full-Stack Software Engineer building scalable, production-grade web applications and AI-driven platforms. Experienced in architecting type-safe systems with **React**, **Next.js**, **TypeScript**, **PostgreSQL**, and **Express** — with a strong focus on secure authentication flows, real-time collaboration, subscription billing, and clean maintainable architecture.

---

## 🛠 Tech Stack

| Layer | Technologies |
| :--- | :--- |
| **Frontend** | React, Next.js 15, TypeScript, Redux Toolkit, TanStack Query, Tailwind CSS, Framer Motion |
| **Backend** | Node.js, Express.js, tRPC, PostgreSQL, MongoDB, Drizzle ORM |
| **Real-time** | Socket.io, Redis Pub/Sub, BullMQ |
| **AI & NLP** | Google Gemini API, OpenAI API, PDF.js |
| **Auth & Payments** | NextAuth v5, JWT, Google OAuth, Firebase, Stripe (Checkout + Subscriptions + Webhooks) |
| **DevOps** | Git, GitHub Actions CI/CD, Vercel, Render, Turborepo, Docker |
| **Testing** | Jest, React Testing Library, Vitest, Playwright E2E |

---

## 🚀 Projects

### 🔷 FlowDesk — B2B SaaS Project Management Platform *(In Development, 2026)*

> Linear-style Kanban + Notion-style docs in a production multi-tenant SaaS platform.

**Tech Stack:** Next.js 15 · tRPC · PostgreSQL · Socket.io · Stripe Subscriptions · Redis · Turborepo

- Architecting a **multi-tenant SaaS platform** with `org_id` row-level isolation across 16 PostgreSQL tables — workspace-scoped RBAC (Owner / Admin / Member / Viewer) enforced at every tRPC procedure
- Building **real-time collaboration** with Socket.io + Redis Pub/Sub: live Kanban updates (`task:created`, `task:moved`), presence indicators ("Alex and 2 others are here"), and in-app notification push
- Implementing **Stripe Subscription billing** (Free / Pro $12 / Team $29) with Checkout Sessions, Customer Portal, webhook signature verification, and server-side plan limit enforcement via tRPC middleware
- Integrating **Tiptap v2 rich text editor** with `/slash` commands, `@mention` support, auto-save, and Cloudinary image uploads — powering both task descriptions and Notion-style workspace documents
- Wiring **BullMQ + Resend** for async email jobs (invite tokens, daily digest notifications) and a full-text search system using PostgreSQL `tsvector` with a `Cmd+K` command palette

---

### 🔷 TechVault — Premium Electronics E-Commerce Platform

[Live](https://gotechvault.vercel.app)

**Tech Stack:** Next.js 15 · TypeScript · Express.js · PostgreSQL · Stripe · Turborepo

- Architected production e-commerce platform with **Next.js 15 App Router**, Express.js, and PostgreSQL via Drizzle ORM — implementing JWT refresh token rotation (15min access / 7d refresh), Firebase Auth, and RBAC across buyer, seller, and admin roles
- Built seller and admin dashboards with **real-time order tracking**, product CRUD with Cloudinary, sales analytics, and a fully type-safe catalog using TanStack Query + Zod — with search, filters, wishlists, reviews, and **optimistic UI reducing perceived latency by 60%**
- Deployed on **Vercel + Render + Neon** with GitHub Actions CI/CD — achieving Lighthouse 94, <2.5s first load, and zero payment failures in production

---

### 🔷 CareerByAI — AI-Powered Career Platform

[Frontend](https://github.com/Jabirmahmud0/AI_career_Client) · [Backend](https://github.com/Jabirmahmud0/AI_career_Server)

**Tech Stack:** React · Node.js · Express · MongoDB · Google Gemini AI · PDF.js

- Built an AI-driven career platform with **Gemini AI** for personalized roadmap generation, job matching, and CV parsing — automated skill extraction via PDF/TXT file analysis
- Integrated a chatbot-style guidance interface with a custom job-fit scoring algorithm based on skill/experience alignment and curated learning resource recommendations

---

### 🔷 CureBay — Healthcare E-Commerce Platform

[Live](https://curebayy.vercel.app) · [Frontend](https://github.com/Jabirmahmud0/CureBay_Client) · [Backend](https://github.com/Jabirmahmud0/CureBay_Backend)

**Tech Stack:** React · Node.js · Firebase · Stripe · Tailwind CSS

- Engineered a full healthcare e-commerce system with secure Stripe payments, order lifecycle management, and an advanced medicine catalog with multi-parameter filtering
- Designed role-specific dashboards for inventory management, order tracking, and user administration (Patient / Doctor / Admin)

---

## 📊 GitHub Stats

<div align="center">

![GitHub Stats](https://github-readme-stats-bfef.vercel.app/api?username=jabirmahmud0&show_icons=true&theme=github_dark&include_all_commits=true&count_private=true&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=c9d1d9&icon_color=58a6ff)

![GitHub Streak](https://streak-stats.demolab.com/?user=jabirmahmud0&theme=github-dark-blue&hide_border=true&background=0d1117&ring=58a6ff&fire=ff6b6b&currStreakLabel=58a6ff)

![Top Languages](https://github-readme-stats-bfef.vercel.app/api/top-langs/?username=jabirmahmud0&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=c9d1d9&langs_count=8)

![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=jabirmahmud0&theme=github-compact&bg_color=0d1117&color=58a6ff&line=58a6ff&point=ffffff&hide_border=true)



</div>

---

## 🎓 Education

**B.Sc. in Computer Science and Engineering** — Daffodil International University  
*Graduated December 2025*

---

## 🤝 Open To

Freelance contracts · Full-stack MERN development · AI integration & intelligent systems · Technical consulting · Code reviews & architecture assessments

---

<div align="center">

*Building production systems — one intelligent architecture at a time.*

</div>
