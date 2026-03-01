# Rudraksha - Personal Assistant Telegram Bot 🔥

Rudraksha is an AI-powered personal assistant Telegram bot created by Gaurav Pandey. It helps users with any task or question and responds strictly in the language of the user's current message.

## Features

✅ Replies in English or Hindi (Roman script) based on the user's message.  
✅ Professional, concise, and slightly humorous responses.  
✅ Uses Groq AI (LLaMA 3.3 70B) for natural conversation.  
✅ Maintains conversation history for context.  
✅ Friendly and engaging with emojis.  
✅ Typing indicator for realistic chat experience.  
✅ Easy setup with JSON-based conversation storage.  

## Install dependencies:

pip install telebot langdetect groq

Add your Telegram Bot Token and Groq API Key in bot.py:

TG_BOT_TOKEN = "YOUR_TELEGRAM_BOT_TOKEN"
GROQ_API_KEY = "YOUR_GROQ_API_KEY"

Run the bot:
```bash
python bot.py
```

## Usage

Start the bot in Telegram using /start.
Send any message in English or Hindi (Roman script).
Rudraksha will reply promptly, following its persona rules.

## Notes

Conversation history is stored in Conversation.json.
The bot strictly replies in the current message's language, ignoring previous messages' languages.

## Contributing

Feel free to fork the project, add features, or improve the bot's responses.
