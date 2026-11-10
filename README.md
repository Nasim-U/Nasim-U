# Nasim Uddin

I am a data scientist and software engineer in the UK. I build SQL pipelines, reporting dashboards, MCP servers for AI agents, and internal web tools.

## What I work on

I help engineering, finance, and operations teams replace manual spreadsheet work with tested software:

- Scheduled data pipelines and SQL models that reconcile billing, webhook, and product events.
- Reporting dashboards with clear definitions for revenue, retention, and operational metrics.
- Model Context Protocol servers and workflow automations with read-only database access and evaluation suites.
- Full-stack internal web apps for account health, operational triage, and filtered data exports.

## Public projects

These repositories show how I structure data warehouses, agent tools, and internal web applications:

- [`metricpulse-bi`](https://github.com/Nasim-U/metricpulse-bi) is a SaaS revenue and retention warehouse built with Python and DuckDB, with a SQLite fallback. It runs SQL staging and mart models, quarantines malformed webhook rows, checks z-score churn spikes, and serves a web dashboard with a read-only SQL explorer.
- [`opsflow-mcp`](https://github.com/Nasim-U/opsflow-mcp) is a Model Context Protocol server built with Node.js and `node:sqlite`. It gives AI clients read-only SQL access, dataset freshness checks, weekly variance digests, and a browser-based JSON-RPC inspector with an 18-case evaluation suite.
- [`signalstream-hq`](https://github.com/Nasim-U/signalstream-hq) is an internal account-health web app built with Node.js and SQLite in WAL mode. It ingests Stripe billing, product usage, and support webhooks idempotently, scores churn risk across four weighted factors, and exports filtered CSV reports.

## Core tools

I work day to day with `Python`, `SQL`, `DuckDB`, `PostgreSQL`, `BigQuery`, `SQLite`, `TypeScript`, `Node.js`, and `MCP`. For testing and delivery, I use `Pytest`, `Docker`, and `GitHub Actions`.
