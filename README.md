<div align="center">

<img src="https://avatars.githubusercontent.com/u/176728515?v=4" width="110" style="border-radius:50%" alt="Shreyash Srivastava" />

# SHREYASH SRIVASTAVA

**Backend Engineer** — Distributed Systems · APIs · Queues · Databases

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=20&duration=2800&pause=1200&color=58A6FF&center=true&vCenter=true&width=560&lines=Backend+Engineer+%C2%B7+Node.js+%2F+NestJS;Designing+for+consistency%2C+not+just+uptime;Currently+building+GitFC+%E2%9A%BD;Shipped%3A+IHateLovePDF+%C2%B7+10K%2B+users)](https://git.io/typing-svg)

<p>
<a href="https://linkedin.com/in/shreyashsrivastavaa"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="https://x.com/ShreyashSrivastavaa"><img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white" /></a>
<a href="https://shreyashsrivastava.vercel.app"><img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white" /></a>
<a href="https://leetcode.com/u/NotRambo"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=white" /></a>
<a href="mailto:shreyashsr2004@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
</p>

</div>

<br>

```
$ whoami
> backend engineer · final-year CSE · building systems that don't fall over
> shipped: 1 product with real users · 8+ projects · currently: GitFC

$ status --current
> ex Backend SDE Intern @ JBH Tech Innovation (6 months)
> freelancing @ UpscaleTechSolutions
> open to backend SDE roles
```

<br>

## `~/about`

I design backends the way you'd design anything meant to survive contact with real users — start from the failure modes, then write the happy path.

Most of what I build lives at the intersection of **queues, consistency, and state**: order pipelines that can't double-charge, booking systems that can't double-book, matching engines that can't leave a request hanging. I think in terms of trade-offs — consistency vs. availability, sync vs. async, normalized vs. denormalized — before I think in terms of frameworks.

**Not just building features. Building systems.**

<br>

## `~/currently_building`

<table>
<tr>
<td width="45%" valign="top">

<img src="./assets/gitfc-card.svg" alt="GitFC card" width="100%" />

</td>
<td width="55%" valign="top">

### ⚽ GitFC

**Turn your GitHub activity into an EA FC–style Ultimate Team card.**

GitFC pulls your commits, PRs, stars, and streaks via the GitHub GraphQL API, runs them through a weighted rating engine (45–99 OVR), assigns you a position (ST / CM / CB / GK), and renders an exportable FUT-style card — TOTY, ICON, and Gold/Silver/Bronze tiers included.

<img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ShreyashSrivastavaa/ShreyashSrivastavaa/main/assets/gitfc-status.json&style=flat-square" />
<img src="https://img.shields.io/github/stars/ShreyashSrivastavaa/GitFc?style=flat-square&label=stars&color=FFD700" />
<img src="https://img.shields.io/github/last-commit/ShreyashSrivastavaa/GitFc?style=flat-square&label=last%20shipped" />

**Stack:** `React 19` · `TypeScript` · `Vite` · `Tailwind CSS` · `html-to-image`

[**Live Demo →**](https://gitfc.vercel.app) · [**Repository →**](https://github.com/ShreyashSrivastavaa/GitFc)

</td>
</tr>
</table>

> The badges above aren't static — `gitfc-status.json` is regenerated every 6 hours by a GitHub Action that pings the live app and rewrites the endpoint. Stars and last-commit are native GitHub data, not custom-tracked.

<br>

## `~/deployed`

### 📄 IHateLovePDF — client-side PDF utility suite

<img src="https://img.shields.io/badge/status-production-brightgreen?style=flat-square" /> <img src="https://img.shields.io/badge/users-10K%2B%2Fmo-blue?style=flat-square" /> <img src="https://img.shields.io/badge/privacy-100%25%20client--side-blueviolet?style=flat-square" />

A PDF toolkit — merge, split, compress, redact, convert, unlock — that never sends your file to a server. Everything runs in the browser: `pdf-lib` / `pdf.js` inside a Web Worker pipeline, so a 200-page PDF doesn't freeze the tab.

- Worker-based processing pipeline handles concurrent uploads without blocking the main thread
- Built the compression and format-conversion paths myself — no wrapper around a third-party API
- Debugged and fixed silent data-corruption bugs in production (a detached-buffer race in the worker pipeline, and a fake-encryption path that shipped unencrypted files) — the kind of bugs that don't show up until real users hit them

**Why it matters:** this wasn't a tutorial CRUD app. It's a product 10,000+ people use monthly, and running it taught me the unglamorous half of engineering — monitoring, error boundaries, and what "done" actually means once strangers depend on your code.

**Stack:** `Next.js` · `TypeScript` · `pdf-lib` · `pdf.js` · `Web Workers`

[**Live →**](https://www.ihatelovepdf.com) · [**Repository →**](https://github.com/ShreyashSrivastavaa/IHateLovePDF)

<br>

## `~/featured`

<table>
<tr>
<td width="33%" valign="top">

**🔄 SwipeRide**
*Real-time ride matching*

Geospatial driver discovery over WebSockets, with a trip lifecycle state machine to keep ride state consistent across distributed events.

`Node.js` `Express` `MongoDB` `Socket.IO` `Redis` `JWT`

[Live](https://swipe-ride.vercel.app) · [Repo](https://github.com/ShreyashSrivastavaa/SwipeRide)

</td>
<td width="33%" valign="top">

**🍜 ZyMeal**
*Food ordering, real-time*

Full-stack ordering app with Socket.io live order tracking, JWT role auth (customer/admin), and Zod-validated checkout end to end.

`Node.js` `Express` `MongoDB` `React` `Socket.io`

[Live](https://zymeal.vercel.app) · [Repo](https://github.com/ShreyashSrivastavaa/ZyMeal)

</td>
<td width="33%" valign="top">

**🏥 Hospital Management System**
*Collaborative team project*

EMR, appointment scheduling, and bed allocation with atomic transactions — zero double-bookings by design, not by luck.

`Node.js` `Express` `PostgreSQL` `Prisma`

[Live](https://hospital-management-system-d3o5.onrender.com) · [Repo](https://github.com/ShreyashSrivastavaa/HMS)

</td>
</tr>
</table>

<br>

## `~/how_i_think_about_systems`

```
                       ┌──────────────────────────────┐
   client  ──POST──▶   │   API layer (validate, auth)  │
                       └──────────────┬────────────────┘
                                      │
                        fast path     │     slow path
                     ┌────────────────┼────────────────┐
                     ▼                                 ▼
             ┌──────────────┐                 ┌────────────────┐
             │  Postgres    │◀── consistency ──│  RabbitMQ queue │
             │ (source of   │                  │  + worker pool  │
             │  truth)      │                  └────────┬────────┘
             └──────┬───────┘                            │
                     │                                    ▼
                     └──────────────▶  Redis (cache / session / rate-limit)

   rules I actually follow:
   · the database is the source of truth — cache invalidates, never the other way
   · anything that can fail async, does fail async — retries + dead-letter, not hope
   · consistency before cleverness; optimize the query plan, not the architecture
```

<br>

## `~/stack`

<table>
<tr><td><b>Primary</b></td><td>
<img src="https://skillicons.dev/icons?i=nodejs,express,nestjs,postgres,prisma,redis" />
</td></tr>
<tr><td><b>Also shipping with</b></td><td>
<img src="https://skillicons.dev/icons?i=rabbitmq,docker,ts,js,nextjs,tailwind" />
</td></tr>
<tr><td><b>Foundations</b></td><td>
<img src="https://skillicons.dev/icons?i=cpp,git,githubactions,postman,mongodb" />
</td></tr>
<tr><td><b>Actively learning</b></td><td>
<img src="https://skillicons.dev/icons?i=go" />
</td></tr>
</table>

| Category | Technologies |
|---|---|
| **Backend runtimes** | Node.js, Express.js, NestJS |
| **Databases & caching** | PostgreSQL (indexing, transactions, query planning), Redis, Prisma ORM, MongoDB |
| **Messaging** | RabbitMQ — pub/sub, task queues, dead-letter handling |
| **Auth & validation** | JWT, RBAC, OAuth 2.0, Zod |
| **Infra** | Docker, Docker Compose, GitHub Actions, Vercel, AWS S3 |
| **Frontend (when needed)** | Next.js, React, TypeScript, Tailwind CSS |
| **Currently learning** | Go, distributed consensus, advanced PostgreSQL internals |

<br>

## `~/activity`

<div align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/contribution-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="./assets/contribution-snake-light.svg" />
  <img alt="contribution snake" src="./assets/contribution-snake-dark.svg" />
</picture>
</div>

<div align="center">

![GitHub followers](https://img.shields.io/github/followers/ShreyashSrivastavaa?style=flat-square&label=followers)
![Profile views](https://u8views.com/api/v1/github/profiles/176728515/views/day-week-month-total-count.svg)

</div>

<br>

## `~/connect`

Open to conversations about backend architecture, system design, or a product that's further along than the idea stage — if it involves queues, consistency guarantees, or turning a rough backend into a production one, I'm interested.

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/shreyashsrivastavaa)
[![X](https://img.shields.io/badge/X-Follow-000000?style=flat-square&logo=x&logoColor=white)](https://x.com/ShreyashSrivastavaa)
[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-000000?style=flat-square&logo=vercel&logoColor=white)](https://shreyashsrivastava.vercel.app)
[![Email](https://img.shields.io/badge/Email-Reach%20out-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:shreyashsr2004@gmail.com)

</div>

<br>

<div align="center">
<sub>Assets in <code>/assets</code> are generated on a schedule by the workflows in <code>/.github/workflows</code> — see below for exactly what's live vs. static.</sub>
</div>
