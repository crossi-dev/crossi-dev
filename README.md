<h1 align="center">Hi, I'm Carlos 👋</h1>

<p align="center">
  <b>Developer building <a href="https://somosvelora.com">Velora</a> — an AI-native, multi-agent commerce platform.</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Builds%20with-Anthropic-D97757?style=for-the-badge&logo=anthropic&logoColor=white" alt="Builds with Anthropic" />
  <a href="mailto:gestiones@somosvelora.com">
    <img src="https://img.shields.io/badge/Contact-gestiones@somosvelora.com-2563eb?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
</p>

---

### 🚀 Velora — commerce you run by chatting

Velora turns a business into something you operate from a chat. An AI **Supervisor**
orchestrates a team of specialized agents that handle sales, payments, invoicing,
shipping and messaging — and they talk to *other companies'* agents over an open
**A2A (Agent-to-Agent)** protocol. Live in production on Google Cloud.

> 🤖 **Builds with Anthropic** — I engineer Velora with Claude Code as my pair-programmer.
> The product itself runs on Google Cloud + Vertex AI; Claude is how it gets built.

**Highlights**
- 🧠 **Multi-agent system** — a Supervisor (owner) + Companion (employee) + specialized
  sub-agents: Sales, Payments, Logistics, Fiscal, Messaging, Team.
- 🔌 **MCP server** — 45 tools across 13 packs, engine-agnostic: any AI client (Claude,
  Codex, Gemini) drives the same toolkit → [tools.somosvelora.com](https://tools.somosvelora.com)
- 🤝 **A2A interoperability** — agents authenticate with Ed25519 identity keys and
  coordinate across companies, not just inside one app.
- 🏗️ **Solid foundations** — hexagonal architecture (ports/adapters/use-cases),
  multi-tenant isolation, idempotent money operations, full audit trail.
- 📲 **WhatsApp-first** — customers and owners run the whole business from chat.

---

### 🛠️ Tech

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?style=flat&logo=tailwindcss&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat&logo=prisma&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Google Cloud](https://img.shields.io/badge/Google%20Cloud-4285F4?style=flat&logo=googlecloud&logoColor=white)
![Vertex AI](https://img.shields.io/badge/Vertex%20AI-4285F4?style=flat&logo=googlecloud&logoColor=white)
![Capacitor](https://img.shields.io/badge/Capacitor-119EFF?style=flat&logo=capacitor&logoColor=white)

---

### ✅ What I've built in Velora

- **End-to-end commerce in chat** — product → sale → payment link → receipt → invoice → shipment, all from a conversation.
- **A2A agent network (v0.3.0)** — each agent has its own cryptographic identity (Ed25519) and coordinates over a shared bus.
- **MCP toolkit (45 tools)** — exposed to any AI engine over HTTP, with per-tenant auth.
- **Real integrations** — MercadoPago (payments), ARCA/AFIP (electronic invoicing), Andreani & PedidosYa (logistics), Meta WhatsApp Cloud API, Twilio SMS, Resend email.
- **Owner / employee roles** — two distinct AI assistants (Supervisor & Companion) with role-based access control.
- **Async WhatsApp pipeline** — inbound messages on Cloud Tasks feeding a dedicated Customer Agent, sub-second webhook acks.
- **Mobile app** — Android via Capacitor, with an offline queue that replays mutations idempotently after reconnect.

---

<p align="center"><sub>Argentina 🇦🇷 · building in public</sub></p>
