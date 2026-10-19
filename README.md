<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=220&color=0:052E16,35:14532D,70:166534,100:22C55E&text=Hadi%20Afyouni&fontColor=ffffff&fontSize=48&fontAlignY=38&desc=Full-Stack%20Developer%20%7C%20Next.js%20%C2%B7%20Node.js%20%C2%B7%20TypeScript%20%C2%B7%20C%23%20%7C%20Applied%20ML&descAlignY=60" alt="Hadi Afyouni banner" />

# 👋 Hi, I'm Hadi Afyouni

### Full-Stack Developer | Real-Time & Transactional Systems | Applied Machine Learning

I design, build and ship complete products: from the database and API to the UI, payments and deployment.

Final-year **Computer Science** student at **City University, Lebanon** • Heading toward a **Master's in Artificial Intelligence & Data Science**

<p>
  <a href="https://github.com/hadiafyouni?tab=repositories"><img src="https://img.shields.io/badge/Explore_Projects-111827?style=for-the-badge&logo=github&logoColor=white" alt="Explore Projects" /></a>
  <a href="https://www.matchahorikku.com.au"><img src="https://img.shields.io/badge/Live_Client_Project-15803D?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Live client project" /></a>
</p>

</div>

---

## 🚀 About Me

I'm a full-stack developer who enjoys the hard parts of real systems: payments that can't double-charge, dispatchers that can't double-book, and checkouts that never leave a half-created order.

I work across **Next.js, Node.js, TypeScript, C# and Python**, and I've taken projects from idea to production, including a live e-commerce and catering platform for a client in Australia.

- 🛒 **Production work:** designed, built, deployed and maintain [matchahorikku.com.au](https://www.matchahorikku.com.au)
- 🚑 **Systems I like:** real-time, concurrent and location-aware applications
- 🔐 **Security by default:** httpOnly JWT cookies, 2FA, rate limiting, server-side validation
- 🤖 **Machine learning:** CNN-based speech recognition running live on a laptop CPU
- ♟️ **From scratch:** a chess engine with magic bitboards and alpha-beta search

---

## 💼 Experience

### Intern · Network & IoT Monitoring System
**Current**

Working on a monitoring system for network switches and IoT devices.

### Full-Stack Developer (Freelance) · Matcha Horikku
**2026 · Remote, client in Australia**

Delivered the entire platform end to end: UI/UX, Next.js frontend, Fastify API, PostgreSQL, PayPal payments, transactional emails, admin panel with TOTP two-factor authentication, and hosting on Railway with a custom domain.

---

## ✨ Featured Projects

### 🍵 Matcha Horikku
**E-commerce & catering platform for an Australian matcha brand · Live in production**

[![Live site](https://img.shields.io/badge/Visit_Live_Site-15803D?style=for-the-badge&logo=googlechrome&logoColor=white)](https://www.matchahorikku.com.au)
[![Showcase](https://img.shields.io/badge/View_Showcase-1D4ED8?style=for-the-badge&logo=github&logoColor=white)](https://github.com/hadiafyouni/MatchaHorikku)

Online shop, customer accounts, catering reservations and a full admin panel the business runs day to day.

**Engineering focus:**
- Prices, discounts and delivery fees computed on the server; every PayPal order verified before capture
- Stock reserved before payment, so a sold-out item is never charged
- Email verification, Google sign-in, TOTP 2FA for admins, revocable JWT sessions
- Next.js 15 · Fastify 5 · PostgreSQL · Cloudflare R2 · Resend · Vitest + GitHub Actions CI

---

### 🚑 Emergency Dispatch System
**Real-time ambulance and fire-unit dispatch platform for Lebanon**

[![View project](https://img.shields.io/badge/View_Project-1D4ED8?style=for-the-badge&logo=github&logoColor=white)](https://github.com/hadiafyouni/Rescue-center-manager)

Citizens report an emergency; the system classifies it, ranks the nearest units by **real road-network ETAs**, and assigns the best one, without ever double-booking a unit.

**Engineering focus:**
- `SELECT … FOR UPDATE SKIP LOCKED` so concurrent incidents never claim the same ambulance
- OSRM routing on OpenStreetMap data, with a graceful fallback if routing is down
- PostGIS nearest-unit search, explicit incident state machine, full audit trail
- Live dispatcher console over authenticated WebSockets with Redis pub/sub

---

### 🛍️ ShopX
**Full-stack electronics store: Go REST API, PostgreSQL and a Next.js storefront with an admin panel**

[![View project](https://img.shields.io/badge/View_Project-0F766E?style=for-the-badge&logo=github&logoColor=white)](https://github.com/hadiafyouni/ecommerceProject)

- Checkout commits order, items, stock reservation and payment in **one transaction**, with row locks against overselling
- Cookie-based JWT auth with scoped refresh tokens and silent refresh
- Plain SQL with `pgx`, no ORM; versioned migrations embedded in the binary
- Go 1.25 · chi · Next.js 16 · React 19 · Tailwind CSS 4 · Docker · CI

---

### ♟️ Chess Engine
**Chess engine written from scratch in C#, with a React UI and live analysis**

[![View project](https://img.shields.io/badge/View_Project-7C3AED?style=for-the-badge&logo=github&logoColor=white)](https://github.com/hadiafyouni/ChessEngine)

- Magic bitboards, Zobrist hashing, perft-verified move generation
- Iterative deepening, PVS, null-move pruning, late move reductions, quiescence search
- Tapered evaluation and an ~8.4M-entry transposition table
- ASP.NET Core API + SignalR streaming depth, score and principal variation to the UI

---

### 🎙️ Marvin: Voice Commands with a Wake Word
**Two CNNs that turn spoken words into actions, live on a laptop CPU**

[![View project](https://img.shields.io/badge/View_Project-DB2777?style=for-the-badge&logo=github&logoColor=white)](https://github.com/hadiafyouni/SpeechCommandCNN)

- Wake-word model for "marvin": **95.0%** test accuracy
- Command model (10 words + "unknown"): **89.2%** test accuracy on 10,413 held-out clips
- Log-mel spectrograms, SpecAugment, silence gating and debounced always-on listening
- A voice-controlled robot game to demo it · TensorFlow/Keras · Python

---

## 🧰 Tech Stack

### Languages & Frontend
<p>
  <img src="https://skillicons.dev/icons?i=ts,js,go,cs,py,react,nextjs,tailwind,vite,html&perline=5" alt="Languages and frontend tools" />
</p>

### Backend, Data & Tools
<p>
  <img src="https://skillicons.dev/icons?i=nodejs,dotnet,postgres,redis,docker,githubactions,tensorflow,sklearn,git,vscode&perline=5" alt="Backend, data and tooling" />
</p>

**Also work with:** Fastify · chi · pgx · ASP.NET Core · SignalR · PostGIS · OSRM · WebSockets · PayPal Orders API · Google OAuth · Resend · Cloudflare R2 · Railway · Vitest · xUnit

**Security & quality:** JWT in httpOnly cookies · bcrypt · TOTP 2FA · rate limiting · CSP and security headers · row-level locking · input validation (Zod) · CI on every push

**Areas I enjoy:** `Transactional systems` · `Real-time apps` · `Geospatial routing` · `REST APIs` · `Authentication` · `Game engines` · `Applied ML`

---

## 🎓 Education

- **BSc in Computer Science** · City University, Lebanon · *Final year*
- **Next:** Master's in Artificial Intelligence & Data Science

---

## 📊 GitHub Stats

<div align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=hadiafyouni&show_icons=true&hide_border=true&bg_color=0D1117&title_color=58A6FF&text_color=C9D1D9&icon_color=79C0FF&rank_icon=github" alt="GitHub stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=hadiafyouni&layout=compact&hide_border=true&bg_color=0D1117&title_color=58A6FF&text_color=C9D1D9" alt="Top languages" />
</div>

<div align="center">
  <img src="https://streak-stats.demolab.com?user=hadiafyouni&theme=github-dark-blue&hide_border=true" alt="GitHub streak" />
</div>

---

## 🐍 Contribution Snake

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/hadiafyouni/hadiafyouni/output/github-contribution-grid-snake-dark.svg" />
    <img src="https://raw.githubusercontent.com/hadiafyouni/hadiafyouni/output/github-contribution-grid-snake.svg" width="100%" alt="Animated snake eating contribution squares" />
  </picture>
</div>

<sub>Regenerated every day from my public contribution calendar.</sub>

---

## 🎯 Current Focus

- Interning on a monitoring system for network switches and IoT devices
- Preparing for a Master's in Artificial Intelligence & Data Science
- Maintaining and improving Matcha Horikku in production
- Taking the dispatch system further: live unit tracking and NLP-based incident classification
- Running speech models on small devices (TensorFlow Lite on a Raspberry Pi)
- Building reliable, secure full-stack products for real clients

---

## 📫 Connect With Me

<div align="center">

If you're working on **full-stack products, real-time systems or applied ML**, I'd be happy to connect.

<a href="https://github.com/hadiafyouni?tab=repositories"><strong>GitHub Repositories</strong></a> · <a href="https://www.matchahorikku.com.au"><strong>Live Project</strong></a>

</div>
