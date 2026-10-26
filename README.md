<h1 align="center">Hi, I'm Saeed Allam 👋</h1>
<h3 align="center">Backend Developer · Node.js · NestJS · TypeScript</h3>

<p align="center">
I build backend systems that stay correct under pressure: secure authentication, multi-tenant data,<br/>
background jobs, and APIs that are safe to retry.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/saeed-allam-076541370/"><img src="https://img.shields.io/badge/LinkedIn-Saeed_Allam-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:saeedaallam91@gmail.com"><img src="https://img.shields.io/badge/Email-Contact_Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <img src="https://komarev.com/ghpvc/?username=saeedallam&style=for-the-badge&color=0e75b6" alt="Profile views"/>
</p>

---

## 🛡️ Featured: [AgentGate](https://github.com/saeedallam/AgentGate)

**A runtime safety layer for AI agents.** The agent proposes an action (a refund, a message, a deployment); AgentGate decides whether that exact action is allowed, under what conditions, and controls its execution with an auditable record.

`NestJS (Fastify)` `TypeScript` `PostgreSQL` `Prisma` `Docker`

**Built so far**
- Multi-tenant organizations, agents and per-agent API credentials — keys shown once, only prefix + hash stored
- Argon2 password hashing, JWT auth, and an agent guard that rejects revoked keys and suspended agents
- Action registry, normalized `ActionRequest`, and a persisted execution lifecycle
- `Idempotency-Key` handling with an atomic claim, so a retried request can never refund twice
- Unit, HTTP and database integration tests

**Next:** deterministic policy engine (`ALLOW` / `DENY` / `REQUIRE_APPROVAL`), exact-action approvals, budgets, and an MCP adapter.

---

## 📌 More Projects

| Project | What it is | Stack |
|---|---|---|
| 🎓 [**E-Learning Backend**](https://github.com/saeedallam/elearning-backend) | Modular REST API: RBAC, courses & lessons, enrollment and progress tracking, Redis caching, background notifications, Swagger docs, Docker, automated tests | NestJS · PostgreSQL · Prisma · Redis · BullMQ |
| 💳 [**SubTrackr**](https://github.com/saeedallam/subtrackr-backend) | Subscription tracking: refresh-token lifecycle, plans & billing periods, scheduled renewals and expiration, usage tracking, analytics | NestJS · MongoDB · Prisma · Redis · BullMQ |

---

## 🛠️ Tech Stack

**Backend**
<br/>
<img src="https://skillicons.dev/icons?i=nodejs,nestjs,ts,js,express" alt="Backend"/>

**Databases & Infrastructure**
<br/>
<img src="https://skillicons.dev/icons?i=postgres,mongodb,redis,prisma,docker" alt="Databases and infrastructure"/>

**Tools**
<br/>
<img src="https://skillicons.dev/icons?i=git,github,linux,postman" alt="Tools"/>

---

## 🧠 How I Work

- **Correctness first** — idempotency, transactions and clear failure states before features
- **Security by default** — hashed secrets, least privilege, tenant isolation
- **Modular monolith** — clean module boundaries; split into services only when it pays off
- **Tested and documented** — every slice ships with tests and a README someone else can follow

---

<p align="center"><b>Open to backend roles and freelance API work — let's build something reliable.</b></p>
