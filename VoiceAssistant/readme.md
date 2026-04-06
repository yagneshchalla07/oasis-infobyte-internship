🎤 Voice Assistant in Python

A simple voice assistant built using Python that can recognize speech, respond using text-to-speech, and perform basic tasks like opening websites, telling time/date, and more.

🚀 Features
🎙️ Voice command recognition
🔊 Text-to-speech response
🌐 Open websites (YouTube, Google)
💻 Open Visual Studio Code
🎵 Play music
🕒 Tell current time
📅 Tell today's date
👤 Respond with user name
❌ Exit on voice command
🛠️ Technologies Used
Python
speech_recognition – for voice input
pyttsx3 – for text-to-speech
datetime – for time and date
webbrowser – to open websites
os – for system commands
📦 Installation
Clone the repository:
git clone https://github.com/your-username/voice-assistant.git
cd voice-assistant
Install required libraries:
pip install SpeechRecognition pyttsx3 pyaudio

⚠️ Note: Installing pyaudio may require additional setup depending on your OS.

▶️ How to Run
python voice_assistant.py
🗣️ Supported Voice Commands
Command	Action
"open youtube"	Opens YouTube
"open google"	Opens Google
"open vs code"	Opens VS Code
"play music"	Plays a song
"tell my name"	Tells your name
"hello"	Greeting
"what is time now"	Tells current time
"tell today's date"	Tells today's date
"exit" / "stop"	Stops assistant
⚙️ How It Works
The program listens to your voice using a microphone.
Converts speech into text using Google Speech Recognition.
Matches the command with predefined conditions.
Executes the task and responds using text-to-speech.
📌 Example
Listening...
You said: open youtube
Assistant: Opening YouTube
🧠 Future Improvements
Add more commands
Integrate AI chatbot
Control system settings (volume, brightness)
Add GUI interface
Support multiple languages
👨‍💻 Author

Challa Yagnesh

📄 License

This project is open-source and free to use.
