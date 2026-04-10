🎙️ Voice Assistant (Python)

A simple and interactive Voice Assistant built using Python that can listen to user commands and perform tasks like opening websites, telling time/date, and more.

📌 Features
🎤 Voice recognition using microphone
🔊 Text-to-speech response
🌐 Open websites like YouTube and Google
💻 Launch applications (Visual Studio Code)
🎵 Play music from YouTube
🕒 Tell current time
📅 Tell today’s date
👤 Recognize and respond with user name
❌ Exit on voice command
🛠️ Technologies Used
Python
speech_recognition – for voice input
pyttsx3 – for text-to-speech
datetime – for time and date
webbrowser – to open websites
os – to run system commands

⚙️ Installation
Install Python (3.x) and Visual Studio Code
Open your project folder in VS Code
Open terminal in VS Code
(Press `Ctrl + ``)
Install required libraries:
pip install SpeechRecognition pyttsx3 pyaudio
If pyaudio fails, run:
pip install pipwin
pipwin install pyaudio
Run the program:
python voice_assistant.py
▶️ How to Run

Run the Python file:

python voice_assistant.py
🎯 Available Voice Commands
Command	Action
"open youtube"	Opens YouTube
"open google"	Opens Google
"open vs code"	Opens Visual Studio Code
"play music"	Plays a YouTube song
"tell my name"	Says your name
"hello"	Greets you
"what is time now"	Tells current time
"tell today's date"	Tells today's date
"exit" / "stop"	Stops the assistant
📸 Sample Output
Assistant: Hello Challa Yagnesh! I am your voice assistant. How can I help you?
Listening...
You said: open youtube
Assistant: Opening YouTube
⚠️ Requirements
Python 3.x
Microphone (for voice input)
Internet connection (for speech recognition & web features)
🚀 Future Enhancements
Add more voice commands
Integrate AI chatbot features
Control system settings (volume, brightness, etc.)
Add GUI interface
👨‍💻 Author

Challa Yagnesh
Internship Project – OASIS INFOBYTE
