# Telegram Proposal & Project Writer Bot

## Overview
Bot helps users generate proposals and project drafts using OpenAI GPT via Telegram.

## Features
- Multi-step conversation: type, topic, key details
- Generates structured draft (Intro, Objectives, Methodology, Conclusion)
- Replies with text and downloadable `.docx` file

## Tech Stack
- Python, `python-telegram-bot`
- `openai` for content generation
- `python-docx` for document export
- Flask for webhook handling
- Docker & Heroku-ready deployment

## Setup

### 1. Create bot & get tokens
- Telegram bot token from BotFather
- OpenAI API key
- Public URL for webhook (via Render, Heroku, or ngrok for dev)

### 2. Install dependencies
```bash
pip install -r requirements.txt
