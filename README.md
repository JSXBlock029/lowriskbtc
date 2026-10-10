### Hi, I build trading systems, automation and APIs in Python

Most of what's here started as tools I needed: bots that trade prediction markets and crypto, scanners that watch new tokens, and automation that removes repetitive work. The Python projects below have test suites that run in CI, and the trading ones are built paper-first with explicit safety gates.

**Featured**

| Project | What it is |
|---|---|
| [polymarket-bot](https://github.com/lowriskbtc/polymarket-bot) | Bot for Polymarket's 5 and 15 minute crypto markets: rule-based strategies, a pure-Python ML model and reinforcement-learning gates behind a Flask dashboard |
| [ai-decision-engine-api](https://github.com/lowriskbtc/ai-decision-engine-api) | FastAPI service for risk-scored decisions: hashed API keys, Stripe billing, JSON or SQLite storage, 73 tests on both backends |
| [hyperliquid-pro](https://github.com/lowriskbtc/hyperliquid-pro) | Self-hosted Hyperliquid terminal with a paper-first scalping stack and optional local-LLM trade judging |
| [solseller](https://github.com/lowriskbtc/solseller) | Solana trading terminal over Jupiter with a server-side take-profit / stop-loss executor and exact bonding-curve math |
| [solana-scanner](https://github.com/lowriskbtc/solana-scanner) | Memecoin scanner that scores new tokens and rotates across free LLM providers |
| [docx-desk](https://lowriskbtc.github.io/docx-desk/) | Word document editor that runs entirely in the browser and keeps the original formatting ([live demo](https://lowriskbtc.github.io/docx-desk/)) |

**Tools I use**

Python, FastAPI, Flask, pytest, SQLite, Stripe, Playwright, TypeScript, Next.js, React, Tailwind, GitHub Actions, Solana and EVM tooling, local and hosted LLMs.

**How I work**

- Tests that are proven to catch bugs: each protection is broken on purpose to confirm a test fails.
- Secrets stay out of code; trading code defaults to paper mode and fails safe.

Site: [aig3nt.com](https://aig3nt.com)
