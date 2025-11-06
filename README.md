# 🗣️ Python Voice Assistant

A simple voice-controlled Python assistant that can respond to commands, tell the time, and search Wikipedia (with spoken responses)!

---

## ✨ Features

- Uses your **microphone** to listen for commands
- **Speaks responses** using text-to-speech (`pyttsx3`)
- **Tells the current time**
- **Searches Wikipedia** and reads a summary aloud
- Handles errors and ambiguous queries gracefully
- All in a single easy-to-run script

---

## 🛠 Requirements

Install these Python packages before running:
`pip install SpeechRecognition pyttsx3 wikipedia`
You also need microphone access (and an internet connection for Wikipedia/speech recognition).

**If you get PyAudio errors on Windows, also run:**
`pip install pipwin
pipwin install pyaudio`

---

## 🚀 How to Run

1. Plug in your microphone/headset.
2. Save `voice.py` in a folder.
3. Open terminal or CMD in that folder.
4. Run: `python voice.py`

---

## 🧑‍💻 Usage

- You will hear "hello! I am your voice assistant. How can I help you?"
- The script waits for your spoken command:
 - **Say "time"** to hear the current time.
 - **Say "wikipedia"** and it will prompt you for a topic to search.
 - **Say "exit" or "stop"** to quit.
 - Any other command gets a polite error response.
- All output is both printed and spoken.

---

## ⚡️ Example Commands

- "time"
- "wikipedia Python programming"
- "stop"

---

## 📝 How It Works

- **speech_recognition**: Listens and turns audio into text
- **pyttsx3**: Speaks answers and Wikipedia summaries
- **wikipedia**: Searches Wikipedia and reads results
- **datetime**: Gets the system time
- **Loop**: Keeps listening until you say "exit"/"stop"

---

## 📜 License

MIT — free to use, modify, distribute.

---

**Just copy, install requirements, and start chatting with your Python voice assistant!**
