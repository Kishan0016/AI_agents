# Jarvis AI Voice Assistant

An AI-powered desktop voice assistant built with Python that listens to voice commands and performs real-world tasks like opening websites, playing music, and interacting through speech.

---

## Features

- Voice Recognition using SpeechRecognition
- Text-to-Speech responses using pyttsx3
- Open websites with voice commands
- Play music directly from YouTube
- Simple and lightweight architecture
- Beginner-friendly AI automation project

---

## Tech Stack

- Python
- SpeechRecognition
- pyttsx3
- Webbrowser Module

---

## Project Structure

```bash
├── main.py
├── musicLibrary.py
└── README.md
```

---

## Supported Voice Commands

| Command | Action |
|---|---|
| Open Google | Opens Google |
| Open YouTube | Opens YouTube |
| Open GitHub | Opens GitHub Profile |
| Open WhatsApp | Opens WhatsApp Web |
| Open Classroom | Opens Google Classroom |
| Play song | Plays predefined music |

---

## How It Works

1. The assistant continuously listens for the wake word:
   ```
   Jarvis
   ```

2. Once activated, it listens for a command.

3. The command is processed and matched with predefined actions.

4. The assistant performs the requested task.

---

## Installation

### Clone the Repository

```bash
git clone https://github.com/your-username/jarvis-ai-assistant.git
```

### Install Dependencies

```bash
pip install SpeechRecognition pyttsx3 pyaudio
```

---

## Run the Project

```bash
python main.py
```

---

## Example Commands

```text
Jarvis
Open Google

Jarvis
Play song

Jarvis
Open GitHub
```

---

## Future Improvements

- Integrate OpenAI API
- Add ChatGPT conversation support
- Smart desktop automation
- Weather updates
- File management commands
- AI-powered responses

---

## Learning Outcomes

This project helped in understanding:

- Speech Recognition
- Voice-controlled automation
- Python modules
- Event-driven programming
- Desktop assistant architecture

---

## Screenshots

(Add your project screenshots here)

---

## Author

Kishan Yadav

---

## License

This project is open-source and available under the MIT License.
