# Helix

Crypto paper-trading desk by [SonoJS](https://sonojs.com) / [Milad Joodi](https://github.com/MiladJoodi).

Live market data, a production-style trading terminal, and a fully simulated portfolio — no wallets, no real orders.

**Live:** https://miladjoodi.github.io/sonojs-crypto-01/

## Features

- Live price ticker and Binance spot WebSocket feed
- Trade terminal: chart, order book, trade tape, market/limit ticket
- Paper buy / sell / swap with % sizing, fee preview, and TP/SL alerts
- Markets table with favorites, gainers, and losers
- Portfolio equity, allocation, session stats, and fill history
- ⌘K command palette, price alerts, dark / light theme
- Home desk with pulse cards and 24h heat map

## Stack

- Vite + React 18 + TypeScript
- Zustand + TanStack Query
- lightweight-charts
- Binance, CoinGecko, CryptoCompare public APIs

## Routes

| Path | Description |
| --- | --- |
| `/` | Home desk |
| `/markets` | Market table |
| `/markets/:id` | Asset detail |
| `/trade` | Trading terminal |
| `/portfolio` | Holdings & PnL |
| `/history` | Paper fills |
| `/news` | Headlines |
| `/settings` | Preferences & reset |

## Getting started

```bash
npm install
npm run dev
