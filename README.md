# 🎮 Telegram Game Bot

Multiplayer Telegram mini-game bot with MongoDB integration. Built with Node.js and deployed on Render.

## 🚀 Features

- **Multiplayer gameplay** – Real-time game sessions
- **MongoDB database** – Persistent player data and achievements
- **Achievement system** – Track player progress
- **Auto-deployment** – Connected to Render for continuous delivery
- **24/7 uptime monitoring** – UptimeRobot keeps the bot active

## 🛠️ Tech Stack

- **Node.js** – Backend runtime
- **Telegraf** – Telegram Bot API framework
- **MongoDB** – Database for game state and user data
- **Express** – Web server for health checks
- **Render** – Hosting platform (free tier)

## 📦 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/gritsenko31/telegram-game-bot.git
   cd telegram-game-bot
Install dependencies:

bash
npm install
Create .env file with your credentials:

text
BOT_TOKEN=your_telegram_bot_token
MONGODB_URI=your_mongodb_connection_string
PORT=10000
Run the bot:

bash
node bot.js
🌐 Deployment
The bot is deployed on Render (free tier):

Live URL: https://telegram-game-bot-tbij.onrender.com/

Note: First request after inactivity may take ~20-30s to wake up

Deploy to Render
Fork this repo

Connect to Render

Set environment variables: BOT_TOKEN, MONGODB_URI

Deploy as Web Service

📝 Project Structure
text
telegram-game-bot/
├── bot.js              # Main bot logic
├── database.js         # MongoDB connection
├── multiplayer.js      # Multiplayer game logic
├── achievements.js     # Achievement tracking
├── package.json        # Dependencies
└── .gitignore          # Git ignore rules
🎯 How to Use
Open Telegram and search for your bot

Start the bot with /start

Follow the game instructions

Compete with other players in real-time

🔧 Development
This is a portfolio project demonstrating:

Telegram Bot API integration

Real-time multiplayer functionality

Database management with MongoDB

Cloud deployment and monitoring

AI-assisted development workflow


👤 Author
gritsenko31

GitHub: @gritsenko31

Portfolio: vibecodegames.org
