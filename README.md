# SoulSync – Telegram Mood Bot

SoulSync is a Telegram chatbot built using **n8n** and **Gemini AI**.  
It detects the user’s mood and replies with supportive messages, short stories, and playlist links.

## Features
- Mood detection: happy, sad, bored, good, normal
- Empathetic AI responses
- Story generation for sad moods
- Playlist/video suggestions
- Telegram Bot integration

## How It Works
1. User sends a message in Telegram
2. Message is sent to Gemini AI via HTTP request
3. Gemini returns structured JSON response
4. n8n formats the message
5. Bot replies in Telegram

## Tech Stack
- n8n (workflow automation)
- Telegram Bot API
- Google Gemini API
