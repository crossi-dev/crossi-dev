<h1 align="center">Hi, I'm Carlos 👋</h1>

<p align="center">
  <b>I build <a href="https://somosvelora.com">Velora</a> — AI-native, multi-agent commerce on an open agent-to-agent layer.</b>
</p>

<p align="center">
  <a href="https://somosvelora.com"><img src="https://img.shields.io/badge/Live-somosvelora.com-22c55e?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Live" /></a>
  <a href="mailto:gestiones@somosvelora.com"><img src="https://img.shields.io/badge/Contact-gestiones@somosvelora.com-2563eb?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <img src="https://img.shields.io/badge/Built%20with-Claude%20Code-D97757?style=for-the-badge&logo=anthropic&logoColor=white" alt="Built with Claude Code" />
</p>

---

### 🚀 Velora

Velora lets a business run from a chat. An AI Supervisor coordinates specialized agents
— sales, payments, invoicing, shipping, messaging — and they talk to *other companies'*
agents over an open **A2A (Agent-to-Agent)** protocol. Live in production at
**[somosvelora.com](https://somosvelora.com)**, on Google Cloud.

> Built with Claude Code as my pair-programmer. The product itself runs on Google Cloud + Vertex AI (Gemini).

### ✅ What I've built

- **Commerce end-to-end in chat** — product → sale → payment link → receipt → invoice → shipment.
- **A multi-agent system** — a Supervisor (owner) and a Companion (employee), plus sub-agents for sales, payments, logistics, fiscal and messaging.
- **An A2A agent network** — every agent carries its own Ed25519 cryptographic identity and coordinates over a shared bus.
- **An MCP server** — exposes the platform's operations (sales, payments, fiscal, logistics) to any MCP client, with per-tenant auth. Live at [tools.somosvelora.com](https://tools.somosvelora.com).
- **Real integrations** — MercadoPago, ARCA/AFIP e-invoicing, Andreani & PedidosYa, Meta WhatsApp Cloud API, Twilio SMS, Resend email.
- **Production hardening** — hexagonal architecture, multi-tenant isolation, idempotent money operations, audit logging on critical writes.
- **An async WhatsApp pipeline** — inbound messages enqueue to Cloud Tasks and ack immediately; a Customer Agent then handles the work.
- **An Android app** — built with Capacitor, with an offline queue that replays mutations idempotently after reconnect.

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

<p align="center"><sub>Argentina 🇦🇷</sub></p>
