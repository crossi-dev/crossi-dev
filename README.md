<h1 align="center">Hi, I'm Charles 👋</h1>

<p align="center">
  <b>I ship real products with Claude Code — MCP servers and AI agents. Velora, a 61-tool production MCP server, is my proof of work. Open to my first role (part-time OK).</b>
</p>

<p align="center">
  <a href="https://cv.somosvelora.com"><img src="https://img.shields.io/badge/Portfolio-cv.somosvelora.com-22c55e?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio" /></a>
  <a href="https://somosvelora.com/developers"><img src="https://img.shields.io/badge/Live_MCP-somosvelora.com%2Fdevelopers-6366f1?style=for-the-badge&logo=anthropic&logoColor=white" alt="Live MCP" /></a>
  <a href="mailto:gestiones@somosvelora.com"><img src="https://img.shields.io/badge/Contact-gestiones@somosvelora.com-2563eb?style=for-the-badge&logo=maildotru&logoColor=white" alt="Email" /></a>
</p>

---

### 🛠️ What I do

I build and ship software with Claude Code — **MCP tools, AI agents, integrations**, and the unglamorous bug-fixes that keep real products moving. Fast, scoped, and verified.

The way I work is the way I prove it: I send real fixes upstream to the open-source projects I use. Runtime-verified, minimal-diff, tied to a real issue. The list below is public and checkable.

If something on your stack is stuck, broken, or just sitting in the backlog — that's the work.

### 🔀 Recent open-source contributions

Real PRs to third-party projects — every link is live and verifiable.

**Merged ✅**

- [`0xMassi/webclaw#59`](https://github.com/0xMassi/webclaw/pull/59) — accept numeric MCP params sent as strings *(Rust · web-extraction MCP server)*
- [`dgtlmoon/changedetection.io#4220`](https://github.com/dgtlmoon/changedetection.io/pull/4220) — extract `<title>` from pages with large `<head>` sections *(Python · 25k★ change-monitoring tool)*

**Open / in review 🔁**

- [`PeculiarVentures/x509#142`](https://github.com/PeculiarVentures/x509/pull/142) — harden GeneralizedTime to whole seconds in cert/CRL generators *(TypeScript · X.509 crypto)*
- [`encoredev/encore#2484`](https://github.com/encoredev/encore/pull/2484) — update deprecated GitHub Actions to current versions *(Go · backend framework)*
- [`RBND-studio/flows-sdk#704`](https://github.com/RBND-studio/flows-sdk/pull/704) — keep `PathnameProvider` mounted so changing `userId` doesn't break hook count *(React)*
- [`next-safe-action/next-safe-action#459`](https://github.com/next-safe-action/next-safe-action/pull/459) — accept safe actions directly in the `form` action prop *(TypeScript types)*
- [`lukevella/rallly#2436`](https://github.com/lukevella/rallly/pull/2436) — allow changing timezone on polls with no votes yet *(Next.js)*
- [`formkit/tempo#84`](https://github.com/formkit/tempo/pull/84) — handle locales with an existing Unicode extension (e.g. `ar-u-nu-arab`) *(date/i18n lib)*
- [`relaticle/custom-fields#167`](https://github.com/relaticle/custom-fields/pull/167) — resolve dependent fields to fix a strict-mode crash *(Laravel/Filament)*
- [`orhun/halp#403`](https://github.com/orhun/halp/pull/403) — migrate HTTP client to `ureq` v3 so the crate builds from source again *(Rust)*
- [`logchimp/logchimp#1789`](https://github.com/logchimp/logchimp/pull/1789) — enforce ownership in the comment destroy handler *(Node · auth fix)*
- [`velobase/velobase-harness#31`](https://github.com/velobase/velobase-harness/pull/31) — stop baking `.env` secrets into Docker image layers *(security)*
- [`tconbeer/textual-fastdatatable#153`](https://github.com/tconbeer/textual-fastdatatable/pull/153) — forward `render_markup` in the tooltip path to fix a JSON crash *(Python)*
- [`terminalwire/ruby#25`](https://github.com/terminalwire/ruby/pull/25) — unknown command should exit 1 and write to stderr *(Ruby/Rails)*

> Full list: [PRs authored by `crossi-dev`](https://github.com/pulls?q=is%3Apr+author%3Acrossi-dev+archived%3Afalse).

### 🚀 Featured project — Velora

The proof I can ship the hard stuff. **[Velora](https://cv.somosvelora.com)** is an AI-native, multi-agent commerce platform running in production on Google Cloud — a Supervisor that coordinates specialized agents (sales, payments, invoicing, shipping) which talk to *other companies'* agents over an open **A2A (Agent-to-Agent)** protocol.

- **Commerce end-to-end in chat** — product → sale → payment link → receipt → invoice → shipment
- **A multi-agent system** — each agent carries its own Ed25519 cryptographic identity over a shared A2A bus
- **An MCP server** — exposes operations (sales, payments, fiscal, logistics) to any MCP client, with per-tenant auth
- **Real integrations** — MercadoPago payments, ARCA/AFIP e-invoicing (real CAE), and Meta WhatsApp Cloud API, live in production; Andreani logistics integrated in sandbox
- **Production hardening** — hexagonal architecture, multi-tenant isolation, idempotent money operations, audit logging

Public companions: **[velora-mcp](https://github.com/crossi-dev/velora-mcp)** (the MCP server) · **[velora-track3](https://github.com/crossi-dev/velora-track3)** (A2A interoperability layer, Google AI Agents Challenge) · **[latam-tools](https://github.com/crossi-dev/latam-tools)** (Argentina CUIT validation + AFIP QR, pure MCP tools).

> **Built with** Claude Code · **Powered by** Google Cloud + Vertex AI (Gemini).

### 🔎 Also shipped — Veripóliza

**[Veripóliza](https://poliza-demo-901300139957.us-central1.run.app)** is an insurance certificate-of-coverage PDF verification engine. It sits between two APIs — one hands over certificate PDFs, one receives the extracted data — and replaces the manual step of retyping certificate fields.

- **Reads certificate PDFs → structured, validated JSON** — policy number, coverage dates, and each insured person's name and DNI
- **A Gemini model-consensus pipeline** on Google Cloud Run (scale-to-zero)
- **Proven on real data** — extracts 5/5 insured correctly from a real Sancor Seguros accident-coverage certificate, matching ground-truth policy number, coverage dates, and every name + DNI

Public repo: **[veripoliza](https://github.com/crossi-dev/veripoliza)** · **[Live demo](https://poliza-demo-901300139957.us-central1.run.app)**.

> **Built with** Claude Code · **Powered by** Google Cloud (Gemini).

### 🔐 Also built — nanoclaw (security-focused Teams agent for Outlook)

**nanoclaw** is a Microsoft Teams agent that gives employees a natural-language interface over their Outlook inbox and calendar. Mention `@nanoclaw` in a chat and it reads mail, reads the calendar, drafts emails, and creates events — always asking for explicit confirmation before any write.

- **Brain:** Claude via a tool-use loop; official Microsoft 365 Agents / Teams SDK; the `olk` Outlook CLI for mail and calendar access
- **Security engineering:** fail-closed allow-list, a write-confirmation gate on every send/create, an untrusted-data envelope around all tool results, a SHA-256-pinned binary, and secrets in GCP Secret Manager
- **Hosting:** Google Cloud Run with encrypted token persistence

> Status: built, private repository — an architecture and security piece, not a public demo (available on request).

> **Built with** Claude Code · **Powered by** Claude (Anthropic) + Google Cloud.

---

<p align="center"><i>Need something shipped? <a href="mailto:gestiones@somosvelora.com">gestiones@somosvelora.com</a> · <a href="https://cv.somosvelora.com">cv.somosvelora.com</a></i></p>
