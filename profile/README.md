# Uproc
All-in-one business automation platform. Modular applications automate documents, finance, sales, data and operations. Each module handles one concrete business function and is activated as needed.
The platform comprises 37 modular applications. It supports cloud multi-tenant deployment and dedicated single-tenant instances. Interfaces are available in English, Spanish and Catalan.
🔗 Website: https://uproc.io | 📄 Docs: https://docs.uproc.io | 🔍 Tools catalog: https://uproc.io/applications/data-validation/tools

## What the platform does
| Area | Capabilities |
|---|---|
| 📄 Documents | Multichannel ingest (email/webhook), OCR classification & routing, PDF/A conversion, merge, batch numbering, archiving, multi-recipient e-signature, document generation from templates/audio/forms |
| 💶 Finance | Supplier invoice OCR + ERP sync, sales invoicing, tax compliance, debt tracking, bank reconciliation, investment analysis |
| 📈 Sales | CRM lead pipeline, lead prospecting & discovery, lead intelligence enrichment, multichannel campaign automation (email/WhatsApp/voice), editorial engine (AI articles to WordPress), market signals |
| 🗄️ Data | No-code data management tables, 469 data-process tools, ETL data sync, natural-language data chatbot, file transfers (SFTP/S3/Dropbox/Drive) |
| 🛠️ Operations | Omnichannel customer care (web/email/WhatsApp/Telegram with AI agent), email assistant, order tracking & ingest, inventory planning, approval workflows, process visibility, form generator |
| ⚖️ Legal & HR | Case lifecycle, contract lifecycle, candidate evaluation |

## Automate with your stack
| 📦 Repo | Description |
|---|---|
| [uproc-n8n](https://github.com/uproc-io/uproc-n8n) | n8n integration for Uproc — improve your data with our tools |
| [uproc-zapier](https://github.com/uproc-io/uproc-zapier) | Zapier integration for Uproc — improve your data with our tools |
| [uproc-make](https://github.com/uproc-io/uproc-make) | Make integration for Uproc — improve your data with our tools |
| [uproc-cli](https://github.com/uproc-io/uproc-cli) | Uproc CLI — authenticate, query data, and run business workflows from the terminal |

## For AI agents
Uproc ships a native MCP server (JSON-RPC) with business-action tools, semantic shortcuts (module.collection.action) and the data-process tool catalog. Works with Claude Code, OpenCode, Cursor, Codex and any MCP client.
The server exposes business-action tools for automated workflows. Clients connect via standard JSON-RPC endpoints.
🤖 Read the integration guide: https://docs.uproc.io

## Get started
1. Create an account at https://uproc.io
2. Pick a surface to run Uproc. Install via Homebrew tap or Scoop bucket, or use the web dashboard.
3. Automate with your stack using the n8n, Zapier, Make or CLI integrations.
The CLI supports authentication and direct data queries.
📧 Contact: support@uproc.io
