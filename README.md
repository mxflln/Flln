# ⚡ EdgeIQ — AI Real Estate Agent Platform

The unfair advantage for top agents. Real Claude AI generating personalised outreach, market intelligence, and transaction predictions.

---

## 🚀 Deploy to Vercel (5 minutes)

### 1. Get your Anthropic API key
- Go to https://console.anthropic.com
- Create an API key

### 2. Deploy
```bash
# Install Vercel CLI
npm i -g vercel

# Clone and deploy
cd edgeiq
npm install
vercel deploy
```

When prompted, add environment variable:
```
ANTHROPIC_API_KEY = your_key_here
```

Or deploy via GitHub:
1. Push this folder to a GitHub repo
2. Go to https://vercel.com → New Project → Import repo
3. Add `ANTHROPIC_API_KEY` in Environment Variables
4. Deploy ✓

### 3. Run locally
```bash
cp .env.local.example .env.local
# Add your API key to .env.local
npm install
npm run dev
# Open http://localhost:3000
```

---

## 🔥 Features
- **Lead Radar** — AI-scored leads ranked by transaction probability
- **Market Intel** — Live Brisbane suburb data with AI insights  
- **AI Outreach** — Real Claude generating personalised emails per lead
- **AI Strategy** — Tactical advice for winning each deal
- **Transaction Predictor** — Claude analyses all leads and predicts who transacts next

## 💰 Monetisation
- $500–$999/month per agent subscription
- White-label for agencies: $2,000–$5,000/month
- Acquisition target: realestate.com.au, Domain, PropTrack

---

Built with Next.js + Anthropic Claude API
