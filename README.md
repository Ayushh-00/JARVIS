# JARVIS
AYUSH KUMAR SINGH PROJECT FOR VITYARTHI
# JARVIS Voice Assistant

A simple, personal voice assistant built in Python. It responds to your voice commands, answers questions, opens apps, fetches weather, takes notes, and can even chat with you. This project is meant to be lightweight, easy to understand, and fun to modify.

---

## 🚀 Features

* Wake-word activation (say **"Hey Jarvis"**)
* Text‑to‑speech using `pyttsx3`
* Speech recognition using Google’s API
* Chat responses via OpenAI
* Dictionary meanings using PyDictionary
* Quick Wikipedia summaries
* Voice commands for opening websites and apps
* Note‑taking and note‑reading
* Weather updates from OpenWeatherMap
* Basic (dummy) face unlock using OpenCV
* System controls like shutdown and restart

---

## 📦 Installation

Install all required Python packages:

```bash
pip install pyttsx3
pip install SpeechRecognition
pip install openai
pip install wikipedia
pip install opencv-python
pip install requests
pip install PyDictionary
```

For microphone support:

```bash
pip install pipwin
pipwin install pyaudio
```

---

## 🔧 Setup

1. Add your OpenAI API key:

```python
openai.api_key = "YOUR_API_KEY"
```

2. Add your OpenWeatherMap key:

```python
api_key = "YOUR_OPENWEATHER_API_KEY"
```

3. Update your music folder path if needed:

```python
music_dir = "C:\Users\YourName\Music"
```

---

## ▶️ Running the Assistant

Run the script normally:

```bash
python jarvis.py
```

Jarvis will wait for the wake word. After you say **"Hey Jarvis"**, you can give commands such as:

* "open youtube"
* "what is machine learning"
* "weather in Mumbai"
* "take note"
* "play music"
* "define gravity"
* "shutdown my system"

---

## 🧠 Chat Mode

Say **"chat mode"** to switch to typing mode.
Type your message, and type **exit** anytime to go back.

---

## 📁 Notes

* "take note" → saves your spoken sentence
* "read notes" → reads everything from *notes.txt*

---

## 🌦 Weather

Gets real‑time weather using OpenWeatherMap. Default city is **Delhi**, but you can customize it easily.

---

## 📸 Face Unlock (Dummy)

Opens the webcam and displays a live feed. This is not actual face recognition—just a placeholder for future improvement.

---

## ⚠️ Important

* Make sure your microphone works.
* Internet is required for ChatGPT, weather, and voice recognition.
* Keep your API keys private.

---

## 💡 Future Improvements

* Real face recognition
* Better wake-word detection
* Offline speech-to-text
* Customizable command sets

---

## 📝 Author

Made by me, with the goal of building a simple and functional personal assistant. Happy coding!
