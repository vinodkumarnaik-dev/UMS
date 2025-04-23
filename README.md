# 🗣️ Simple Python Voice Assistant

A fun and simple voice assistant built entirely in Python! This project is a personal assistant that responds to voice commands and performs basic tasks like searching the web, telling the time, opening applications, and more.

## 🚀 Features

- 🎤 Voice recognition using `speech_recognition`
- 🗣️ Text-to-speech with `pyttsx3`
- 🌐 Web search functionality
- 🕒 Tells the current time
- 📂 Opens specific applications or files
- ✨ Easy to customize and extend

## 📆 Requirements

Install the required libraries before running the assistant:

```bash
pip install pyttsx3 speechrecognition pyaudio
```

> ⚠️ Note: You might need to install `PyAudio` separately depending on your OS. On Windows, use a pre-built wheel; on macOS/Linux, use `brew` or `apt`.

## 🧠 How It Works

The assistant listens for your voice input through the microphone, processes the command using a speech recognition engine, and responds with an appropriate action using a text-to-speech engine.

## 📁 Project Structure

```
voice-assistant/
│
├── assistant.py         # Main voice assistant script
├── requirements.txt     # Python dependencies
└── README.md            # You're here!
```

## 🛠️ Customization

Want to make it your own? You can:
- Add more commands (open websites, play music, etc.)
- Connect it with APIs (like weather or news)
- Improve the NLP with external libraries

## 🤖 Example Commands

- “What’s the time?”
- “Open YouTube”
- “Search for Python tutorials”

## 🎉 Future Improvements

- Add GUI with `Tkinter` or `PyQt`
- Integrate with AI chat models for conversation
- Add user wake word detection

.

