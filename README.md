# Telegram Multi-Model AI Chatbot (n8n)

A Telegram chatbot built in n8n that has several AI models embedded behind one chat.

## What it does
- Reads messages sent to the bot on Telegram
- Lets you choose a model by starting your message with "using meta:" or "using deepseek:"
- Answers directly with a default model when you don't pick one
- Remembers the conversation using n8n Simple Memory
- Sends the reply back to the Telegram chat

## Tools used
n8n (self-hosted with Docker), Telegram Bot API, OpenRouter, ngrok

## How to use
1. Import telegram_ai_bot.json into n8n
2. Add your own credentials for Telegram and OpenRouter
3. Activate the workflow and message the bot
