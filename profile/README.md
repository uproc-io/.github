# Uproc

> **All-in-one business automation platform** — modular applications that automate documents, finance, sales, data and operations, powered by **469 data tools** and AI agents.

Uproc is a modular platform where each application handles one concrete business function (document ingest → classification → signing, invoicing, CRM, customer care, data pipelines…) and can be activated as needed. It runs on **400+ data processing tools** (validation, enrichment, lookups across company, person, finance, geographic, communication and more), a natural-language data chatbot, and AI copilots — all exposed through **REST API, CLI and MCP** so humans and AI agents can operate the same workflows.

🔗 **Website:** [uproc.io](https://uproc.io) · **Docs:** [docs.uproc.io](https://docs.uproc.io) · **Tool catalog & pricing:** [uproc.io/applications/data-validation/tools](https://uproc.io/applications/data-validation/tools)

## What the platform does

| Area | Capabilities |
|------|--------------|
| 📄 **Documents** | Multichannel ingest (email/webhook), OCR classification & routing, PDF/A conversion, merge, batch numbering, archiving, multi-recipient e-signature, document generation from templates/audio/forms |
| 💶 **Finance** | Supplier invoice OCR + ERP sync (Holded, Factura Directa, Invoice Ninja), sales invoicing, tax compliance (incl. VeriFactu), debt tracking, bank reconciliation, investment analysis |
| 📈 **Sales** | CRM lead pipeline, lead prospecting & discovery, lead intelligence enrichment, multichannel campaign automation (email/WhatsApp/voice), editorial engine (AI articles → WordPress), market signals |
| 🗄️ **Data** | No-code data management tables, **469-tool data-process catalog** (pay-per-use), ETL data sync, natural-language data chatbot, file transfers (SFTP/S3/Dropbox/Drive) |
| 🛠️ **Operations** | Omnichannel customer care (email/WhatsApp/Telegram + AI agent), email assistant, order tracking & ingest, inventory planning, approval workflows, process visibility, form generator |
| ⚖️ **Legal & HR** | Case lifecycle, contract lifecycle, candidate evaluation |

**Deployment:** Cloud (multi-tenant) or Private (dedicated instance, customer network/VPN).
**Languages:** English, Spanish, Catalan.

## Automate with your stack (public repositories)

| Repo | Description |
|------|-------------|
| [uproc-n8n](https://github.com/uproc-io/uproc-n8n) | Official n8n community node — the source of the node published at [n8n.io/integrations/uproc](https://n8n.io/integrations/uproc) |
| [uproc-make](https://github.com/uproc-io/uproc-make) | Make.com integration for Uproc |
| [uproc-zapier](https://github.com/uproc-io/uproc-zapier) | Zapier integration for Uproc |
| [uproc-cli](https://github.com/uproc-io/uproc-cli) | Go CLI — authenticate, query data and run business workflows from the terminal |
| [uproc-sdk-nodejs](https://github.com/uproc-io/uproc-sdk-nodejs) | Node.js client for the Uproc data quality API |
| [any-file](https://github.com/uproc-io/any-file) | Node.js library to copy files between storage sources (FTP, HTTP, S3, SSH, local…) |

## Self-hosted tools & open source

| Repo | Description |
|------|-------------|
| [screenshoter](https://github.com/uproc-io/screenshoter) | Puppeteer as a Dockerized HTTP service |
| [wappalyzer](https://github.com/uproc-io/wappalyzer) | Identify technology on websites |
| [wappalyzer-api](https://github.com/uproc-io/wappalyzer-api) | Wappalyzer, apified |
| [n8n-fork](https://github.com/uproc-io/n8n-fork) | Fair-code workflow automation platform with native AI capabilities |
| [uproc-homebrew](https://github.com/uproc-io/uproc-homebrew) | Homebrew tap for the Uproc CLI (`brew install`) |
| [scoop-bucket](https://github.com/uproc-io/scoop-bucket) | Scoop bucket for the Uproc CLI on Windows |

## For AI agents

Uproc ships a native **MCP server** (`/api/v1/external/mcp`, JSON-RPC) with ~170+ business-action tools, semantic shortcuts (`module.collection.action`) and the full data-process tool catalog (`data-process.search/tool/execute/batch`). It works out of the box with Claude Code, OpenCode, Cursor, Codex and any MCP client — see [docs.uproc.io](https://docs.uproc.io).

## Get started

1. Create an account at [uproc.io](https://uproc.io) (data-process has no license — pay per use)
2. Pick your surface: web app, CLI (`brew install uproc` / `scoop install uproc`), API or MCP
3. Automate with n8n, Make or Zapier using the integrations above

📮 Contact: [support@uproc.io](mailto:support@uproc.io)
