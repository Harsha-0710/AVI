
# Smart Home Voice Control System 🏠🎤

This is a simple Python-based **Voice-Controlled Smart Home System**. It uses speech recognition to interpret voice commands and control virtual appliances such as lights, fans, TVs, ACs, and heaters.

## 🔧 Features

- Voice recognition using `speech_recognition`
- Text-to-speech feedback using `pyttsx3`
- Supports multiple aliases and catchy phrases for commands
- Turn on/off individual appliances or all at once
- Includes conversational trigger phrases like *"Netflix and chill"*

## 🖥️ Requirements

- Python 3.x
- Microphone (for input)
- Internet connection (for Google Speech Recognition API)

### Python Packages

Install the required Python libraries using pip:

```bash
pip install SpeechRecognition pyttsx3 pyaudio
```

> Note: If you face issues with installing `pyaudio`, try:
> - Windows: Use wheel files from https://www.lfd.uci.edu/~gohlke/pythonlibs/#pyaudio
> - macOS/Linux: Use `brew install portaudio` or `apt install portaudio19-dev`

## 🚀 How to Use

1. Run the script:
    ```bash
    python Voice_assisted_home_appliance.ipynb
    ```
2. Speak commands like:
    - "Lights on"
    - "Make it breezy"
    - "Netflix and chill"
    - "Good night"

3. Say `"exit"`, `"stop"`, or `"quit"` to end the program.

## 🔄 Example Commands

| Command | Meaning |
|--------|---------|
| "Let's light it up" | Turn on light |
| "I'm hot" | Turn on fan |
| "I'm freezing" | Turn off AC |
| "Good night" | Turn off all appliances |

## 📂 File Structure

```
Voice_assisted_home_appliance.ipynb
README.md
```

## 🧠 Future Improvements

- Add GUI interface using Tkinter or PyQt
- Integrate with real IoT devices (e.g., using Raspberry Pi or Arduino)
- Include support for multiple languages

## 👨‍💻 Author

Built by Harshavardhan.V – a Smart Home enthusiast. 😊

---

Enjoy your smart and voice-powered home! 🔌🎙️✨
