 n8n-weather-monitor-mailer-AI-AGENT
 n8n-daily-weather-gmail-agent

This project is a no-code automation workflow built with [n8n](https://n8n.io) that **fetches daily weather data from a website or API** and **emails the forecast to your Gmail inbox every morning**.


 Features

- ⏰ Runs automatically every morning using a Cron trigger
- 🌍 Fetches weather data (e.g., for Hubballi or any city)
- 📧 Sends the weather report to your Gmail
- 💬 Easy to customize for different locations, email addresses, or formats


 Tools & Tech

- [n8n](https://n8n.io) (self-hosted or cloud)
- Gmail API (via OAuth2)
- HTTP Request Node (to fetch weather)
- Cron Node (to run daily)

---

Workflow Overview

1. Cron → Triggers every morning (e.g., 7 AM IST)
2. HTTP Request → Calls weather API or scrapes weather site
3. Function → Formats the data into readable message
4. Gmail Node → Sends the email to your inbox
