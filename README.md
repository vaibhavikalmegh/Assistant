# 🧠 WhatsApp Assistant + AI Chatbot

A Python-based voice assistant that sends WhatsApp messages, makes calls, opens apps, and answers questions using Hugging Face AI — all through a sleek web interface.

🎥 [Watch Full Demo on Google Drive](https://drive.google.com/file/d/1Yum_9rY4S-vG1vgi3TYyKKFy4u7L54Sw/view?usp=sharing)
---

## 🚀 Features

| Feature                  | Description                                                                 |
|------------------------  |-----------------------------------------------------------------------------|
| 📱 WhatsApp Control      |Send messages, make calls, and open chats via WhatsApp Web                  |
| 🗣️ Voice Commands        | Control the assistant using your voice (Speech-to-Text)                    |
| 🧠 AI Question Answering | Integrated with Hugging Face Transformers to answer your queries           |
| 🖥️ App Launcher          | Open local apps or web platforms like YouTube, Gmail, etc.                 |
| 🌐 Web Interface         | Lightweight front-end (HTML/CSS/JS) to control the assistant               |
| 🔊 Text-to-Speech        | The assistant replies using a synthetic voice (TTS)                        |
| 🧩 Modular Design        | Organized structure: separate logic, UI, and AI handling                   |

---

## 🔧 Tech Stack

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Python, Flask
- **NLP/AI**: Hugging Face Transformers
- **Voice Processing**: `speech_recognition`, `pyttsx3`
- **Automation**: Selenium (for WhatsApp Web)
- **Database**: SQLite (`vaibhavi.db`)
- **Integration**: Eel (Python + JS Bridge)

---

## 🔐 Privacy Notice

The following sensitive files were excluded for your safety and privacy:
- `cookies.json` – Contains session tokens for WhatsApp Web
- `vaibhavi.db` – Local contact database
- `contacts_sample.csv` – Sample contacts including phone numbers

> ⚠️ Please create or modify these files using your own test data before running the assistant.

---

## 🧪 How to Run

```bash
# Clone the repository
git clone https://github.com/vaibhavikalmegh/Assistant.git
cd whatsapp-assistant

# (Optional) Set up a virtual environment
python -m venv venv
source venv/bin/activate  # For Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run the assistant
python jarvis.py
```

---

## 👩‍💻 About Me
Vaibhavi Kalmegh
📍 G.V.I.S.H., Amravati
🎓 M.Sc. in Statistics (2023) 
Follow me on:  
🔗 [GitHub](https://github.com/vaibhavikalmegh)  
🔗 [LinkedIn](https://www.linkedin.com/in/vaibhavikalmegh18)

---

## 📎 Future Enhancements

- [ ] Deploy assistant as a web app
- [ ] Add login system with user history
- [ ] Use OpenAI for improved natural conversations

