# NEXUS AI TRADER

A mobile-first XAUUSD M5 trading application prototype.

## Current status

This repository currently contains a front-end prototype only. It does not connect to MetaTrader 5, receive live prices, or place orders. Any sample graphics or labels are illustrative, not live account data or verified trading signals.

## Planned architecture

1. Mobile web dashboard
2. Python backend for market data, strategy evaluation and risk checks
3. MT5 execution service on a supported Windows environment
4. Demo-only integration, backtesting and safety testing before any live use

## Proposed safety settings

- Demo mode first
- Planned risk: 1% per trade (not a guaranteed maximum loss)
- One open position at a time
- Proposed daily loss lockout: 2%
- Proposed maximum: 3 trades per day
- Emergency stop
- Never store broker passwords, API keys, or account numbers in this repository

## Run

Open `index.html` in a browser, or enable GitHub Pages in repository Settings.

## Roadmap

- [x] Initial mobile dashboard prototype
- [ ] Strategy specification and historical-data validation
- [ ] Position sizing and risk controls with tests
- [ ] Backtesting with spread, commission and slippage
- [ ] MT5 demo execution adapter
- [ ] Monitoring, logs and failure-safe controls

This is experimental software, not investment advice or a promise of profitability. Never connect it to a live account until it has been independently reviewed and extensively demo-tested.
