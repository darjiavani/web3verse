# Web3Verse 🌐⛓️

A single-page Web3 educational website built for the **Arbitrum Builder Pods** assignment.  
All 4 sections live in one HTML file — navigate without any page reload.

## Pages

| Page | What It Does |
|------|-------------|
| 🏠 **Home** | Landing page — hero with animated chain visual, 6 Web3 features, how blockchain works (4 steps), explore section 
<img width="1920" height="1080" alt="Screenshot (321)" src="https://github.com/user-attachments/assets/50880562-61e6-4bf9-8092-3c7be0867694" />
<img width="1920" height="1080" alt="Screenshot (321)" src="https://github.com/user-attachments/assets/69923af6-c444-41f2-a9f1-f8360ffaba42" />
<img width="1920" height="1080" alt="Screenshot (321)" src="https://github.com/user-attachments/assets/8bedc440-a7a6-409b-893c-865265ac7e4b" />
<img width="1920" height="1080" alt="Screenshot (321)" src="https://github.com/user-attachments/assets/8380087e-a4c5-4c3c-853a-a5a490381ec3" /> |
| 📚 **Concepts** | 4 side-by-side comparisons: Web2 vs Web3, Ethereum vs Bitcoin (table), Public vs Private Key, Blockchain vs Traditional DB |
| 📈 **Live Prices** | Real-time ETH, BTC, SOL, MATIC, ARB, ADA from CoinGecko API — 24h change with ▲/▼ arrows, sparklines, coin filter |
| ⛏️ **Block Simulator** | Real SHA-256 proof-of-work — mine Block 1, change its data, Block 2 breaks instantly (immutability demo) |

## How to Run

**Option 1 — Just open in browser:**
```
Double-click web3.html
```

**Option 2 — Local server (recommended for CoinGecko API):**
```bash
python -m http.server 8080
# Open http://localhost:8080
```

**Option 3 — VS Code Live Server** (right-click index.html → Open with Live Server)

## Tech Stack

- **Pure HTML / CSS / JavaScript** — zero dependencies, zero build step
- **Web Crypto API** (`crypto.subtle`) — real browser-native SHA-256
- **CoinGecko Public API** — no API key needed
- **Google Fonts** — Syne + Inter + JetBrains Mono

## Features Checklist

- ✅ 4 pages in 1 file — shared nav, no reloads
- ✅ Active page highlighted in navbar
- ✅ Fully responsive (mobile nav with hamburger)
- ✅ Green ▲ / Red ▼ arrows on price change
- ✅ Refresh button re-fetches live data
- ✅ Real SHA-256 mining (Web Crypto API)
- ✅ Block Valid / Block Invalid display
- ✅ Chain breaks when Block 1 data is changed
- ✅ Consistent dark design across all sections
- ✅ Footer: name, GitHub, batch on every page

## Known Issues

- CoinGecko free API has rate limits — if error appears, wait ~60s and refresh
- Mining speed depends on browser (SHA-256 is async, UI stays responsive)

---

Built by **Avani** · Arbitrum Builder Pods Batch 2025
