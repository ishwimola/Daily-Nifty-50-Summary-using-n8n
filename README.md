# 🇮🇳 Daily Nifty 50 Market Summary Bot

Automated n8n workflow that fetches Indian stock market data every day at 3:30 PM IST and sends an email summary.

## ✨ Features
- 📅 Auto-schedules at 15:30 IST daily
- 📊 Fetches Nifty 50 closing data from Yahoo Finance
- 🔢 Calculates change points & percentage
- 🧮 Auto-detects Bullish/Bearish sentiment
- 📧 Email summary delivered via Gmail

## 🛠 Tech Stack
- n8n (open-source workflow automation)
- Yahoo Finance API (free, no key required)
- Gmail OAuth2

## 🚀 Quick Start

### Prerequisites
1. Self-hosted or cloud n8n instance
2. Gmail account (OAuth2 configured)
3. Internet access

### Setup Steps
1. Import `workflow.json` into n8n
2. Configure Gmail credential in n8n
3. Set Schedule Trigger to `15:30` / `Asia/Kolkata`
4. Click "Execute Workflow" to test

## 📁 Files Included
| File | Purpose |
|------|---------|
| `workflow.json` | Exported n8n workflow |
| `README.md` | This documentation |

## ⚠️ Important Notes
- Remove all credentials before committing to GitHub
- Use environment variables for sensitive data
- Test before setting schedule to production

## 🤝 Contributing
Feel free to fork, modify, and share improvements!

