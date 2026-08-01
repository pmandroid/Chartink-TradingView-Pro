# Chartink-TradingView-Pro
Adds a one-click menu to every Chartink stock symbol — open TradingView Chart, TradingView Stats, or Screener.in instantly.

A production-quality, modular Chrome Extension (Manifest V3) that turns every stock symbol on Chartink into a launchpad for deeper research — one hover, three destinations, zero copy-pasting.

Works across screener results, watchlists, related-stocks tables, and anything else Chartink's Vue.js frontend renders — without relying on column position or fragile CSS selectors, and without breaking when Chartink sorts, paginates, or filters the table.

What it does

Wherever Chartink shows a stock symbol, the extension adds a small "⋮" options menu next to it. Hover (or tap, on touch devices) to reveal three links, each opening in a new tab:

Option	Destination
Open TV Chart	https://www.tradingview.com/chart/?symbol=NSE:SYMBOL
Open TV Stats	https://in.tradingview.com/symbols/NSE-SYMBOL/
Open Screener.in	https://www.screener.in/company/SYMBOL/
