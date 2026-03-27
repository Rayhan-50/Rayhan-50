<!-- ========== SELF-CONTAINED SVG BANNER — NO EXTERNAL IMAGES ========== -->
<p align="center">
<svg width="900" height="280" viewBox="0 0 900 280" fill="none" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <!-- Deep dark background gradient -->
    <linearGradient id="bgGrad" x1="0" y1="0" x2="900" y2="280" gradientUnits="userSpaceOnUse">
      <stop offset="0%"   stop-color="#0a0000"/>
      <stop offset="50%"  stop-color="#1a0505"/>
      <stop offset="100%" stop-color="#0d0000"/>
    </linearGradient>
    <!-- Red accent glow gradient -->
    <radialGradient id="glowLeft" cx="20%" cy="50%" r="45%">
      <stop offset="0%"  stop-color="#FF0033" stop-opacity="0.18"/>
      <stop offset="100%" stop-color="#FF0033" stop-opacity="0"/>
    </radialGradient>
    <radialGradient id="glowRight" cx="80%" cy="50%" r="40%">
      <stop offset="0%"  stop-color="#FF0033" stop-opacity="0.10"/>
      <stop offset="100%" stop-color="#FF0033" stop-opacity="0"/>
    </radialGradient>
    <!-- Shimmer sweep -->
    <linearGradient id="shimmer" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%"   stop-color="white" stop-opacity="0"/>
      <stop offset="50%"  stop-color="white" stop-opacity="0.04"/>
      <stop offset="100%" stop-color="white" stop-opacity="0"/>
      <animate attributeName="x1" values="-100%;200%" dur="5s" repeatCount="indefinite"/>
      <animate attributeName="x2" values="0%;300%"    dur="5s" repeatCount="indefinite"/>
    </linearGradient>
    <!-- Grid pattern -->
    <pattern id="grid" width="40" height="40" patternUnits="userSpaceOnUse">
      <path d="M 40 0 L 0 0 0 40" fill="none" stroke="#FF0033" stroke-width="0.3" stroke-opacity="0.15"/>
    </pattern>
    <clipPath id="roundedClip">
      <rect width="900" height="280" rx="16" ry="16"/>
    </clipPath>
  </defs>

  <!-- Base -->
  <rect width="900" height="280" rx="16" fill="url(#bgGrad)"/>
  <!-- Grid overlay -->
  <rect width="900" height="280" rx="16" fill="url(#grid)" clip-path="url(#roundedClip)"/>
  <!-- Glow blobs -->
  <rect width="900" height="280" fill="url(#glowLeft)"  clip-path="url(#roundedClip)"/>
  <rect width="900" height="280" fill="url(#glowRight)" clip-path="url(#roundedClip)"/>
  <!-- Shimmer sweep -->
  <rect width="900" height="280" fill="url(#shimmer)"   clip-path="url(#roundedClip)"/>

  <!-- Top red accent line -->
  <rect x="0" y="0" width="900" height="3" rx="2" fill="#FF0033" opacity="0.9"/>
  <!-- Bottom red accent line -->
  <rect x="0" y="277" width="900" height="3" rx="2" fill="#FF0033" opacity="0.5"/>

  <!-- Left vertical accent bar -->
  <rect x="52" y="50" width="3" height="180" rx="2" fill="#FF0033" opacity="0.7">
    <animate attributeName="opacity" values="0.7;1;0.7" dur="3s" repeatCount="indefinite"/>
  </rect>

  <!-- RA monogram circle -->
  <circle cx="88" cy="80" r="28" fill="none" stroke="#FF0033" stroke-width="1.5" opacity="0.6"/>
  <text x="88" y="86" font-family="monospace" font-size="16" font-weight="bold" fill="#FF0033" text-anchor="middle" opacity="0.9">RA</text>

  <!-- Name -->
  <text x="130" y="82" font-family="'Courier New', monospace" font-size="34" font-weight="bold" fill="#FFFFFF" letter-spacing="2">
    Rayhan Ahmed
  </text>

  <!-- Red underline under name -->
  <rect x="130" y="92" width="340" height="2" rx="1" fill="#FF0033" opacity="0.8"/>

  <!-- Role line -->
  <text x="131" y="122" font-family="'Courier New', monospace" font-size="14" fill="#FF0033" letter-spacing="1" opacity="0.95">
    Senior Full Stack Engineer
  </text>

  <!-- Divider dot row -->
  <circle cx="131" cy="143" r="2" fill="#FF0033" opacity="0.7"/>
  <circle cx="141" cy="143" r="2" fill="#FF0033" opacity="0.5"/>
  <circle cx="151" cy="143" r="2" fill="#FF0033" opacity="0.3"/>

  <!-- Tag pills row -->
  <!-- MERN -->
  <rect x="130" y="156" width="62" height="22" rx="4" fill="#FF0033" fill-opacity="0.15" stroke="#FF0033" stroke-width="0.8" stroke-opacity="0.6"/>
  <text x="161" y="171" font-family="monospace" font-size="11" fill="#FF6680" text-anchor="middle">MERN</text>
  <!-- Next.js -->
  <rect x="200" y="156" width="62" height="22" rx="4" fill="#FF0033" fill-opacity="0.15" stroke="#FF0033" stroke-width="0.8" stroke-opacity="0.6"/>
  <text x="231" y="171" font-family="monospace" font-size="11" fill="#FF6680" text-anchor="middle">Next.js</text>
  <!-- TypeScript -->
  <rect x="270" y="156" width="80" height="22" rx="4" fill="#FF0033" fill-opacity="0.15" stroke="#FF0033" stroke-width="0.8" stroke-opacity="0.6"/>
  <text x="310" y="171" font-family="monospace" font-size="11" fill="#FF6680" text-anchor="middle">TypeScript</text>
  <!-- Docker -->
  <rect x="358" y="156" width="62" height="22" rx="4" fill="#FF0033" fill-opacity="0.15" stroke="#FF0033" stroke-width="0.8" stroke-opacity="0.6"/>
  <text x="389" y="171" font-family="monospace" font-size="11" fill="#FF6680" text-anchor="middle">Docker</text>
  <!-- Golang -->
  <rect x="428" y="156" width="62" height="22" rx="4" fill="#FF0033" fill-opacity="0.15" stroke="#FF0033" stroke-width="0.8" stroke-opacity="0.6"/>
  <text x="459" y="171" font-family="monospace" font-size="11" fill="#FF6680" text-anchor="middle">Golang</text>

  <!-- Tagline -->
  <text x="130" y="212" font-family="'Courier New', monospace" font-size="13" fill="#aaaaaa" letter-spacing="0.5">
    Designing scalable systems &amp; production-grade APIs
  </text>

  <!-- Location / email line -->
  <text x="130" y="238" font-family="monospace" font-size="11" fill="#666666">
    📍 Dhaka, Bangladesh  ·  rayhanahmed.nstu@gmail.com
  </text>

  <!-- Right-side decorative circuit lines -->
  <line x1="720" y1="60"  x2="860" y2="60"  stroke="#FF0033" stroke-width="0.6" stroke-opacity="0.3"/>
  <line x1="740" y1="80"  x2="860" y2="80"  stroke="#FF0033" stroke-width="0.6" stroke-opacity="0.2"/>
  <line x1="760" y1="100" x2="860" y2="100" stroke="#FF0033" stroke-width="0.6" stroke-opacity="0.15"/>
  <circle cx="720" cy="60"  r="3" fill="#FF0033" opacity="0.5"/>
  <circle cx="740" cy="80"  r="3" fill="#FF0033" opacity="0.4"/>
  <circle cx="760" cy="100" r="3" fill="#FF0033" opacity="0.3"/>
  <!-- Vertical connector -->
  <line x1="860" y1="60" x2="860" y2="100" stroke="#FF0033" stroke-width="0.6" stroke-opacity="0.3"/>

  <!-- Large faint background RA watermark -->
  <text x="660" y="230" font-family="monospace" font-size="130" font-weight="bold" fill="#FF0033" fill-opacity="0.04" text-anchor="middle">RA</text>

  <!-- Animated pulse dot top-right -->
  <circle cx="860" cy="40" r="5" fill="#FF0033" opacity="0.9">
    <animate attributeName="r"       values="5;8;5"     dur="2s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.9;0.3;0.9" dur="2s" repeatCount="indefinite"/>
  </circle>
  <circle cx="860" cy="40" r="10" fill="none" stroke="#FF0033" stroke-width="1" opacity="0.4">
    <animate attributeName="r"       values="10;16;10"  dur="2s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.4;0;0.4"  dur="2s" repeatCount="indefinite"/>
  </circle>
</svg>
</p>

<!-- ========== ROLE TICKER (RED) ========== -->
<h3 align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=900&duration=1800&color=FF0033&center=true&vCenter=true&width=900&lines=Designing+Scalable+Systems+%26+Production-Grade+APIs;Senior+Full+Stack+Engineer+%7C+MERN+%2B+Next.js+%2B+TypeScript;Backend+Architecture+%7C+PostgreSQL+%7C+Docker+%7C+Golang;Clean+Code.+Zero+Compromise.+Ship+at+Scale." alt="typing roles" />
</h3>

<!-- ========== QUICK CONTACT / CTA (RED) ========== -->
<p align="center">
  <a href="mailto:rayhanahmed.nstu@gmail.com">
    <img src="https://img.shields.io/badge/Hire%20Me-FF0033?style=for-the-badge&logo=Handshake&logoColor=000&labelColor=1b0a0a&color=FF0033" />
  </a>
  <a href="https://adhesive-bed.surge.sh/">
    <img src="https://img.shields.io/badge/Portfolio-Visit-1b0a0a?style=for-the-badge&logo=google-chrome&logoColor=FF0033" />
  </a>
  <a href="https://linkedin.com/in/rayhan-ahmed-0ab5aa33a">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-1b0a0a?style=for-the-badge&logo=linkedin&logoColor=FF0033" />
  </a>
  <a href="https://github.com/Rayhan-50">
    <img src="https://img.shields.io/badge/GitHub-Rayhan--50-181717?style=for-the-badge&logo=github&logoColor=FF0033" />
  </a>
</p>

<br/>

---

## 🧠 About Me

I'm a **Senior Full Stack Engineer** who builds production-grade systems — not just working prototypes, but **scalable, maintainable, observable** applications that hold up under real-world load.

My work lives at the intersection of **backend engineering, API design, and systems architecture**. I care deeply about the things that matter in production: latency, failure recovery, data integrity, and developer ergonomics.

```
🔧  Systems I build:   REST & GraphQL APIs · Auth systems · Background jobs · Microservices
📐  How I think:       Domain-driven design · Separation of concerns · Fail-fast principle
🚀  What I optimize:   Query performance · Bundle size · Response time · Developer feedback loops
🌍  Location:          Dhaka, Bangladesh  ·  Available for remote & contract work
📫  Contact:           rayhanahmed.nstu@gmail.com
```

> *I don't just write code that works — I write code that scales, survives, and is easy to reason about six months later.*

---

## 💎 What I Do Best

<table>
  <tr>
    <td>⚙️</td>
    <td><strong>Scalable Backend Systems</strong></td>
    <td>Design and ship APIs and services built for growth — modular, observable, and fault-tolerant</td>
  </tr>
  <tr>
    <td>📐</td>
    <td><strong>RESTful & GraphQL API Design</strong></td>
    <td>Resource-first API modeling with versioning, validation, rate-limiting, and clean error contracts</td>
  </tr>
  <tr>
    <td>🗄️</td>
    <td><strong>Database Architecture</strong></td>
    <td>Relational data modeling in PostgreSQL, query optimization, indexing strategy, and Prisma ORM</td>
  </tr>
  <tr>
    <td>🔐</td>
    <td><strong>Auth & Security</strong></td>
    <td>JWT, OAuth2, session management, RBAC, input sanitization, and secure cookie patterns</td>
  </tr>
  <tr>
    <td>🖥️</td>
    <td><strong>Full-Stack React / Next.js</strong></td>
    <td>SSR, ISR, App Router, streaming, Server Actions — the full Next.js production toolkit</td>
  </tr>
  <tr>
    <td>🐳</td>
    <td><strong>Containerized Deployments</strong></td>
    <td>Docker, multi-stage builds, Docker Compose, Nginx reverse proxy, and CI/CD pipelines</td>
  </tr>
  <tr>
    <td>⚡</td>
    <td><strong>Performance Engineering</strong></td>
    <td>Core Web Vitals, caching layers (Redis), DB indexing, lazy loading, and bundle optimization</td>
  </tr>
</table>

---

## 🛠️ Tech Stack

### ⚡ Languages & Runtimes

| Tech | Badge | Strength |
|---|---|---|
| **TypeScript** | ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) | Strong typing, scalable codebases, zero runtime surprises |
| **JavaScript** | ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=000) | Deep ES2022+ knowledge, async patterns, event loop mastery |
| **Golang** | ![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white) | High-performance concurrent systems, CLI tools, microservices |

### 🖥️ Frontend

| Tech | Badge | Strength |
|---|---|---|
| **Next.js** | ![Next.js](https://img.shields.io/badge/Next.js-000?style=flat-square&logo=nextdotjs&logoColor=white) | SSR, ISR, App Router, full-stack React, streaming |
| **React** | ![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB) | Component architecture, custom hooks, compound patterns |
| **TailwindCSS** | ![TailwindCSS](https://img.shields.io/badge/TailwindCSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white) | Utility-first systems, design tokens, responsive layouts |

### ⚙️ Backend & APIs

| Tech | Badge | Strength |
|---|---|---|
| **Node.js** | ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white) | Async architecture, streams, backend runtime, event-driven |
| **Express** | ![Express](https://img.shields.io/badge/Express-000?style=flat-square&logo=express&logoColor=white) | REST APIs, middleware pipelines, route composition |
| **Firebase** | ![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=000) | Realtime DB, Auth, Firestore, Cloud Functions |

### 🗄️ Databases & ORM

| Tech | Badge | Strength |
|---|---|---|
| **PostgreSQL** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white) | Relational modeling, indexing, query optimization, transactions |
| **MongoDB** | ![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=flat-square&logo=mongodb&logoColor=white) | Document modeling, aggregations, schema design |
| **Prisma** | ![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white) | Type-safe database layer, migrations, relation modeling |

### 🚀 DevOps & Tooling

| Tech | Badge | Strength |
|---|---|---|
| **Docker** | ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) | Containerized deployments, multi-stage builds, Compose |
| **Nginx** | ![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white) | Reverse proxy, load balancing, SSL termination |
| **Git / GitHub** | ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) | Branch strategies, CI/CD, code review workflows |
| **VS Code** | ![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=flat-square&logo=visual-studio-code&logoColor=white) | Advanced configs, custom snippets, workspace tuning |

---

## 🏗️ Architecture Mindset

```
┌─────────────┐     ┌──────────────────┐     ┌──────────────────────┐
│   Client    │────▶│  Next.js Layer   │────▶│  API Layer           │
│  (Browser)  │     │  SSR · ISR · RSC │     │  Node/Express · REST │
└─────────────┘     └──────────────────┘     └──────────┬───────────┘
                                                         │
                          ┌──────────────────────────────┤
                          │                              │
                ┌─────────▼──────────┐      ┌───────────▼───────────┐
                │   Primary DB       │      │   Cache Layer         │
                │  PostgreSQL/Mongo  │      │   Redis / Edge Cache  │
                └─────────┬──────────┘      └───────────────────────┘
                          │
                ┌─────────▼──────────┐
                │   Deployment       │
                │  Docker · Nginx    │
                │  CI/CD Pipeline    │
                └────────────────────┘
```

**How I think about systems:**

- **Separation of Concerns** — Each layer owns one responsibility. Business logic never bleeds into routes. DB queries never live inside components.
- **Scalability First** — Services are stateless by design, enabling horizontal scaling. Shared state lives in Redis or the DB — never in memory.
- **Performance at Every Layer** — DB indexes before adding cache. N+1 queries eliminated. Response payloads shaped to what the client actually needs.
- **Observability** — Structured logging, error boundaries, and health-check endpoints are not afterthoughts — they ship with the feature.

---

## ⚡ Engineering Snippet

A taste of how I write production-grade code:

```typescript
// ── types/user.ts ─────────────────────────────────────────────
interface CreateUserDTO {
  name: string;
  email: string;
  role: "admin" | "user" | "guest";
}

interface ApiResponse<T> {
  success: boolean;
  data: T;
  meta?: { total?: number; page?: number };
}
```

```typescript
// ── routes/users.ts ───────────────────────────────────────────
import { Router, Request, Response, NextFunction } from "express";
import { validateBody } from "../middleware/validate";
import { createUserSchema } from "../schemas/user.schema";
import { UserService } from "../services/user.service";

const router = Router();

router.post(
  "/",
  validateBody(createUserSchema),
  async (req: Request, res: Response, next: NextFunction) => {
    try {
      const user = await UserService.create(req.body as CreateUserDTO);
      res.status(201).json({ success: true, data: user });
    } catch (err) {
      next(err); // centralised error handler
    }
  }
);

export default router;
```

```typescript
// ── services/user.service.ts ──────────────────────────────────
import { prisma } from "../lib/prisma";
import type { CreateUserDTO } from "../types/user";

export const UserService = {
  async create(dto: CreateUserDTO) {
    return prisma.user.create({
      data: dto,
      select: { id: true, name: true, email: true, role: true, createdAt: true },
    });
  },

  async findByEmail(email: string) {
    return prisma.user.findUnique({
      where: { email },
      include: { profile: true },
    });
  },
};
```

> Clean schema validation at the route boundary · Service layer owns DB access · Prisma for type-safe queries · Centralised error propagation.

---

## 🔥 Highlighted Projects

### 🔐 VISA Client — Visa Management Portal

> A full-stack portal for managing visa applications with role-based auth, protected routes, and complete CRUD workflows.

- **Problem solved:** Manual visa tracking with zero digital infrastructure — replaced with a structured, auth-gated portal
- **Architecture:** React SPA with Firebase Auth + Firestore, client-side route protection via custom auth context
- **Real-world value:** Dynamic status tracking, multi-role access control, and form-driven data entry

[![Live](https://img.shields.io/badge/Live-Demo-FF0033?style=flat-square&logo=google-chrome&logoColor=white)](https://assignment-10-427ea.firebaseapp.com/)
[![Code](https://img.shields.io/badge/Source-Code-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Rayhan-50/VISA-client)
`React` `Firebase Auth` `Firestore` `Protected Routes` `CRUD`

---

### 🌍 Tourism Management — Full-Stack Booking Platform

> End-to-end tour booking application with authenticated user flows, dynamic listings, and booking management.

- **Problem solved:** Tourism operators needed a branded platform replacing manual booking coordination
- **Architecture:** Component-driven React frontend · Firebase Realtime DB · context-based auth with persistent sessions
- **Real-world value:** Live booking state, protected user dashboards, and scalable listing structure

[![Live](https://img.shields.io/badge/Live-Demo-FF0033?style=flat-square&logo=google-chrome&logoColor=white)](https://tourism-management-28e12.web.app/)
[![Code](https://img.shields.io/badge/Source-Code-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Rayhan-50/TOURISM-MANAGEMENT-Client)
`React` `Firebase` `Booking Flow` `Auth` `Dynamic Routing`

---

### 🏨 Hotel Booking — Listings & Reservation System

> Hotel listing platform with advanced filters, detailed property pages, and a complete booking flow.

- **Problem solved:** Static hotel pages with no reservation pipeline — replaced with an interactive booking system
- **Architecture:** Filter-driven listing architecture, booking state modeled cleanly through React context + Firebase
- **Real-world value:** Price/availability filtering, room selection, and booking confirmation workflow

[![Live](https://img.shields.io/badge/Live-Demo-FF0033?style=flat-square&logo=google-chrome&logoColor=white)](https://hotel-booking-client-2f049.web.app/)
[![Code](https://img.shields.io/badge/Source-Code-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Rayhan-50/Hotel-Booking-client)
`React` `Firebase` `Filtering` `Booking UX` `Responsive UI`

---

## 📊 GitHub Stats & Activity

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Rayhan-50&show_icons=true&theme=tokyonight&hide_border=false&count_private=true&include_all_commits=true" height="170" />
  &nbsp;&nbsp;
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Rayhan-50&layout=compact&theme=tokyonight&hide_border=false&langs_count=8" height="170" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Rayhan-50&theme=tokyonight&hide_border=false" width="49%" />
  &nbsp;
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Rayhan-50&theme=tokyonight" width="49%" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Rayhan-50&theme=redical&hide_border=false&area=true" width="98%" />
</p>

---

## 🎯 Engineering Goals

```
  Q2 2025 ──▶  Ship production app with Next.js App Router + Prisma + PostgreSQL
  Q3 2025 ──▶  Master Golang microservices with gRPC & message queues
  Q4 2025 ──▶  Full Docker + Nginx + CI/CD deployment pipeline on VPS
  2026    ──▶  Contribute to open-source backend tooling + publish engineering blog
```

---

## 🤝 Let's Connect

<p align="center">

[![Portfolio](https://img.shields.io/badge/🌐%20Portfolio-adhesive--bed.surge.sh-1b0a0a?style=for-the-badge&logo=google-chrome&logoColor=FF0033)](https://adhesive-bed.surge.sh/)
[![GitHub](https://img.shields.io/badge/GitHub-Rayhan--50-181717?style=for-the-badge&logo=github&logoColor=FF0033)](https://github.com/Rayhan-50)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-rayhan--ahmed-1b0a0a?style=for-the-badge&logo=linkedin&logoColor=FF0033)](https://linkedin.com/in/rayhan-ahmed-0ab5aa33a)
[![Email](https://img.shields.io/badge/Email-rayhanahmed.nstu%40gmail.com-1b0a0a?style=for-the-badge&logo=gmail&logoColor=FF0033)](mailto:rayhanahmed.nstu@gmail.com)

</p>

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=120&color=ff0033&section=footer" />
</p>

<p align="center">
  <i>"The function of good software is to make the complex appear simple." — Grady Booch</i>
</p>
