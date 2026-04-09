# 🏆 BetTracker — Sports Bet & Pool Tracker

A sleek, self-contained sports betting tracker and pool manager. One HTML file, zero backend, runs anywhere.

![BetTracker Screenshot](https://via.placeholder.com/900x500/0b0f14/d4a853?text=BetTracker+Dashboard)

## Features

- **Bet Tracking** — Log bets with sport, event, pick, odds (American), wager, and status. Auto-calculates payouts and implied probability.
- **Pool Manager** — Create and track Pick 'Em, Bracket, Survivor, Season-Long, and Confidence pools with inline scoring.
- **Dashboard** — Summary stats (ROI, win rate, units, P&L), cumulative P&L chart, and per-sport breakdown.
- **Bankroll Management** — Set starting bankroll, log deposits/withdrawals, track your balance in real time.
- **Live Tab** — View all pending bets in one place, ready for live score integration.
- **Persistent Storage** — All data saved to `localStorage`; survives refreshes and sessions.
- **Mobile Friendly** — Responsive layout with sidebar nav on desktop and tab bar on mobile.

## Quick Start

### Option 1: Open locally
Download `index.html` and open it in any modern browser. That's it.

### Option 2: Deploy to Vercel
1. Fork or clone this repo
2. Connect to [Vercel](https://vercel.com)
3. Deploy — zero config needed

### Option 3: GitHub Pages
1. Push to a GitHub repo
2. Go to **Settings → Pages → Source: main branch**
3. Your tracker is live at `https://yourusername.github.io/repo-name/`

## Tech Stack

| Layer | Tech |
|-------|------|
| UI | React 18 (CDN) |
| Charts | Recharts (CDN) |
| Styling | Vanilla CSS, custom properties |
| Fonts | DM Sans, Outfit, JetBrains Mono |
| Storage | localStorage |
| Build | None — single HTML file, Babel in-browser |

## File Structure

```
├── index.html      ← The entire app
├── vercel.json      ← Vercel routing config
└── README.md        ← You are here
```

## Data & Privacy

All data stays in your browser's `localStorage`. Nothing is sent to any server. Clear your browser data to reset.

---

Built by **Will Graves**
Use it in good health 🤝
Send feedback to [jwgraves21@gmail.com](mailto:jwgraves21@gmail.com)
