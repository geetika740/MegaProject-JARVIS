# 🧠 JARVIS - Virtual Desktop Assistant (Python)

JARVIS is an intelligent voice-controlled virtual assistant built using Python. It can perform various desktop automation tasks through voice commands, making your interaction with your computer faster and more intuitive.

## 🚀 Features

- 🗣️ Voice recognition and speech output
- 🔍 Search Wikipedia and Google
- 🌐 Open websites like YouTube, Gmail, Stack Overflow
- 🕒 Tell the current time and date
- 📁 Open system applications (e.g., Notepad, Command Prompt)
- 📧 Send emails using voice
- 🎶 Play music from your local system
- 💻 Automate keyboard and system functions
- 🧠 Extendable with new commands and functions

## 🛠️ Tech Stack

- **Language**: Python
- **Libraries**:
  - `speech_recognition`
  - `pyttsx3`
  - `datetime`
  - `webbrowser`
  - `wikipedia`
  - `os`, `smtplib`, `pywhatkit`, `keyboard`, etc.

## 🧪 How to Run

### 1. Clone the repository


git clone https://github.com/<your-username>/MegaProject-JARVIS.git
cd MegaProject-JARVIS

### 2. Create a virtual environment (optional but recommended)

python -m venv venv
venv\Scripts\activate

### 3. Install dependencies

pip install -r requirements.txt
If requirements.txt doesn’t exist, manually install:
pip install pyttsx3 SpeechRecognition wikipedia pywhatkit keyboard

### 4. Run the Assistant

python main.py
Speak clearly into your microphone and JARVIS will respond!

## 📂 Folder Structure

MegaProject-JARVIS/
├── main.py               # Main assistant script
├── commands/             # (Optional) Additional features/scripts
├── requirements.txt      # Python dependencies
├── README.md             # Project overview
└── .gitignore            # Ignored files

## 🎯 Example Commands

“Open YouTube”
“Play music”
“What is the time?”
“Who is Elon Musk?”
“Send an email”
“Search on Google for machine learning”

## 🧠 Future Ideas

GUI-based interface
Voice training/recognition personalization
Integration with APIs like weather, news, etc.
Smart home control (IoT)

## 🙋‍♀️ Author
Geetika Kakkar


## 📝 License
This project is licensed under the MIT License. You can freely use, modify, and distribute it.
