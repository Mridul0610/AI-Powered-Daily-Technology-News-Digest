# 🤖 AI-Powered Technology News Automation

An automated technology news briefing system built using **n8n, Google Gemini, JavaScript, and Telegram**.

This workflow automatically fetches the latest technology news, analyzes articles using Google Gemini, and delivers structured news briefings directly to Telegram.

## 🚀 Features

- Automatically fetches news from The Verge RSS feed every 23 hours.
- Selects the two latest articles.
- Extracts article content using Jina AI Reader.
- Uses Google Gemini to generate detailed news briefings.
- Highlights key facts, business impact, risks, and takeaways.
- Formats messages using JavaScript and HTML.
- Delivers automated briefings directly to Telegram.

## 🛠️ Tech Stack

- **n8n** – Workflow automation
- **Google Gemini** – AI-powered news analysis
- **The Verge RSS** – News source
- **Jina AI Reader** – Article extraction
- **JavaScript** – Data processing and formatting
- **Telegram Bot API** – News delivery

## ⚙️ Workflow

`Schedule Trigger → RSS Read → Limit to 2 Latest → HTTP Request → AI Agent → JavaScript Code → Telegram`

## 🔧 Setup

1. Import the workflow JSON into n8n.
2. Configure Google Gemini API credentials.
3. Connect your Telegram bot credentials.
4. Configure your Telegram Chat ID.
5. Test and activate the workflow.

## 🎯 Objective

To automate technology news collection and transform articles into simple, structured, AI-generated insights, saving time and keeping users updated on the latest developments.

## 👨‍💻 Author

**Mridul Sharma**

⭐ If you find this project useful, consider giving it a star!
