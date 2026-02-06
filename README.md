# telegram-ai-agent
# n8n Telegram AI Agent Bot

This project is an **n8n workflow** that connects a Telegram bot to an AI Agent (OpenRouter model).
Whenever a user sends a message to the Telegram bot, the workflow receives it, processes it with AI, and sends a reply back.

## Features
- Telegram message trigger
- AI Agent response (OpenRouter Chat Model)
- Automatic reply in Telegram

## Requirements
- n8n (Cloud or Self-hosted)
- Telegram Bot Token
- OpenRouter API Key

## Setup
1. Import the workflow JSON file into n8n.
2. Add Telegram credentials (Bot Token).
3. Add OpenRouter credentials (API Key).
4. Select your preferred model inside the OpenRouter node.
5. Activate the workflow.

## Workflow Logic
Telegram Trigger → AI Agent (OpenRouter) → Send Message (Telegram)

## Notes
- Do not upload your API keys inside the workflow JSON.
- Use n8n Credentials to store tokens securely.

## Author
Created by [hasti rostami]
