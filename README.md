# Assistant
A Python-based voice assistant that sends WhatsApp messages, makes calls, opens apps, and answers questions using Hugging Face AI.
# 🧠 WhatsApp Assistant + AI Chatbot (`whatsapp-assistant`)

A smart voice-based assistant built with Python that can:
- 🔓 Open desktop or web applications
- 💬 Send WhatsApp messages
- 📞 Make WhatsApp voice and video calls
- 🤖 Answer general questions using Hugging Face AI
- 🌐 Provide a simple web interface for control

---

## 🚀 Features

| Feature | Description |
|--------|-------------|
| 📱 WhatsApp Control | Send messages, make calls, open chats via WhatsApp Web |
| 🗣️ Voice Commands | Control the assistant using your voice (speech-to-text) |
| 🧠 AI Question Answering | Integrated with Hugging Face to answer user queries |
| 🖥️ App Launcher | Open installed apps or web apps like YouTube, Gmail, etc. |
| 🌐 Web Interface | Simple front-end using HTML/CSS/JS for controlling assistant |
| 🔊 Text-to-Speech | Assistant speaks responses back to you |
| 🧩 Modular Design | Cleanly structured with separate modules for logic, UI, and API |

---

## 📁 Project Structure

whatsapp-assistant/
│
├── engine/ # Core logic and helpers
│ ├── command.py
│ ├── config.py
│ ├── features.py
│ ├── helper.py
│ └── db.py
│
├── www/ # Web interface
│ ├── index.html
│ ├── main.js
│ ├── controller.js
│ ├── script.js
│ └── style.css
│
├── main.py # Project entry point
├── run.py # Alternate entry script
├── .gitignore
└── README.md

## 🔐 Privacy Notice

> The following sensitive files were excluded:
- `cookies.json` – Contains session tokens for WhatsApp Web
- `vaibhavi.db` – Database with personal contact info
- `contacts_sample.csv` – Includes private contact numbers

Ensure you create or configure your own clean versions before running.


