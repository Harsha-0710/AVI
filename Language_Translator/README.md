
# 🎤 Voice Translator & Speaker 🌐

This is a simple Python-based **Voice Translator & Speaker** tool. It listens to your voice, translates your speech from one language to another using Google Translate, and then speaks the translated output.

## ✨ Features

- 🎙️ Voice recognition using `speech_recognition`
- 🌐 Translation using `googletrans`
- 🔊 Text-to-speech using `pyttsx3`
- Supports language names or ISO 639-1 codes (e.g., `en`, `ta`, `hi`, `fr`)
- No file saving – all translation happens in real-time

## 🖥️ Requirements

- Python 3.x
- Internet connection (for speech recognition and translation)

### 📦 Required Libraries

Install the dependencies using:

```bash
pip install SpeechRecognition pyttsx3 googletrans==4.0.0-rc1 pyaudio
```

> Note: If you have trouble installing `pyaudio`, check [this guide](https://people.csail.mit.edu/hubert/pyaudio/#downloads) for help.

## 🚀 How to Run

```bash
Language_translator.ipynb
```

### 🧪 Sample Input

When prompted:

```
🗣️ Enter source language (code or name): english
🌍 Enter target language (code or name): french
```

Then say something like:
> "Good morning"

You’ll hear:
> "Bonjour"

## 🌍 Supported Languages

All languages supported by Google Translate (like Tamil, Hindi, English, French, Spanish, etc.). Use either the name (`Hindi`) or code (`hi`) to select.

## 📂 File Structure

```
Language_translator.ipynb
README.md
```

## 💡 Future Ideas

- Add GUI interface with language dropdowns
- Save translations to a file
- Add offline translation model

## 👨‍💻 Author

Created by Harshavardhan.V to break language barriers with voice and code. 🌐🧠🔊

---

Speak. Translate. Understand. 🌎✨
