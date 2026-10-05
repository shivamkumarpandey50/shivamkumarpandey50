<!-- ───────────── HEADER ───────────── -->
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,24&height=230&section=header&text=Shivam%20Kumar%20Pandey&fontSize=46&fontColor=ffffff&fontAlignY=38&animation=fadeIn&desc=Full-Stack%20Engineer%20%C2%B7%20AI%20Systems%20%C2%B7%20Distributed%20Backends&descSize=17&descAlignY=60" alt="Shivam Kumar Pandey" width="100%" />

<a href="https://github.com/shivamkumarpandey50">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=21&duration=3200&pause=900&color=58A6FF&center=true&vCenter=true&width=720&height=45&lines=Full-Stack+Software+Engineer+%C2%B7+Gurugram%2C+India;Building+enterprise+aviation+ERP+%40+Aerotech+FMS;AI+agents+%C2%B7+LLM+pipelines+%C2%B7+event-driven+microservices;React+%C2%B7+TypeScript+%C2%B7+NestJS+%C2%B7+PostgreSQL" alt="Typing intro" />
</a>

<br/>

<a href="https://linkedin.com/in/shivamkumarpandey50"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="mailto:shivamkumarpandey3971@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
<img src="https://img.shields.io/badge/Open%20to-Backend%20%2F%20Full--Stack%20roles-2ea44f?style=for-the-badge" alt="Open to work" />
<img src="https://komarev.com/ghpvc/?username=shivamkumarpandey50&label=Profile%20views&color=0e75b6&style=for-the-badge" alt="Profile views" />

</div>

<br/>

<!-- ───────────── PILLARS ───────────── -->
## ⚡ What I do

<table>
<tr>
<td width="33%" valign="top">

### 🛫 Enterprise Systems
Owning features end to end on an **aviation ERP**: permits, flight dispatch, GST invoicing and briefing PDFs. Multi-step flows, role-based UI, race-condition and data-integrity fixes in production.

</td>
<td width="33%" valign="top">

### 🤖 AI Engineering
Shipping **LLM features** that do real work: an email-to-structured-permit pipeline (Microsoft Graph + GPT-4o-mini), Gemini trip summaries, and a **tool-calling ops agent** over live FMS data.

</td>
<td width="33%" valign="top">

### 🏗️ Distributed Backends
Designing **event-driven microservices**: database-per-service, Kafka with the transactional outbox pattern, PostGIS for geospatial data, Redis, WebSockets and Docker.

</td>
</tr>
</table>

<!-- ───────────── FEATURED ───────────── -->
## 🚀 Featured work

### 🛵 SmartFleet: real-time delivery & fleet platform

Seven NestJS services behind an API gateway, a React/Vite/TypeScript/Tailwind frontend, database-per-service on PostgreSQL, and reliable event publishing through a Kafka outbox. Documented end to end (README, HLD, LLD, DB and API design, setup guide).

```mermaid
flowchart LR
    UI["⚛️ React UI<br/>(Vite · TS · Tailwind)"] -->|REST| GW["🚪 API Gateway"]
    UI <-.->|WebSockets| NS

    GW --> US["👤 User Service"]
    GW --> RS["🍽️ Restaurant Service"]
    GW --> OS["🧾 Order Service"]
    GW --> DS["🛵 Delivery Service"]

    US --> DB1[("PostgreSQL")]
    RS --> DB2[("PostgreSQL")]
    OS --> DB3[("PostgreSQL")]
    DS --> DB4[("PostGIS")]
    DS --- RD[("Redis")]

    OS -- "outbox" --> K{{"Kafka"}}
    DS -- "outbox" --> K
    K --> NS["🔔 Notification Service"]
    K --> AN["📊 Analytics Service"]
```

`NestJS` `PostgreSQL` `PostGIS` `Prisma` `Redis` `Kafka` `WebSockets` `Docker` `pnpm workspaces` `React`

<br/>

<table>
<tr>
<td width="50%" valign="top">

### 🧠 FMS Ops Agent
A standalone **AI agent** that answers flight and permit status questions from Aerotech FMS data. Gemini tool-calling, an agent loop, and a tool registry covering flight, permit, invoice and email tools.

`NestJS` `Prisma` `Gemini`

</td>
<td width="50%" valign="top">

### 🧳 Rajasthan Cabs & Tours (Live)
A production **travel booking platform** built end to end for a real client: dynamic tour and cab pages, a full SEO suite (Open Graph, Twitter Cards, canonical URLs, 20+ keywords) and dual Nodemailer booking emails.

`Next.js` `TypeScript` `Tailwind` `Nodemailer`

</td>
</tr>
</table>

<!-- ───────────── EXPERIENCE ───────────── -->
## 💼 Experience

| | Role | Company | Highlights |
|:-:|:--|:--|:--|
| 🟢 | **Full-Stack Developer**<br/>*Present* | **Aerotech FMS** · Gurugram | Aviation ERP, AI permit-email pipeline, Gemini features, PDF generation, RocketRoute + PostGIS integration |
| 🔵 | **Junior Full-Stack Developer**<br/>*Aug 2025 – Dec 2025* | **Nextify Solutions** · Lucknow | 30+ page SEO-optimised Next.js site; Lighthouse performance **+30%** via lazy loading, code splitting, image optimisation |
| 🟣 | **Junior Full-Stack Developer**<br/>*Aug 2024 – Feb 2025* | **xBesh Technologies** · Noida | Accessible UI components for a library adopted by **1,000+ developers**; React, TypeScript, Redux, MongoDB |

<!-- ───────────── STACK ───────────── -->
## 🛠️ Tech arsenal

<div align="center">

**Frontend**<br/>
<img src="https://skillicons.dev/icons?i=react,nextjs,ts,js,redux,tailwind,vite,html,css&perline=9" alt="Frontend" />

**Backend & Data**<br/>
<img src="https://skillicons.dev/icons?i=nodejs,nestjs,prisma,postgres,mongodb,redis,kafka&perline=7" alt="Backend" />

**Tooling**<br/>
<img src="https://skillicons.dev/icons?i=docker,git,github,linux,vercel,postman&perline=6" alt="Tooling" />

**Currently learning**<br/>
<img src="https://skillicons.dev/icons?i=kubernetes,aws&perline=2" alt="Learning" />

</div>

<!-- ───────────── STATS ───────────── -->
## 📊 GitHub & coding stats

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=shivamkumarpandey50&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=58a6ff&icon_color=58a6ff" alt="GitHub stats" />
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=shivamkumarpandey50&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=58a6ff" alt="Top languages" />

<br/><br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=shivamkumarpandey50&theme=tokyo-night&hide_border=true&bg_color=0d1117&area=true" alt="Contribution graph" width="100%" />

<br/>

🧩 **LeetCode:** 646 problems solved · rating ~1,656 · top ~17% · 365-day streak

<br/>

<img src="https://raw.githubusercontent.com/shivamkumarpandey50/shivamkumarpandey50/output/github-snake-dark.svg" alt="Contribution snake" width="100%" />

</div>

<!-- ───────────── FOOTER ───────────── -->
<div align="center">

### 📫 Let's build something great together
**shivamkumarpandey3971@gmail.com**

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,24&height=120&section=footer" alt="" width="100%" />

</div>
