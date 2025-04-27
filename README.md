Edge TTS Text-to-Speech Gradio App

This project is a Text-to-Speech (TTS) web application built with Gradio and powered by Microsoft Edge TTS voices.
It allows users to input text, select a voice, adjust speech rate and pitch, and instantly generate spoken audio.

Features

--- Full list of Microsoft Edge TTS voices (different languages, genders).

--- Adjustable speech rate (faster/slower speech).

--- Adjustable pitch (higher/lower voice tone).

--- Instant preview of generated audio (MP3 format).

--- Simple Gradio web UI, easy to use and share.

Tech Stack

Python 3.8+

Gradio (for the user interface)

edge-tts (Microsoft Edge's free TTS API)

asyncio (for asynchronous voice generation)

Tempfile + OS (for handling audio files temporarily)

Installation and Setup

1. Clone this repository

git clone https://github.com/KarthikaRajagopal44/Text-to-voice-chatbot.git
cd Text-to-voice-chatbot

2. Install dependencies

pip install -r requirements.txt

3. Run the app

python app.py
Access the app
It will be available at: http://localhost:7860

