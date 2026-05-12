# ⚔️ BASE FIGHTER

A retro pixel art fighting game built on Base. Single player vs AI, fully browser-based — no installs, no libraries, just one HTML file.

![Base Fighter Screenshot](screenshot.png)

## 🎮 Play

**[▶ Live Demo](https://base-fighter.vercel.app)**

## 🛡️ Security & GitHub Alerts
If you upload this to GitHub, you will likely get a "Secret Leak" alert. **This is normal for Firebase.**
- **The Fix**: Go to [Google Cloud Credentials](https://console.cloud.google.com/apis/credentials), edit your API key, and add a **Website Restriction** for your domain (e.g., `your-app.vercel.app/*`). This prevents others from using your billable resources.

## Controls

| Action | Key |
|--------|-----|
| Move Left | ← |
| Move Right | → |
| Jump | ↑ or Space |
| Punch | A |
| Kick | S |
| Block | D |

Mobile touch buttons included.

## Features

- **Global Leaderboard**: Cross-session rankings powered by Firebase.
- **Blockchain Sync**: Record your wins permanently on the Base Chain.
- Pixel art characters & arena
- Player vs AI with adaptive difficulty
- Health bars + round system + score tracker
- Zero dependencies — single `index.html`

## Built With

- HTML5 Canvas & Vanilla JavaScript
- Firebase (Leaderboard)
- Ethers.js (Base Chain)
- Deployed on [Vercel](https://vercel.com)

## 🔵 Base Integration

This app is registered as a BaseApp on Base.  
Builder Code tracks engagement and qualifies for [Base Builder Rewards](https://base.dev).

## Run Locally

```bash
git clone https://github.com/georgiakapodistria/base-fighter
cd base-fighter
# open index.html in your browser
```

---

Built by [@tzogirl](https://x.com/tzogirl) · Powered by Base
