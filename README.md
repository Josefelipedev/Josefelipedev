# Hey there! 👋 I'm José Felipe

**Full-stack developer, back-end at heart.** I build and run SaaS products end to end: the API, the web app, the Android app, the AI workers and the server they all run on.

📍 Faro, Portugal · 🎓 BSc in Internet Systems (IFC, Brazil) · 📚 MSc in Informatics Engineering, Universidade do Algarve *(ongoing)* · 🔐 Next: Cybersecurity postgrad

---

### 🚀 What I'm building

**[TheChats.me](https://thechats.me)**: a multi-tenant customer-messaging and commerce platform
- NestJS API + React 19 dashboard + Python AI workers, talking over RabbitMQ and Redis
- WhatsApp / Meta APIs, a web chat widget, and AI agents with long-term memory and RAG over each company's knowledge base
- Marketplace connectors (eBay Inventory API, Vinted), a Sellbrite-style shared catalogue and multi-channel publishing
- Stripe billing with plans, per-resource quantities, currency-aware proration and usage limits enforced in the backend
- Docker on a VPS, front-ends on Cloudflare Workers, daily off-site backups

**FinPloit**: personal and couple finances, built around one question: *can you trust this number?*
- [`finance-front`](https://github.com/Josefelipedev/finance-front) (React 19 + Vite + Tailwind), `finploit-api` (NestJS + Prisma + PostgreSQL), [`finploit-android`](https://github.com/Josefelipedev/finploit-android) (Kotlin + Jetpack Compose)
- Multi-currency ledger converted at the rate of each transaction's date (ECB), with a shared space for couples who invite each other
- Recurring bills, debt payoff plans, 5-year projections with what-if scenarios, a meal planner that turns into a shopping list and expenses
- A nightly audit job with 48 data-integrity checks running in production

**[Mini Sentry](https://github.com/Josefelipedev/mini-sentry)**: self-hosted front-end error monitoring
- Browser SDK (errors, unhandled rejections, failed HTTP calls, breadcrumbs) → Fastify + Prisma API → Next.js 15 dashboard

**Other things I've built**
- 🧾 **payments-api**: one payments service for several products, each with its own Stripe account
- 🕷️ **multiscraper**: a Python scraping API for grocery prices and Portuguese university courses
- 🛴 An Android app that replaces the vendor app for my electric scooter over **Bluetooth LE**, and locks the scooter by itself when I walk away
- 🎬 A local-first AI media app: Whisper subtitles, video editing and local LLMs (Ollama), all on my own machine

**[Portfolio →](https://portfolio.josefelipedev.com)**

---

### 🛠️ Tech Stack

<div align="center">

**Back-end**<br>
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white)
![Fastify](https://img.shields.io/badge/Fastify-000000?style=for-the-badge&logo=fastify&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white)

**Data & messaging**<br>
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white)
![Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)

**Front-end & mobile**<br>
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)
![Jetpack Compose](https://img.shields.io/badge/Jetpack_Compose-4285F4?style=for-the-badge&logo=jetpackcompose&logoColor=white)

**AI**<br>
![LLM agents](https://img.shields.io/badge/LLM_agents_%26_RAG-D97757?style=for-the-badge&logo=claude&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white)
![Whisper](https://img.shields.io/badge/Whisper-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)

**Infra & integrations**<br>
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare_Workers-F38020?style=for-the-badge&logo=cloudflare&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Stripe](https://img.shields.io/badge/Stripe-635BFF?style=for-the-badge&logo=stripe&logoColor=white)
![Meta](https://img.shields.io/badge/Meta_%26_WhatsApp_APIs-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge&logo=testinglibrary&logoColor=white)

<sub>Also worked with: PHP / Laravel · Java · C# / .NET · Flutter / Dart · React Native</sub>

</div>

---

### 🧭 How I work

- **Correct numbers before new features.** Money, dates and time zones get tests, and production data gets audited.
- **I ship and I operate.** I deploy, monitor, back up and fix in production, not just open the pull request.
- **One product, every client.** The web app, the Android app and the API stay in sync.

---

### 📊 GitHub Stats

<div align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Josefelipedev&theme=dracula" />
</div>

<div align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=Josefelipedev&theme=dracula" height="150" />
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=Josefelipedev&theme=dracula" height="150" />
</div>

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=Josefelipedev&color=blueviolet&style=flat-square" />
</div>

---

### 📫 Connect with me

<div align="center">

[![Portfolio](https://img.shields.io/badge/-Portfolio-%23111?style=for-the-badge&logo=googlechrome&logoColor=white)](https://portfolio.josefelipedev.com)
[![LinkedIn](https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/josefelipealmeida/)
[![Gmail](https://img.shields.io/badge/-Gmail-%23333?style=for-the-badge&logo=gmail&logoColor=white)](mailto:josefelipedev@gmail.com)
[![Instagram](https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/josefelipealmeida/)

</div>
