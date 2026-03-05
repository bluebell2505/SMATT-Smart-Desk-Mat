# SMATT 🤖 - Smart Desk Mat powered by Gemini

## 🌟 Overview

SMATT is an intelligent voice-controlled assistant integrated with IoT designed to enhance productivity and integrate seamlessly with IoT devices. By leveraging AI and real-time data processing, SMATT helps users manage tasks, monitor environments, and interact with smart devices effortlessly.

---

## Key Features

✅ **AI-Powered Voice Assistant** – Interact naturally using voice commands.\
✅ **Smart Scheduling** – Google Calendar integration for effortless task management.\
✅ **IoT Connectivity** – Supports sensors and smart devices via serial communication.\
✅ **Environmental Monitoring** – Tracks real-time temperature and humidity.\
✅ **Task & Reminder System** – Manage to-do lists and set intelligent reminders.\
✅ **Real-Time Data Processing** – Fetch AI-powered insights and responses.

---

## 📂 Project Structure

```
SMATT/
├── ai/              # AI integration
│   ├── gemini_handler.py
│
├── utils/           # Utility modules
│   ├── config.py
│   ├── google_calendar.py
│   ├── real_time.py
│   ├── serial_handler.py
│   ├── timer.py
│   ├── todo.py
│
├── voice/           # Voice processing
│   ├── speech_handler.py
│
├── .env             # Environment variables
├── .gitignore       # Ignored files
├── credentials.json # API credentials
├── main.py          # Main execution file
├── test_oauth.py    # OAuth testing script
├── token.json       # OAuth token storage
└── README.md        # Project documentation
```

---

## 🛠 Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/SMATT.git
   cd SMATT
   ```
2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
3. **Set up environment variables:**
   ```bash
   cp .env.example .env
   # Update .env with your API keys
   ```
4. **Run the assistant:**
   ```bash
   python main.py
   ```

---

## 🗣 Example Commands

🔹 "**Hey Assistant**" → "Good Afternoon! How can I help you?"\
🔹 **"What's the temperature?"** → *"The current temperature is 25°C."*\
🔹 "**How much humidity is present in my room?**" → "The current Humidity is 35%."\
🔹 **"Add 'Call Mom' to my to-do list."** → *"Added: Call Mom."*\
🔹 **"Set a timer for 20 minutes."** → *"Timer started for 20 minutes."*\
🔹 **"Explain machine learning."** → *[AI-generated response]*

---

<img width="462" height="351" alt="image" src="https://github.com/user-attachments/assets/edac25d8-41f2-40c0-b689-001c025eb260" />

Project Demo: https://youtu.be/bhgKWdaKAhk?si=ZcwO1AB_Xqv2HhE9

---

## 🤝 Contributing

We welcome contributions! Feel free to submit issues or pull requests to enhance SMATT’s functionality.

---




