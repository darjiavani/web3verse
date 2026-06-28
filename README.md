# Web3Verse 🌐⛓️

A single-page Web3 educational website built for the **Arbitrum Builder Pods** assignment.  
All 4 sections live in one HTML file — navigate without any page reload.

## Pages

| Page | What It Does |
|------|-------------|
| 🏠 **Home** | Landing page — hero with animated chain visual, 6 Web3 features, how blockchain works (4 steps), explore section|
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

## screenshots 
## HOMEPAGE
<img width="1920" height="1080" alt="Screenshot (321)" src="https://github.com/user-attachments/assets/0fd8577e-542a-4e2d-a3f4-953013a894ef" />
<img width="1920" height="1080" alt="Screenshot (322)" src="https://github.com/user-attachments/assets/297966b1-2d31-4be4-8cf7-a8b12f29c80f" />
<img width="1920" height="1080" alt="Screenshot (323)" src="https://github.com/user-attachments/assets/858351e8-eff6-4fa2-83f2-231138d288e4" />
<img width="1920" height="1080" alt="Screenshot (324)" src="https://github.com/user-attachments/assets/600770fc-cb09-41ac-84d3-9df5f260d56b" />

## CORECONCEPTS
<img width="1920" height="1080" alt="Screenshot (325)" src="https://github.com/user-attachments/assets/aa55c81f-998b-4cbc-b6f7-ede2fac44685" />
<img width="1920" height="1080" alt="Screenshot (326)" src="https://github.com/user-attachments/assets/6a4b574d-3c3f-4ce5-9e6e-250948528ead" />
<img width="1920" height="1080" alt="Screenshot (327)" src="https://github.com/user-attachments/assets/e98d796f-8623-41f1-b8f3-fbbcb06fc49d" />
<img width="1920" height="1080" alt="Screenshot (328)" src="https://github.com/user-attachments/assets/667ccecb-5f50-4e2c-aa33-cde7de47782e" />

## BLOCK SIMULATOR
<img width="1920" height="1080" alt="Screenshot (329)" src="https://github.com/user-attachments/assets/f74d66f5-020b-4f28-869a-e316634f153c" />
<img width="1920" height="1080" alt="Screenshot (330)" src="https://github.com/user-attachments/assets/46ff97e9-7bde-4629-b7a4-79b41e2d5c9b" />
---

Built by **Avani** · Arbitrum Builder Pods Batch 2025
