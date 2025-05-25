
# 🆘 Voice-Activated Emergency & Reminder Assistant 🤖

This is a voice-controlled assistant built with Python. It can recognize emergency commands, set voice-based reminders, and tell the current time and date.

## 🧠 Features

- 🗣️ Voice input using `speech_recognition`
- 🔊 Text-to-speech feedback via `pyttsx3`
- 🆘 Emergency contact handling (name or number)
- ⏰ Voice-activated reminders (with delay)
- 🕒 Tells current time and date
- 🔐 Thread-safe speaking using a locking mechanism

## 🖥️ Requirements

- Python 3.x
- Microphone and speakers
- Internet connection (for speech recognition)

### 📦 Install Dependencies

```bash
pip install SpeechRecognition pyttsx3 pyaudio
```

> Tip: If `pyaudio` fails to install, refer to OS-specific installation guides or use precompiled binaries from [Gohlke's repository](https://www.lfd.uci.edu/~gohlke/pythonlibs/#pyaudio).

## 🚀 How to Use

```bash
python voice_assistance_for_elderly.ipynb
```

### 🎙️ Sample Commands

| Command | Action |
|--------|--------|
| "Emergency" / "SOS" | Triggers emergency contact prompt |
| "Remind me to drink water" | Sets a spoken reminder |
| "What time is it?" | Says the current time |
| "What's today's date?" | Says today's date |
| "Stop" or "Exit" | Quits the assistant |

## 🧪 Use Case Example

- User: *"Emergency"*
- Assistant: *"Would you like to provide contact name or phone number?"*

- User: *"Name"*
- Assistant: *"Please say the contact name."*

- User: *"Mom"*
- Assistant: *"Okay, calling Mom. Stay safe!"*

## 📂 File Structure

```
voice_assistance_for_elderly.ipynb
README.md
```

## 🔮 Future Improvements

- Integrate real calling/SMS APIs (e.g., Twilio)
- Store and manage multiple reminders
- Add support for more natural conversation

## 👨‍💻 Author

Developed by Harshavardhan.V – making everyday safety and productivity easier with Python and voice technology. 🎤🧠📅

---

Stay safe and organized with your voice! 💬🔒🕓
