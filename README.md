# Crypto Grid

A multi-chart trading dashboard in a single HTML file. Open `index.html` in a browser — no build step, no server, no account.

## Features

- **Up to 16 charts** in a grid (1, 2, 4, 6, 8, 10, 12, 14 or 16), drag to reorder, fullscreen any chart
- **Markets:** Binance Spot & Futures, Hyperliquid TradFi (HIP-3, e.g. `xyz:GOLD`, `xyz:NVDA`) and Twelve Data (gold, silver, stocks, ETFs, forex)
- **Intervals** from 1m to 12M (3M and 12M are built from monthly candles)
- **Drawing tools:** horizontal line, trend line, channel, Fibonacci (custom levels per drawing), rectangle, brush, eraser
- **Magnet** snapping to high / low / open / close (hold Ctrl to toggle)
- **Moving averages:** up to 4 per chart (EMA, SMA, HMA)
- **Risk calculator:** position size and 1R / 2R / 3R targets from entry, stop and amount at risk
- **Export / import** drawings (CSV + JSON backup), lock and hide drawings, inverted price scale

Everything (layout, drawings, settings) is saved in your browser's `localStorage`. Duplicate the file under another name (e.g. `scalping.html`) to get a separate workspace with its own saved state.

## Keyboard shortcuts

| Key | Action |
| --- | --- |
| V | Cursor |
| H | Horizontal line |
| T | Trend line |
| C | Channel |
| F | Fibonacci |
| R | Rectangle |
| B | Brush |
| E | Eraser |
| L | Lock / unlock drawings |
| Delete | Delete selected drawing |
| Ctrl+Z | Undo last drawing |
| Esc | Back to cursor / exit fullscreen |

## Twelve Data (optional)

Needed only for traditional markets with long history. Get a free key at [twelvedata.com](https://twelvedata.com/) and paste it in the **Twelve Data** panel. The key is stored only in your browser and is never included in the file. The free plan allows 8 requests per minute and 800 per day.

## Built with

[TradingView Lightweight Charts](https://github.com/tradingview/lightweight-charts) v4.2.0 (loaded from jsDelivr).

## Disclaimer

For charting and educational purposes only. Not financial advice.
