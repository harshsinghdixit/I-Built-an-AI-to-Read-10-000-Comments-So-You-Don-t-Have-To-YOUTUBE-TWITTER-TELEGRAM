# HARSH SINGH // INTELLIGENCE MATRIX

Welcome to the **HARSH SINGH // INTELLIGENCE MATRIX**—a high-performance, cross-platform audience intelligence system. This tool is built to ingest, clean, analyze, and visualize audience engagement feeds from YouTube, X (Twitter), Telegram, and local spreadsheets. 

Whether you are tracking community sentiment, identifying narrative leaders, or mapping political stances, this matrix provides deep, actionable predictive insights using a localized AI engine.

---

## ⚡ Quick Start Guide 

Getting the application running is completely frictionless—no command lines, Python installations, or developer setups required for the end user.

1. **Download the Project Package:** Get the complete application archive directly via Google Drive: [Download SA.zip on Google Drive](https://drive.google.com/file/d/1o7Od1WGIbNo6k651MQ82P7OLmIpKZPEi/view?usp=drive_link).
2. **Launch:** Extract the ZIP file and locate the standalone executable (`AudienceIntelligence.exe`). Double-click the file, and a background service terminal will spin up locally on your machine to host the application server.
3. **Analyze:** Within seconds, your default web browser will automatically open the full interface at `http://127.0.0.1:5000/`.
4. **Close:** To shut down the app, simply close the terminal window running in the background.

---

## 🛠️ Core Features

*   **Multi-Platform Ingestion:** Pull live feedback streams directly from YouTube videos, X (Twitter) threads, or Telegram channels. Alternatively, upload raw CSV/Excel data for custom analysis.
*   **Granular Emotion Distribution:** Visualizes sentiment breakdowns across emotions like joy, anger, sadness, fear, and surprise using robust donut and bar charts.
*   **Political Spectrum Mapping:** Maps out community discourse across an interactive $x/y$ political matrix, automatically categorizing opinions into Left Wing, Center, and Right Wing ranked leaderboards.
*   **Neural Chat Assistant & AI Briefing:** Toggle the localized Gemini intelligence layer to automatically summarize recurring community themes, or use the interactive chat box to query your data directly.
*   **Narrative Leader Tracking:** Identify top commentators and narrative leaders. Click any author to open an interactive modal displaying their engagement rank (complete with custom tilted crowns for top contributors).
*   **One-Click Export:** Instantly download a structured CSV spreadsheet containing all analyzed comments, author names, engagement metrics, and timestamps.

---

## ⚙️ Configuration & Setup

Before analyzing live platform streams, you will need to configure your access credentials securely:

1. Click the **CONFIG** button in the top header.
2. Enter your respective API credentials (e.g., YouTube Data API v3 Key, Google Gemini AI API Key, X Bearer Token, Telegram API ID & Hash).
3. Click **SAVE KEYS**. All credentials are saved securely to a local `config.json` file on your machine and are never transmitted elsewhere.

---

## 💻 Tech Stack

*   **Backend:** Python, Flask, Pandas, Transformers (Hugging Face)
*   **Frontend:** HTML/CSS (Custom Sci-Fi UI), Chart.js
*   **APIs & Integrations:** Google Generative AI (Gemini), YouTube Data API, Telethon (Telegram), Twitter v2 API
*   **Packaging:** PyInstaller

---

## 🤝 Let's Connect

This project is continuously evolving, and I'm always open to feedback, collaborations, or discussing new ideas in data analytics and software architecture. 

If you found this tool useful or want to see what else I'm working on, feel free to reach out:

*   **GitHub:** [github.com/harshsinghdixit](https://github.com/harshsinghdixit)
*   **LinkedIn:** [Harsh Singh](https://www.linkedin.com/in/harsh-singh-b04b73434/)

*Built with precision. Designed for insight. Thank you for exploring the Intelligence Matrix.*
