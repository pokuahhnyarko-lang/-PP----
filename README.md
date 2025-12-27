# -PP----
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
