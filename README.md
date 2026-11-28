<!-- ═══════════════════════════ HEADER ═══════════════════════════ -->
<div align="center">
    
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,50:6366f1,100:14b8a6&height=200&section=header&text=Pranjal%20Kuhikar&fontSize=52&fontColor=ffffff&fontAlignY=36&desc=Frontend%20Engineer%20%C2%B7%20React%20%C2%B7%20TypeScript%20%C2%B7%20Micro-Frontends%20%C2%B7%20Playwright&descSize=17&descAlignY=58" width="100%" alt="Pranjal Kuhikar banner" />
  
<a href="https://github.com/pranjalkuhikar">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=3200&pause=900&color=14B8A6&center=true&vCenter=true&width=760&lines=Frontend+Engineer+%7C+React+%26+TypeScript;300%2B+Playwright+E2E+tests+wired+into+CI;Micro-frontends+%E2%86%92+API+gateway+%E2%86%92+production;Bengaluru+%E2%80%A2+immediate+joiner" alt="Typing intro" />
</a>
   
<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/pranjal-kuhikar/)
[![X](https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/KuhikarPranjal)
[![Portfolio](https://img.shields.io/badge/Portfolio-pranjalkuhikar.com-FF7A00?style=for-the-badge&logo=firefox&logoColor=white)](https://pranjalkuhikar.com)
[![Profile Views](https://komarev.com/ghpvc/?username=pranjalkuhikar&label=Profile+Views&color=6366f1&style=for-the-badge)](https://github.com/pranjalkuhikar)

</div>

<br/>

<!-- ═══════════════════════════ INTENT ═══════════════════════════ -->
## 🎯 What I'm looking for

**Frontend / React Engineer** role on a product or platform team in **Bengaluru** — React, TypeScript, micro-frontends, web performance and frontend quality. Open to full-stack roles where React is the main surface, and to roles where the Playwright/CI work is a real part of the job.

📍 Bengaluru, India · 🕐 IST (UTC+5:30) · ✅ **Immediate joiner** · on-site / hybrid · 📫 [kuhikarpranjal@gmail.com](mailto:kuhikarpranjal@gmail.com)

<!-- ═══════════════════════════ ABOUT ═══════════════════════════ -->
## 👋 About Me

<table>
<tr>
<td width="60%" valign="top">

I'm a **frontend-focused full-stack engineer** who takes products from idea to production.

- 💻 **2 yr 4 mo professional** experience (+1 yr internship) shipping **React + TypeScript** apps
- 🧩 Own the frontend architecture of a live US ed-tech platform: **micro-frontends**, shared auth/session, API gateway to a .NET microservices backend
- 🧪 Built **300+ Playwright E2E tests** wired into the client's **CI pipeline** for automatic regression checks
- 🖥️ Delivered an **80+ screen** operations platform replacing **3 separate tools**; owned Nginx, PM2, SSL and zero-downtime deploys
- 🤝 Mentor **2 junior developers**; introduced the team's Git branching and PR review process
- 🤖 Side projects in **GenAI/RAG** with LangChain, Pinecone and Gemini

</td>
<td width="40%" valign="top">

```text
const pranjal = {
  role: "Frontend Engineer",
  location: "Bengaluru, India",
  availability: "Immediate joiner",
  experience: "2 yr 4 mo + 1 yr internship",
  core: ["React", "TypeScript", "Micro-frontends"],
  quality: ["Playwright", "CI regression", "Core Web Vitals"],
  fullStack: ["Node.js", "MongoDB", "PostgreSQL"],
  sideProjects: ["RAG", "LangChain", "Pinecone", "Gemini"],
};
```

</td>
</tr>
</table>

<!-- ═══════════════════════════ START HERE ═══════════════════════════ -->
## 🔎 Start here

Three minutes, four files — if you'd rather read code than READMEs:

| File | What it shows |
|:--|:--|
| [`transition.controller.js`](https://github.com/pranjalkuhikar/NeuroBank/blob/main/transition/src/controllers/transition.controller.js) | Idempotent transfers: key pre-check, status replay, unique index |
| [`rabbit.js`](https://github.com/pranjalkuhikar/SonicFlow/blob/main/Auth/src/broker/rabbit.js) · [`listener.js`](https://github.com/pranjalkuhikar/SonicFlow/blob/main/Notification/src/broker/listener.js) | One event crossing two services over CloudAMQP |
| [`rag.js`](https://github.com/pranjalkuhikar/DocuChat/blob/main/server/src/utils/rag.js) | The whole RAG pipeline: load → split → embed → upsert → retrieve → answer |
| [`guard.js`](https://github.com/pranjalkuhikar/load-tester/blob/main/lib/guard.js) | Loopback-only request guard, so a load tester can't become a DDoS tool |

Each project ends with a **⚠️ Known limitations** section — what it doesn't do is written down, not left for you to discover.

<!-- ═══════════════════════════ PROJECTS ═══════════════════════════ -->
## 🚀 Featured Projects

<table>
<tr>
<td width="33%" valign="top">

### 🎵 SonicFlow
**Distributed music streaming backend**

- 4 independent Node.js microservices: Auth, Music, Notification, Client
- Async service communication via **CloudAMQP** message queues
- Dual-role auth (Artists / Users) with **JWT + RBAC**
- **Multer → ImageKit** upload pipeline for audio and artwork

<sub>`Node.js` `Express` `MongoDB` `CloudAMQP` `JWT` `Multer` `ImageKit`</sub>

<sub>▶ Run locally — 4 services + MongoDB + CloudAMQP · [known limitations](https://github.com/pranjalkuhikar/SonicFlow#known-limitations)</sub>

<br/><br/>

[![Repo](https://img.shields.io/badge/View_on_GitHub-181717?style=for-the-badge&logo=github)](https://github.com/pranjalkuhikar/SonicFlow)

</td>
<td width="33%" valign="top">

### 🏦 NeuroBank
**Digital banking platform**

- Full-stack banking simulation with **5 backend microservices**
- **CloudAMQP** pub/sub for decoupled service communication
- **React Native** (Expo) mobile app for core banking flows
- Server-side **idempotency checks** to prevent duplicate transactions

<sub>`MERN` `React Native` `Microservices` `CloudAMQP` `JWT`</sub>

<sub>▶ Run locally — 5 services + MongoDB + CloudAMQP · [known limitations](https://github.com/pranjalkuhikar/NeuroBank#known-limitations)</sub>

<br/><br/>

[![Repo](https://img.shields.io/badge/View_on_GitHub-181717?style=for-the-badge&logo=github)](https://github.com/pranjalkuhikar/NeuroBank)

</td>
<td width="33%" valign="top">

### 🤖 DocuChat
**RAG-based AI knowledge assistant**

- Chatbot that answers questions from uploaded PDFs using **RAG**
- Full pipeline: ingestion → chunking → embeddings → semantic retrieval → response
- **Pinecone** vector database stores and retrieves relevant chunks

<sub>`Next.js` `Node.js` `LangChain` `Gemini API` `Pinecone`</sub>

<sub>[![CI](https://github.com/pranjalkuhikar/DocuChat/actions/workflows/ci.yml/badge.svg)](https://github.com/pranjalkuhikar/DocuChat/actions/workflows/ci.yml) · [known limitations](https://github.com/pranjalkuhikar/DocuChat#known-limitations)</sub>

<br/><br/>

[![Repo](https://img.shields.io/badge/View_on_GitHub-181717?style=for-the-badge&logo=github)](https://github.com/pranjalkuhikar/DocuChat)

</td>
</tr>
</table>

### 🧩 More Projects

| Project | What it is | Stack | Links |
|:--|:--|:--|:--|
| ⚡ **LoadLab** | Self-hosted load tester: auto-detects local endpoints, live percentile charts, **371 unit tests in CI** | Next.js · Node · custom load engine | [Code](https://github.com/pranjalkuhikar/load-tester) |
| 📊 **Test Dashboard** | Paste a repo, get test coverage by layer with per-test drill-down and history | Next.js · Postgres · Playwright | [Code](https://github.com/pranjalkuhikar/Test-Dashboard) |
| 🔐 **Todo Platform** | Four apps behind one SSO hub, with Prometheus + Grafana + Loki wired in | Next.js · Postgres · Docker · Microservices | [Code](https://github.com/pranjalkuhikar/Todo-Platform) |
| 🎬 **CineVerse** | Movie search & browse app powered by TMDB | Next.js · Tailwind · TMDB | [Live](https://movie-app-nine-khaki.vercel.app/) · [Code](https://github.com/pranjalkuhikar/CineVerse) |
| 😊 **Beat Sync** | AI mood & music app: webcam face detection picks your music | React · face-api · Deezer API | [Live](https://beatsync-plum.vercel.app/) · [Code](https://github.com/pranjalkuhikar/VibeBeats) |
| 📹 **Aora** | Social video-sharing mobile app | React Native · Appwrite · Tailwind | [Code](https://github.com/pranjalkuhikar/Aora) |
| 🏠 **Airbnb clone** | Listings app with auth, uploads and maps | Node · Express · MongoDB · Passport · Cloudinary | [Live](https://airbnb-run1.onrender.com/listings) <sub>(free tier — first load ~20s)</sub> · [Code](https://github.com/pranjalkuhikar/Airbnb) |
| ✍️ **Blog** | CMS-driven blog with light/dark mode | Next.js · Sanity · TypeScript · Shadcn | [Live](https://blog-zeta-wheat-68.vercel.app/) · [Code](https://github.com/pranjalkuhikar/blog) |
| 🛒 **E-Commerce** | Storefront on a headless CMS | Next.js · Sanity | [Live](https://e-commerce-eosin-seven-90.vercel.app/) · [Code](https://github.com/pranjalkuhikar/E_Commerce) |
| 🎨 **LogoLumina** | Logo creation website | React · Vite · html2canvas | [Live](https://logo-lumina.vercel.app/) · [Code](https://github.com/pranjalkuhikar/LogoLumina) |

> 💡 More on **[pranjalkuhikar.com/projects](https://pranjalkuhikar.com/projects)**.

<!-- ═══════════════════════════ EXPERIENCE ═══════════════════════════ -->
## 💼 Experience Highlights

<details open>
<summary><b>🧑‍💻 Full Stack Developer, Pi Labs (Priyam Innovations Pvt. Ltd.)</b> &nbsp;·&nbsp; Bengaluru &nbsp;·&nbsp; Jul 2024 – Present</summary>

<br/>

**US ed-tech client (live product, real users)**
- 🧩 Own the **frontend architecture**: React + TypeScript **micro-frontends**, shared authentication and session handling, cross-module routing and UI consistency
- 🔌 Integrate the MFE shell with a **.NET microservices backend** via an API gateway — request routing, payload handling and error propagation
- ⚡ Improved page-load performance with route-level **code splitting and lazy loading** at MFE boundaries
- 👥 Delivered full-stack features (React, TypeScript, Node.js) for a new user-facing product in a **15-member team**

**QA / test automation client**
- 🧪 Built **300+ Playwright E2E tests** covering critical user journeys of a live production app
- 🔁 Wired suites into the client's **CI pipeline** so every change triggers regression checks before release
- 📋 Own test planning, structured defect reporting (repro steps, severity, logs) and fix verification

**Internal platforms & leadership**
- 🖥️ Delivered an **80+ screen** operations platform (React, TypeScript, Node.js, MongoDB) consolidating **3 separate tools**
- ⚙️ Owned production infrastructure: Nginx reverse proxy, PM2 clustering, SSL and zero-downtime deploys on Ubuntu VPS
- 📱 Shared **30%** of core business logic between web and React Native clients (Expo, NativeWind)
- 🌿 Introduced Git branching and PR review processes; mentor **2 junior developers**

</details>

<details>
<summary><b>🎓 Software Developer Intern, IXOLabs Pvt. Ltd.</b> &nbsp;·&nbsp; Remote &nbsp;·&nbsp; Jul 2023 – Jul 2024</summary>

<br/>

- 🌐 Delivered **6 client-facing web projects** end-to-end: requirements gathering, custom implementation and production deployment
- 🔍 Built SEO-friendly page structures, metadata and performance-conscious layouts
- 🤝 Worked with cross-functional teams on scope and delivery timelines; took part in code reviews

</details>

<details open>
<summary><b>🤖 Side projects — GenAI & LLM applications</b></summary>

<br/>

- 🔗 Built **RAG pipelines** with LangChain, Pinecone vector databases and the Gemini API
- 📄 Implemented PDF ingestion, semantic chunking, embedding generation, retrieval and cited, page-grounded answers

</details>

<!-- ═══════════════════════════ TECH ═══════════════════════════ -->
## 💻 Tech Stack

<div align="center">

| | |
|:--|:--|
| **🎨 Frontend** | ![React](https://img.shields.io/badge/React-20232a?style=flat-square&logo=react&logoColor=61DAFB) ![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white) ![Micro-frontends](https://img.shields.io/badge/Micro--frontends-83BD75?style=flat-square&logo=webpack&logoColor=white) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white) ![Redux Toolkit](https://img.shields.io/badge/Redux_Toolkit-593d88?style=flat-square&logo=redux&logoColor=white) ![RTK Query](https://img.shields.io/badge/RTK_Query-593d88?style=flat-square&logo=redux&logoColor=white) ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat-square&logo=tailwindcss&logoColor=white) ![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white) ![Core Web Vitals](https://img.shields.io/badge/Core_Web_Vitals-4285F4?style=flat-square&logo=googlechrome&logoColor=white) |
| **📱 Mobile** | ![React Native](https://img.shields.io/badge/React_Native-20232a?style=flat-square&logo=react&logoColor=61DAFB) ![Expo](https://img.shields.io/badge/Expo-1C1E24?style=flat-square&logo=expo&logoColor=white) ![NativeWind](https://img.shields.io/badge/NativeWind-38B2AC?style=flat-square&logo=tailwindcss&logoColor=white) |
| **⚙️ Backend** | ![Node.js](https://img.shields.io/badge/Node.js-6DA55F?style=flat-square&logo=nodedotjs&logoColor=white) ![Express](https://img.shields.io/badge/Express-404d59?style=flat-square&logo=express&logoColor=61DAFB) ![Microservices](https://img.shields.io/badge/Microservices-326CE5?style=flat-square&logo=kubernetes&logoColor=white) ![REST APIs](https://img.shields.io/badge/REST_APIs-009688?style=flat-square&logo=fastapi&logoColor=white) ![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white) ![RBAC](https://img.shields.io/badge/RBAC-DC2626?style=flat-square&logo=letsencrypt&logoColor=white) |
| **🗄️ Data & Caching** | ![MongoDB](https://img.shields.io/badge/MongoDB-4ea94b?style=flat-square&logo=mongodb&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DD0031?style=flat-square&logo=redis&logoColor=white) ![Pinecone](https://img.shields.io/badge/Pinecone-000000?style=flat-square&logo=pinecone&logoColor=white) |
| **🤖 AI / LLM** | ![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white) ![RAG](https://img.shields.io/badge/RAG-7C3AED?style=flat-square&logo=opensearch&logoColor=white) ![Gemini API](https://img.shields.io/badge/Gemini_API-4285F4?style=flat-square&logo=googlegemini&logoColor=white) ![Prompt Engineering](https://img.shields.io/badge/Prompt_Engineering-F97316?style=flat-square&logo=openai&logoColor=white) |
| **☁️ Infra & DevOps** | ![Docker](https://img.shields.io/badge/Docker-0db7ed?style=flat-square&logo=docker&logoColor=white) ![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=amazonwebservices&logoColor=white) ![EC2](https://img.shields.io/badge/EC2-FF9900?style=flat-square&logo=amazonec2&logoColor=white) ![S3](https://img.shields.io/badge/S3-569A31?style=flat-square&logo=amazons3&logoColor=white) ![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white) ![PM2](https://img.shields.io/badge/PM2-2B037A?style=flat-square&logo=pm2&logoColor=white) ![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=flat-square&logo=ubuntu&logoColor=white) ![CloudAMQP](https://img.shields.io/badge/CloudAMQP-FF6600?style=flat-square&logo=rabbitmq&logoColor=white) ![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white) |
| **🛠️ Tools** | ![Git](https://img.shields.io/badge/Git-F05033?style=flat-square&logo=git&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) ![CI/CD](https://img.shields.io/badge/CI%2FCD-16A34A?style=flat-square&logo=githubactions&logoColor=white) ![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white) ![Sanity](https://img.shields.io/badge/Sanity-F03E2F?style=flat-square&logo=sanity&logoColor=white) |

</div>

<!-- ═══════════════════════════ EXPLORING ═══════════════════════════ -->
## 🌱 Currently Exploring

| 🧠 | ⚡ | 🏛️ | 🤖 |
|:--|:--|:--|:--|
| React Server Components and Next.js App Router | Web performance: INP, LCP, bundle analysis | System design for scalable frontends and APIs | RAG evaluation: retrieval recall and faithfulness |

<br/>

<div align="center">

> *"Code is like humor. When you have to explain it, it's bad."* — Cory House

<br/>

**📫 Let's build something together →** [Email](mailto:kuhikarpranjal@gmail.com) · [LinkedIn](https://www.linkedin.com/in/pranjal-kuhikar/) · [X](https://x.com/KuhikarPranjal) · [Portfolio](https://pranjalkuhikar.com)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:14b8a6,50:6366f1,100:0f172a&height=110&section=footer" width="100%" alt="footer" />

</div>
