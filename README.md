# All Trading Bots Architecture

Architecture documentation for 4 autonomous trading bots across Indian equities, US markets, and crypto.

**Live site:** [https://vadiraj1998.github.io/All-Trading-Bots-Architecture/](https://vadiraj1998.github.io/All-Trading-Bots-Architecture/)

## Bots

- **Nifty Bot** — Zerodha F&O · ORB · Breakout · Mean Reversion · 3 Instances (1 Live, 2 Dry)
- **US Bot** — IBKR · Earnings Momentum · Spot + Options · 51 Symbols (Dry Run)
- **Crypto Spot** — Binance · AI-Ranked Weekly Selection · 30 Pairs (Dry Run)
- **Crypto Futures** — Binance Futures · 3x Leverage · Long + Short (Dry Run)

## Infrastructure

- Oracle ARM Free Tier · Ubuntu 22.04 · ₹0/month
- Local AI: Ollama · Llama 3.1 8B
- Alerts: Telegram + Email
- Token Auth: Cloudflare Worker (Zerodha auto-token)

Built & maintained by **Vadiraja Tantri M S**
