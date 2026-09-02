[README_ShreyashSrivastavaa.md](https://github.com/user-attachments/files/31718003/README_ShreyashSrivastavaa.md)
::: {align="center"}
`<img src="https://avatars.githubusercontent.com/u/176728515?v=4" width="110" alt="Shreyash Srivastava" />`{=html}

# SHREYASH SRIVASTAVA

**Backend Engineer** --- Distributed Systems · APIs · Queues · Databases

*I build production-grade backend systems and care about what happens
when things fail.*

[![Typing
SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=20&duration=2800&pause=1200&color=58A6FF&center=true&vCenter=true&width=620&lines=Backend+Engineer+%C2%B7+Node.js+%2F+NestJS;Designing+for+consistency%2C+not+just+uptime;Currently+building+GitFC+%E2%9A%BD;Shipped%3A+IHateLovePDF+%C2%B7+10K%2B+users)](https://git.io/typing-svg)

```{=html}
<p>
```
`<a href="https://linkedin.com/in/shreyashsrivastavaa">`{=html}`<img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />`{=html}`</a>`{=html}
`<a href="https://x.com/ShreyashSrivastavaa">`{=html}`<img src="https://img.shields.io/badge/X-Follow-000000?style=for-the-badge&logo=x&logoColor=white" />`{=html}`</a>`{=html}
`<a href="https://shreyashsrivastava.vercel.app">`{=html}`<img src="https://img.shields.io/badge/Portfolio-Visit-000000?style=for-the-badge&logo=vercel&logoColor=white" />`{=html}`</a>`{=html}
`<a href="https://leetcode.com/u/NotRambo">`{=html}`<img src="https://img.shields.io/badge/LeetCode-Profile-FFA116?style=for-the-badge&logo=leetcode&logoColor=white" />`{=html}`</a>`{=html}
`<a href="mailto:shreyashsr2004@gmail.com">`{=html}`<img src="https://img.shields.io/badge/Email-Reach%20out-D14836?style=for-the-badge&logo=gmail&logoColor=white" />`{=html}`</a>`{=html}
```{=html}
</p>
```
:::

------------------------------------------------------------------------

``` text
$ whoami
> backend engineer · final-year CSE · building systems that don't fall over
> shipped: 1 product with real users · 8+ projects · currently: GitFC

$ status --current
> ex Backend SDE Intern @ JBH Tech Innovation (6 months)
> freelancing @ UpscaleTechSolutions
> open to backend SDE roles
```

## `identity`

I design backends the way you'd design anything meant to survive contact
with real users --- start from the failure modes, then write the happy
path.

Most of what I build lives at the intersection of **queues, consistency,
and state**: order pipelines that can't double-charge, booking systems
that can't double-book, matching engines that can't leave a request
hanging.

I think in terms of trade-offs --- **consistency vs. availability, sync
vs. async, normalized vs. denormalized** --- before I think in terms of
frameworks.

**Not just building features. Building systems.**

------------------------------------------------------------------------

## `in_progress`

```{=html}
<table>
```
```{=html}
<tr>
```
```{=html}
<td width="45%" valign="top">
```
`<a href="https://gitfc.vercel.app">`{=html}
`<img src="https://raw.githubusercontent.com/ShreyashSrivastavaa/ShreyashSrivastavaa/main/assets/gitfc-card.svg" alt="GitFC card" width="100%" />`{=html}
`</a>`{=html}

```{=html}
</td>
```
```{=html}
<td width="55%" valign="top">
```
### ⚽ GitFC

**Turn your GitHub activity into an EA FC--style Ultimate Team card.**

GitFC pulls commits, PRs, stars, and streaks through the GitHub GraphQL
API, runs them through a weighted rating engine, assigns a position, and
renders an exportable FUT-style card.

**Stack:** `React 19` · `TypeScript` · `Vite` · `Tailwind CSS` ·
`html-to-image`

[**Live Demo →**](https://gitfc.vercel.app) · [**Repository
→**](https://github.com/ShreyashSrivastavaa/GitFc)

```{=html}
</td>
```
```{=html}
</tr>
```
```{=html}
</table>
```
> The GitFC card above is served from the repository's `assets/`
> directory so GitHub renders it reliably. The status/stars/last-shipped
> badges below are live endpoints.

```{=html}
<p align="center">
```
`<img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/ShreyashSrivastavaa/ShreyashSrivastavaa/main/assets/gitfc-status.json&style=flat-square" alt="GitFC status" />`{=html}
`<img src="https://img.shields.io/github/stars/ShreyashSrivastavaa/GitFc?style=flat-square&label=stars" alt="GitFC stars" />`{=html}
`<img src="https://img.shields.io/github/last-commit/ShreyashSrivastavaa/GitFc?style=flat-square&label=last%20shipped" alt="GitFC last commit" />`{=html}
```{=html}
</p>
```

------------------------------------------------------------------------

## `shipped`

### 📄 IHateLovePDF --- client-side PDF utility suite

`<img src="https://img.shields.io/badge/status-production-brightgreen?style=flat-square" />`{=html}
`<img src="https://img.shields.io/badge/users-10K%2B%2Fmo-blue?style=flat-square" />`{=html}
`<img src="https://img.shields.io/badge/privacy-100%25%20client--side-blueviolet?style=flat-square" />`{=html}

A PDF toolkit --- merge, split, compress, redact, convert, unlock ---
that never sends your file to a server. Everything runs in the browser
using `pdf-lib` / `pdf.js` inside a Web Worker pipeline.

-   Worker-based processing without blocking the main thread
-   Built the compression and format-conversion paths myself
-   Debugged production data-corruption bugs involving worker buffers
    and encryption paths
-   **10,000+ monthly users**

**Stack:** `Next.js` · `TypeScript` · `pdf-lib` · `pdf.js` ·
`Web Workers`

[**Live →**](https://www.ihatelovepdf.com) · [**Repository
→**](https://github.com/ShreyashSrivastavaa/IHateLovePDF)

------------------------------------------------------------------------

## `systems`

```{=html}
<table>
```
```{=html}
<tr>
```
```{=html}
<td width="33%" valign="top">
```
### 🔄 SwipeRide

*Real-time ride matching*

Geospatial driver discovery over WebSockets, with a trip lifecycle state
machine to keep ride state consistent across distributed events.

`Node.js` `Express` `MongoDB` `Socket.IO` `Redis` `JWT`

[Live](https://swipe-ride.vercel.app) ·
[Repo](https://github.com/ShreyashSrivastavaa/SwipeRide)

```{=html}
</td>
```
```{=html}
<td width="33%" valign="top">
```
### 🍜 ZyMeal

*Food ordering, real-time*

Full-stack ordering app with Socket.io live order tracking, JWT role
auth, and Zod-validated checkout.

`Node.js` `Express` `MongoDB` `React` `Socket.io`

[Live](https://zymeal.vercel.app) ·
[Repo](https://github.com/ShreyashSrivastavaa/ZyMeal)

```{=html}
</td>
```
```{=html}
<td width="33%" valign="top">
```
### 🏥 Hospital Management System

*Collaborative team project*

EMR, appointment scheduling, and bed allocation with atomic transactions
--- zero double-bookings by design.

`Node.js` `Express` `PostgreSQL` `Prisma`

[Live](https://hospital-management-system-d3o5.onrender.com) ·
[Repo](https://github.com/ShreyashSrivastavaa/HMS)

```{=html}
</td>
```
```{=html}
</tr>
```
```{=html}
</table>
```

------------------------------------------------------------------------

## `toolbox`

```{=html}
<p align="center">
```
`<img src="https://skillicons.dev/icons?i=nodejs,express,nestjs,postgres,prisma,redis,rabbitmq,docker,ts,js,nextjs,tailwind,cpp,git,githubactions,mongodb,go" alt="Technology stack" />`{=html}
```{=html}
</p>
```
```{=html}
<table>
```
```{=html}
<tr>
```
```{=html}
<td width="50%" valign="top">
```
**Backend**

`Node.js` · `Express.js` · `NestJS`

**Data**

`PostgreSQL` · `Redis` · `Prisma` · `MongoDB`

**Messaging**

`RabbitMQ` · Pub/Sub · Task Queues · Dead Letters

```{=html}
</td>
```
```{=html}
<td width="50%" valign="top">
```
**Infrastructure**

`Docker` · `Docker Compose` · `GitHub Actions` · `Vercel` · `AWS S3`

**Frontend**

`Next.js` · `React` · `TypeScript` · `Tailwind CSS`

**Foundations**

`C++` · `Git` · `Postman`

```{=html}
</td>
```
```{=html}
</tr>
```
```{=html}
</table>
```

------------------------------------------------------------------------

## `language_mix`

::: {align="center"}
`<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ShreyashSrivastavaa&layout=compact&langs_count=10&hide_border=true&theme=github_dark&cache_seconds=86400" alt="Most used languages" />`{=html}
:::

------------------------------------------------------------------------

## `engineering_thought`

``` text
                       ┌──────────────────────────────┐
   client ──POST──▶    │   API layer (validate, auth) │
                       └──────────────┬───────────────┘
                                      │
                            fast path │ slow path
                                      │
                         ┌────────────┼────────────┐
                         ▼                         ▼
                 ┌──────────────┐         ┌────────────────┐
                 │  PostgreSQL  │◀────────│ RabbitMQ queue │
                 │ source truth │ consistency│ + workers   │
                 └──────┬───────┘         └───────┬────────┘
                        │                          │
                        └──────────┬───────────────┘
                                   ▼
                         Redis / cache / sessions

rules I actually follow:
· database is the source of truth — cache invalidates, never the other way
· anything that can fail async, does fail async — retries + dead-letter, not hope
· consistency before cleverness; optimize the query plan, not the architecture
```

------------------------------------------------------------------------

## `telemetry`

::: {align="center"}
[![GitHub
Streak](https://streak-stats.demolab.com?user=ShreyashSrivastavaa&theme=github-dark&hide_border=true)](https://git.io/streak-stats)

`<img src="https://github-readme-activity-graph.vercel.app/graph?username=ShreyashSrivastavaa&theme=github-compact&hide_border=true&area=true&custom_title=Contribution%20Graph" alt="GitHub contribution graph" width="95%" />`{=html}

`<br />`{=html}

`<img src="https://raw.githubusercontent.com/Platane/snk/output/github-contribution-grid-snake-dark.svg" alt="Contribution snake" width="95%" />`{=html}
:::

------------------------------------------------------------------------

## `metrics`

::: {align="center"}
`<img src="https://github-readme-stats.vercel.app/api?username=ShreyashSrivastavaa&show_icons=true&include_all_commits=true&count_private=true&hide_border=true&theme=github_dark&rank_icon=github" alt="GitHub stats" width="49%" />`{=html}
`<img src="https://github-readme-streak-stats.herokuapp.com?user=ShreyashSrivastavaa&theme=github-dark-blue&hide_border=true" alt="GitHub streak" width="49%" />`{=html}

`<br />`{=html}`<br />`{=html}

`<img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=ShreyashSrivastavaa&theme=github_dark" alt="Profile summary" width="98%" />`{=html}
:::

------------------------------------------------------------------------

## `milestones`

::: {align="center"}
`<img src="https://github-profile-trophy.vercel.app/?username=ShreyashSrivastavaa&theme=darkhub&no-frame=true&no-bg=true&margin-w=10&row=1&column=8" alt="GitHub trophies" width="100%" />`{=html}
:::

------------------------------------------------------------------------

## `open_source`

::: {align="center"}
`<img src="https://github-readme-stats.vercel.app/api/pin/?username=ShreyashSrivastavaa&repo=GitFc&theme=github_dark&hide_border=true" alt="GitFC" />`{=html}
`<img src="https://github-readme-stats.vercel.app/api/pin/?username=ShreyashSrivastavaa&repo=IHateLovePDF&theme=github_dark&hide_border=true" alt="IHateLovePDF" />`{=html}
:::

------------------------------------------------------------------------

## `community`

::: {align="center"}
`<img src="https://img.shields.io/badge/GSSoC-2026-7B61FF?style=for-the-badge&logo=github&logoColor=white" alt="GSSoC 2026" />`{=html}

`<br />`{=html}`<br />`{=html}

*Contribution badges can be added here once their official image URLs
are available.*
:::

------------------------------------------------------------------------

## `signal`

::: {align="center"}
`<img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=dark" alt="Random developer quote" width="85%" />`{=html}
:::

------------------------------------------------------------------------

## `contact`

Open to conversations about backend architecture, system design, or a
product that's further along than the idea stage --- especially if it
involves **queues, consistency guarantees, or turning a rough backend
into a production one**.

::: {align="center"}
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/shreyashsrivastavaa)
[![X](https://img.shields.io/badge/X-Follow-000000?style=flat-square&logo=x&logoColor=white)](https://x.com/ShreyashSrivastavaa)
[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-000000?style=flat-square&logo=vercel&logoColor=white)](https://shreyashsrivastava.vercel.app)
[![Email](https://img.shields.io/badge/Email-Reach%20out-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:shreyashsr2004@gmail.com)

`<br />`{=html}

![Profile
views](https://u8views.com/api/v1/github/profiles/176728515/views/day-week-month-total-count.svg)
:::

------------------------------------------------------------------------

::: {align="center"}
`<sub>`{=html} Built with Markdown, GitHub Actions, and an unreasonable
number of SVGs. `</sub>`{=html}
:::
