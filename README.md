<h1 align="center">Hi, I'm Charles 👋</h1>

<p align="center">
  <b>Senior Software Engineer at <a href="https://choreless.dev">Choreless</a> — software built and shipped fast, or your money back.</b>
</p>

<p align="center">
  <a href="https://choreless.dev"><img src="https://img.shields.io/badge/Choreless-choreless.dev-22c55e?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Choreless" /></a>
  <a href="mailto:charles@choreless.dev"><img src="https://img.shields.io/badge/Contact-charles@choreless.dev-2563eb?style=for-the-badge&logo=maildotru&logoColor=white" alt="Email" /></a>
</p>

---

### 🛠️ What I do

At [Choreless](https://choreless.dev) I build and ship software for teams that need it done — **MCP tools, AI agents, integrations**, and the unglamorous bug-fixes that keep real products moving. Fast, scoped, and verified.

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

The proof I can ship the hard stuff. **[Velora](https://somosvelora.com)** is an AI-native, multi-agent commerce platform running in production on Google Cloud — a Supervisor that coordinates specialized agents (sales, payments, invoicing, shipping) which talk to *other companies'* agents over an open **A2A (Agent-to-Agent)** protocol.

- **Commerce end-to-end in chat** — product → sale → payment link → receipt → invoice → shipment
- **A multi-agent system** — each agent carries its own Ed25519 cryptographic identity over a shared A2A bus
- **An MCP server** — exposes operations (sales, payments, fiscal, logistics) to any MCP client, with per-tenant auth
- **Real integrations** — MercadoPago, ARCA/AFIP e-invoicing, Andreani, Meta WhatsApp Cloud API
- **Production hardening** — hexagonal architecture, multi-tenant isolation, idempotent money operations, audit logging

Public companions: **[velora-mcp](https://github.com/crossi-dev/velora-mcp)** (the MCP server) · **[velora-track3](https://github.com/crossi-dev/velora-track3)** (A2A interoperability layer, Google AI Agents Challenge) · **[latam-tools](https://github.com/crossi-dev/latam-tools)** (Argentina CUIT validation + AFIP QR, pure MCP tools).

> **Built with** Claude Code · **Powered by** Google Cloud + Vertex AI (Gemini).

---

<p align="center"><i>Need something shipped? <a href="mailto:charles@choreless.dev">charles@choreless.dev</a> · <a href="https://choreless.dev">choreless.dev</a></i></p>
