# 🤖 J.A.R.V.I.S – Desktop Voice Assistant (Part-01)

A **Python-based Desktop Voice Assistant** with a **graphical user interface**, inspired by *JARVIS*.  
This project combines **speech recognition**, **text-to-speech**, and **PyQt5 GUI** to create an interactive desktop assistant capable of performing daily tasks through voice commands.

---

## 📂 Repository Structure

```
Jarvis-Desktop-Voice-Assistant/
│
├── Assets/                  # UI images, GIFs, and media files
├── client.py                # Core assistant logic (voice + actions)
├── main.py                  # PyQt5 GUI entry point
├── musicLibrary.py          # Music handling module
├── requirements.txt         # Python dependencies
├── temp.mp3                 # Temporary audio output file
└── README.md                # Project documentation
```

---

## ✨ Features

- 🎙️ Voice input using microphone  
- 🔊 Text-to-Speech responses  
- 🖥️ Interactive PyQt5 desktop GUI  
- 🌐 Open websites & perform Google searches  
- ▶️ Play YouTube videos  
- 🎵 Play local music  
- 📰 Fetch latest news  
- 🧮 Answer factual & computational questions  
- 📅 Date & time updates  
- 😂 Jokes & fun facts  
- 📸 Screenshot capture  
- 📧 Send emails  
- ⚙️ System information (CPU, RAM, etc.)

---

## 🧰 Tech Stack

- **Python 3.10+**
- **PyQt5**
- **SpeechRecognition**
- **pyttsx3**
- **PyAudio**
- **psutil**
- **pywhatkit**
- **pyautogui**
- **WolframAlpha API**

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/imanshu-01/J.A.R.V.IS-PART-01.git
cd J.A.R.V.IS-PART-01/Jarvis-Desktop-Voice-Assistant
```

---

### 2️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

#### PyAudio (Windows only)
```bash
pip install pipwin
pipwin install pyaudio
```

---

## ▶️ Run the Application

```bash
python main.py
```

Click the **Start** button in the GUI to activate the assistant.

---

## 🔑 Configuration

Before running, ensure:
- **WolframAlpha App ID** is configured
- **Email credentials** are correctly set (if using email feature)
- Microphone access is enabled in **Windows Privacy Settings**

---

## ⚠️ Known Limitations

- Microphone and TTS must run in the **same thread** to avoid audio conflicts
- Application is currently **Windows-focused**
- No wake-word detection (manual start required)

---

## 🚀 Future Scope (Part-02)

- Wake-word detection (“Hey Jarvis”)
- Continuous background listening
- ChatGPT / AI integration
- Improved UI animations
- Cross-platform support (Linux/macOS)
- Better error handling & logging

---

## 👤 Author

**Himanshu Patle**  
📍 Nagpur, India  
🔗 GitHub: https://github.com/imanshu-01

---

## ⭐ Support & Contribution

If you find this project useful:
- ⭐ Star the repository  
- 🍴 Fork it  
- 🐞 Report issues  
- 📢 Share feedback  

---

© 2025 Himanshu Narayan Patle. All rights reserved.
