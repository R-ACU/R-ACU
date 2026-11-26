# Remo Lamm

Junior developer from Hanover, Germany. I build web apps, Windows tools and AI automations with Claude Code: I write the briefs, check every result with automated tests and independent reviews, and write down the limits.

**Portfolio:** [portfolio.remos.systems](https://portfolio.remos.systems/en) · **Contact:** [remolamm@icloud.com](mailto:remolamm@icloud.com)

## Products

| Project | What it is | Stack |
| :--- | :--- | :--- |
| [Spechy](https://github.com/R-ACU/spechy) | Open-source voice dictation for Windows: hold a key, speak, and the text lands in any app. 16 releases since September 2026. [Website](https://spechy.vercel.app) | Rust, Tauri, React |
| [SnipDrop](https://github.com/R-ACU/snipdrop) | Screenshot tool that pastes to fit the target: an image in a chat, a path in a terminal, a file in Explorer. [Website](https://snipdrop.app) | Rust, Tauri, React |

## Demos

Three working demos with invented data. Each one has a live version, a test suite and a documented security model.

| Project | What it shows | Tests | Live |
| :--- | :--- | :--- | :--- |
| [Inquiry CRM](https://github.com/R-ACU/inquiry-crm) | Next.js 16 and Supabase with Row Level Security, plus an AI assistant that drafts but never decides | 526 automated tests, 42 browser tests | [English](https://inquiry-crm-demo.vercel.app) · [German](https://anfragen-crm.vercel.app) |
| [Inbox assistant](https://github.com/R-ACU/inbox-assistant) | n8n and Claude sort mail, check invoices to the cent and draft replies that only go out after a click | 356 automated tests, 47 browser tests | [English](https://inbox.remos.systems) · [German](https://demo.remos.systems) |
| [Product data checker](https://github.com/R-ACU/product-data-checker) | Python, pandas and DuckDB SQL clean a messy supplier list and check every number against the source | 272 tests, 51 browser tests | [German](https://produktdaten-pruefer.vercel.app) |

## How I work

- The AI drafts, a person decides. Nothing in these demos acts without approval.
- Every security claim has a test. Each `SECURITY.md` lists the threats, the protection and the test that proves it.
- Known limits are written down in the README, not hidden.
