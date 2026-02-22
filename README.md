# PolyTeleChecker
Telegram based Polymarket checker for new markets

Setup
-----
1. Create a Telegram bot via @BotFather and get the token.
2. Get your chat/channel ID (send a message to the bot, then visit
   https://api.telegram.org/bot<TOKEN>/getUpdates to find it).
3. Fill in the config block below (or set the env vars).

Install dependencies
--------------------
    pip install requests python-dotenv

Run
---
    python polymarket_notifier.py
