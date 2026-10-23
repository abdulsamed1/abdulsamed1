<div align="center">

![Header](https://capsule-render.vercel.app/api?type=waving&color=0:1a1a2e,100:16213e&height=200&section=header&text=Abdulsamed%20Hamdy&fontSize=50&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Software%20Engineer%20%7C%20Backend%20%26%20Distributed%20Systems%20%7C%20AI%20Infrastructure&descSize=16&descAlignY=55)

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=18&duration=3000&pause=1000&color=6C63FF&center=true&vCenter=true&width=600&lines=Building+production-grade+backend+systems;Designing+for+reliability%2C+concurrency%2C+and+failure;TypeScript+%C2%B7+Rust+%C2%B7+Cloudflare+Workers)](https://git.io/typing-svg)

<br>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/abdulsamed1)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:abdulsamedhamdy@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/abdulsamed1)

</div>

<br>

## About

Software engineer focused on **backend engineering**, **distributed systems**, and **production reliability**. I build APIs and services that stay correct under concurrency, failure, and real traffic — from multi-channel lead ingestion and tenant-isolated gateways to AI-powered automation.

I work primarily with **TypeScript/Node.js**, **Rust**, **Cloudflare Workers**, **PostgreSQL**, **Redis**, and **Docker**, with a bias toward idempotency, strong validation, observability, and clean failure handling.

Currently open to **backend, distributed systems, and AI infrastructure** roles.

<br>

## Tech Stack

<div align="center">

**Languages**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square)

**Backend & APIs**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![Cloudflare Workers](https://img.shields.io/badge/Cloudflare_Workers-F38020?style=flat-square&logo=cloudflareworkers&logoColor=white)
![REST](https://img.shields.io/badge/REST_APIs-005571?style=flat-square)
![WebSockets](https://img.shields.io/badge/WebSockets-010101?style=flat-square)
![BullMQ](https://img.shields.io/badge/BullMQ-DC382D?style=flat-square&logo=redis&logoColor=white)

**Data & State**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Durable Objects](https://img.shields.io/badge/Durable_Objects-F38020?style=flat-square&logo=cloudflare&logoColor=white)

**Infrastructure**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Docker Compose](https://img.shields.io/badge/Docker_Compose-2496ED?style=flat-square&logo=docker&logoColor=white)
![CI/CD](https://img.shields.io/badge/CI%2FCD-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

**AI & Automation**

![ElizaOS](https://img.shields.io/badge/ElizaOS-000000?style=flat-square)
![LLM Classification](https://img.shields.io/badge/LLM_Classification-412991?style=flat-square&logo=openai&logoColor=white)
![Telegram Bot API](https://img.shields.io/badge/Telegram_Bot_API-26A5E4?style=flat-square&logo=telegram&logoColor=white)

</div>

<br>

## Experience

| Role | Organization | Period | Focus |
|:-----|:-------------|:------:|:------|
| **Forward Deployed Engineer** | [Eagles](https://app.eagles-eg.online/) | Jun 2026 – Oct 2026 | CRM automation, webhook ingestion, lead routing |
| **Forward Deployed Engineer** | [Opran](https://opran.org/) · Self-employed | Nov 2025 – Jul 2026 | Tenant-isolated pricing gateway, billing, reliability |

<br>

## Impact

<table>
<tr>
<td align="center"><b>8,000+</b><br><sub>Skill files processed</sub></td>
<td align="center"><b>3,600+</b><br><sub>Skills catalogued</sub></td>
<td align="center"><b>100+</b><br><sub>Repositories aggregated</sub></td>
<td align="center"><b>~270 ms</b><br><sub>Booking scan latency</sub></td>
</tr>
</table>

<br>

## Selected Projects

### [Booking Automation](https://github.com/abdulsamed1/aegisflow) · `aegisflow`

**Cloudflare Workers · Durable Objects · SQL · Telegram Bot API**

- Scans an eight-week booking horizon at roughly 270 ms per request, running up to 24 parallel requests across 20 active jobs.
- Uses Durable Objects and SQL-backed state to prevent duplicate bookings during concurrent execution, verified with concurrency tests.
- Protects applicant data with AES-256-GCM field-level encryption, runtime-managed secrets, and administrative authentication.
- Handles failures with execution timeouts, adaptive backoff, circuit breakers, and fallbacks for browser and audio-transcription failures.

### [AI Aggregator](https://github.com/abdulsamed1/AI-skills-bank) · `AI-skills-bank`

**Rust · LLM Classification · CI/CD**

- Built a classification pipeline combining deterministic keyword filtering with LLM-based semantic classification across 8,000+ skill files.
- Aggregated 100+ repositories into a deduplicated catalog of 3,600+ skills, routable to 12+ AI-agent platforms.
- Added classification caching and cache metrics, jittered exponential backoff, circuit breaking, and schema-aware output validation.

### [Autonomous AI Agents](https://github.com/abdulsamed1/Intellichain) · `Intellichain`

**ElizaOS · TypeScript · Docker**

- Integrated an ElizaOS agent to extract wallet addresses and claim codes from social media replies and detect claim intent.
- Connected agent outputs to a four-stage workflow for validation, eligibility checks, authorization, and reward delivery.
- Added server-side claim validation to prevent duplicate redemptions, with tests covering access control, fulfillment, rewards, and gas usage.

<br>

## Education

**Bachelor's Degree in Management Information Systems** — New Cairo Academy · Cairo, Egypt · 2026

<br>

## GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=abdulsamed1&show_icons=true&theme=tokyonight&hide_border=true&bg_color=1a1a2e&title_color=6C63FF&icon_color=6C63FF&text_color=ffffff&ring_color=6C63FF" height="165" />
<img src="https://streak-stats.demolab.com?user=abdulsamed1&theme=tokyonight&hide_border=true&background=1a1a2e&ring=6C63FF&fire=6C63FF&currStreakLabel=6C63FF" height="165" />

</div>

<br>

<div align="center">

**Open to backend, distributed systems, and AI infrastructure roles.**

📧 [abdulsamedhamdy@gmail.com](mailto:abdulsamedhamdy@gmail.com) · 💼 [LinkedIn](https://linkedin.com/in/abdulsamed1)

![Footer](https://capsule-render.vercel.app/api?type=waving&color=0:1a1a2e,100:16213e&height=100&section=footer)

</div>
