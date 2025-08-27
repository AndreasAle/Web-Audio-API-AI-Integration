# Web-Audio-API-AI-Integration
Real-time audio → text → translation → smart reply system built with Web Audio API, AudioWorklet, and OpenAI Whisper/gpt-4o. This project demonstrates AI-assisted live captions and contextual replies for online meetings.

# 🎤 Web Audio API + AI Integration

## 📌 Overview
This project captures **live audio** from system/tab using **Web Audio API + AudioWorklet**, processes it into **16kHz WAV**, and sends it to **OpenAI Whisper/gpt-4o** for:
- 📝 Real-time transcription (captions)  
- 🌍 Instant translation  
- 💬 Context-aware suggested replies  

Perfect for **meetings, online classes, or live caption demos**.

---

## ⚡ Tech Stack
- **Frontend**: HTML, CSS, JavaScript  
- **Audio Processing**: Web Audio API, AudioWorklet (resample 16kHz PCM WAV)  
- **AI Integration**: OpenAI Whisper (`whisper-1` / `gpt-4o-mini-transcribe`) + GPT-4o for translation & replies  

---

## 🚀 Features
- 🎤 Capture system/tab audio  
- 📝 Real-time captions  
- 🌍 Auto translation (EN ↔ ID)  
- 💬 AI-generated suggested replies (context-aware & stable)  
- 🔒 Lock mode: replies only refresh per new question  

---

## 🛠️ Setup
1. Clone this repo:
   ```bash
   git clone https://github.com/AndreasAle/Web-Audio-API-AI-Integration.git
   cd Web-Audio-API-AI-Integration
