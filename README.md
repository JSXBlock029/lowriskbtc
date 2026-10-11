<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/banner-light.svg">
  <img alt="lowriskbtc: trading systems, automation and APIs in Python" src="assets/banner-dark.svg" width="100%">
</picture>

<p align="center">
  <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white">
  <img alt="FastAPI" src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white">
  <img alt="Flask" src="https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white">
  <img alt="pytest" src="https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white">
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white">
  <img alt="Next.js" src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white">
  <img alt="Tailwind CSS" src="https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white">
  <img alt="Solana" src="https://img.shields.io/badge/Solana-9945FF?style=flat-square&logo=solana&logoColor=white">
  <img alt="Stripe" src="https://img.shields.io/badge/Stripe-635BFF?style=flat-square&logo=stripe&logoColor=white">
  <img alt="GitHub Actions" src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white">
</p>

### About

I build tools that trade, watch markets and remove repetitive work: bots for prediction markets and crypto, token scanners, a payments-ready API and browser automation. The projects below have test suites that run in CI, and the trading code is built paper-first with explicit safety gates.

### Featured projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/lowriskbtc/polymarket-bot">polymarket-bot</a></h4>
      Bot for Polymarket's 5 and 15 minute crypto markets: rule-based strategies, a pure-Python ML model and reinforcement-learning gates behind a Flask dashboard.<br><br>
      <a href="https://github.com/lowriskbtc/polymarket-bot/actions/workflows/ci.yml"><img alt="CI" src="https://github.com/lowriskbtc/polymarket-bot/actions/workflows/ci.yml/badge.svg"></a>
    </td>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/lowriskbtc/ai-decision-engine-api">ai-decision-engine-api</a></h4>
      FastAPI service for risk-scored decisions with hashed API keys, Stripe billing, and JSON or SQLite storage, tested on both backends.<br><br>
      <a href="https://github.com/lowriskbtc/ai-decision-engine-api/actions/workflows/ci.yml"><img alt="CI" src="https://github.com/lowriskbtc/ai-decision-engine-api/actions/workflows/ci.yml/badge.svg"></a>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/lowriskbtc/solseller">solseller</a></h4>
      Solana trading terminal over Jupiter with a server-side take-profit / stop-loss executor and exact bonding-curve math.<br><br>
      <a href="https://github.com/lowriskbtc/solseller/actions/workflows/ci.yml"><img alt="CI" src="https://github.com/lowriskbtc/solseller/actions/workflows/ci.yml/badge.svg"></a>
    </td>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/lowriskbtc/hyperliquid-pro">hyperliquid-pro</a></h4>
      Self-hosted Hyperliquid terminal with a paper-first scalping stack and optional local-LLM trade judging.<br><br>
      <a href="https://github.com/lowriskbtc/hyperliquid-pro/actions/workflows/ci.yml"><img alt="CI" src="https://github.com/lowriskbtc/hyperliquid-pro/actions/workflows/ci.yml/badge.svg"></a>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/lowriskbtc/solana-scanner">solana-scanner</a></h4>
      Memecoin scanner that scores new tokens and rotates across free LLM providers, failing over cleanly when one goes down.<br><br>
      <a href="https://github.com/lowriskbtc/solana-scanner/actions/workflows/ci.yml"><img alt="CI" src="https://github.com/lowriskbtc/solana-scanner/actions/workflows/ci.yml/badge.svg"></a>
    </td>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/lowriskbtc/docx-desk">docx-desk</a></h4>
      Word document editor that runs entirely in the browser and keeps the original formatting. Nothing is uploaded.<br><br>
      <a href="https://lowriskbtc.github.io/docx-desk/"><img alt="Live demo" src="https://img.shields.io/badge/live_demo-open-22d3ee?style=flat-square"></a>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/lowriskbtc/antirugdex">antirugdex</a></h4>
      Verifiable token launches on Solana: a Token-2022 fee token, an Anchor fair-sale program that seeds a Raydium pool and burns the LP, and an on-chain rug-risk grader. Verified end to end on devnet.<br><br>
      <a href="https://github.com/lowriskbtc/antirugdex/actions/workflows/ci.yml"><img alt="CI" src="https://github.com/lowriskbtc/antirugdex/actions/workflows/ci.yml/badge.svg"></a>
    </td>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/lowriskbtc/duck-store">duck-store</a></h4>
      Flask storefront with Stripe checkout, server-side pricing, buyer-only downloads and a password-protected admin, deployed on Vercel with Postgres.<br><br>
      <a href="https://duck-store.vercel.app"><img alt="Live site" src="https://img.shields.io/badge/live_site-open-22d3ee?style=flat-square"></a>
      <a href="https://github.com/lowriskbtc/duck-store/actions/workflows/ci.yml"><img alt="CI" src="https://github.com/lowriskbtc/duck-store/actions/workflows/ci.yml/badge.svg"></a>
    </td>
  </tr>
</table>

### How the code is checked

- **450+ automated tests** across nine repositories, running on every push with GitHub Actions.
- **Mutation-tested:** each protection was broken on purpose to confirm a test catches it.
- **Safe by default:** secrets stay out of code, trading defaults to paper mode, and anything ambiguous fails safe.

<p align="center">
  <a href="https://aig3nt.com"><img alt="Website" src="https://img.shields.io/badge/aig3nt.com-0f172a?style=for-the-badge&logo=googlechrome&logoColor=white"></a>
</p>
