# 📰 Daily News Automation using n8n

An automated news delivery workflow built with **n8n**, **Times of India RSS**, and **Telegram**.

The workflow automatically fetches the latest news headlines, formats the top 10 headlines into a morning bulletin, and sends the message to a Telegram channel.

## 🚀 Workflow

Schedule Trigger (7:00 AM)
        ↓
Times of India RSS Feed
        ↓
Latest 10 Headlines
        ↓
Aggregate Headlines
        ↓
Format News Summary
        ↓
Format Telegram Message
        ↓
Telegram Channel

## ✨ Features

- ⏰ Runs automatically every day at 7:00 AM
- 📰 Fetches headlines from Times of India RSS
- 🔟 Selects the latest 10 headlines
- 📝 Automatically formats the news summary
- 📲 Sends the bulletin to Telegram
- ✅ Includes success handling
- ❌ Includes error handling

## 🛠️ Technologies

- n8n
- RSS Feed
- Telegram Bot
- JavaScript
- HTML

## 📁 Project Structure

n8n-daily-news-automation/
│
├── workflows/
│   └── TOI_News_to_Telegram.json
│
├── screenshots/
│
├── README.md
└── .gitignore

## ⚙️ Setup

1. Import `TOI_News_to_Telegram.json` into n8n.
2. Configure your Telegram credentials.
3. Verify the Telegram channel/chat ID.
4. Test the workflow manually.
5. Set/verify the schedule for 7:00 AM.
6. Activate the workflow.

## 📸 Screenshots

Screenshots of the workflow and successful Telegram execution will be added here.

## ⚠️ Security

Do not upload Telegram bot tokens, API keys, passwords, or other credentials to GitHub.

## 📌 Workflow Status

- [x] Workflow created
- [x] Workflow exported
- [ ] Telegram credentials configured
- [ ] Workflow tested
- [ ] Screenshots added
- [ ] GitHub repository published

## 👨‍💻 Author

Mohit Mali