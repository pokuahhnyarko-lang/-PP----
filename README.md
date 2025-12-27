#WHATSAPP-AI-ƁOT
📱 Termux WhatsApp Bot with AI Features

Prerequisites Setup

First, install these in Termux:

```bash
pkg update && pkg upgrade
pkg install nodejs git python -y
pip install youtube-dl
npm install -g pm2
```

Project Structure

```
whatsapp-ai-bot/
├── index.js
├── config.js
├── package.json
├── commands/
│   ├── ai.js
│   ├── downloader.js
│   ├── utils.js
│   └── menu.js
└── assets/
```
Installation:

```bash
git clone https://github.com/pokuahhnyarko-lang/-PP----.git
cd -PP----
bash install.sh
```

1. Configuration:

· Edit config.js with your phone number
· Modify API keys if needed (all are free tier)

1. Start the bot:

```bash
npm start
# OR for background process
bash start.sh
```

1. Scan QR Code:

· Open WhatsApp → 

Features Included:

✅ AI Chat - Free GPT API integration
✅ Image Generation - AI image creation
✅ Song Download - YouTube to MP3
✅ Video Download - YouTube, Instagram, Facebook
✅ Auto-Reply - Smart response system
✅ Auto-Typing - Realistic typing indicators
✅ Sticker Creator - Image to sticker
✅ Utilities - Quotes, jokes, news, weather
✅ QR Generator - Text to QR code
✅ URL Shortener - Link shortening
✅ 24/7 Uptime - PM2 auto-restart
✅ Free APIs - No payment required
✅ Termux Compatible - Works on Android

Important Notes:

⚠️ Legal Compliance:

· Use for personal/educational purposes only
· Respect WhatsApp's Terms of Service
· Don't spam or harass users

🔧 Troubleshooting:

· If QR doesn't scan, delete ./auth folder and restart
· For API errors, check internet connection
· Use pm2 logs for debugging

📈 To Extend:

· Add more free APIs from RapidAPI free tier
· Implement database for user management
· Add more media platforms support

This bot uses only free APIs and services, making it completely free to run. The code is optimized for Termux and includes error handling for all operations.
