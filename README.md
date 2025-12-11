# 🎙️ Voice Assistant  
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)  
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)  
[![Build Status](https://img.shields.io/badge/Build-Passing-brightgreen.svg)]()  
[![Contributions Welcome](https://img.shields.io/badge/Contributions-Welcome-orange.svg)]()

---

## 📌 Overview  
**Voice Assistant** is an AI-powered personal assistant built using **Python**.  
It performs real-time speech recognition, converts speech to text, automates tasks, searches the web, provides text-to-speech feedback, opens applications, and interacts naturally with users.

Designed as a lightweight yet powerful automation tool, the project demonstrates applied AI/ML concepts including NLP, speech processing, and intelligent workflow automation.

---

## 🚀 Key Features  

- 🎤 **Speech Recognition** – Understands voice commands using advanced ASR models  
- 🗣️ **Text-to-Speech (TTS)** – Responds using natural voice output  
- 🌐 **Smart Web Search** – Performs Google queries and retrieves information  
- 🧭 **Task Automation** – Opens apps, plays music, sends emails, and more  
- 🖥️ **System Control** – Shutdown, restart, volume control, etc.  
- 🔄 **Continuous Listening Mode** – Responds without repeated wake prompts  
- 🧠 **Modular Architecture** – Easily extendable command handlers  
- ⚙️ **Highly Customizable** – Environment variables and config-based setup  

---

## 🛠️ Tech Stack  

| Technology | Purpose |
|-----------|----------|
| ![Python](https://img.shields.io/badge/Python-3.8+-blue?logo=python&logoColor=white) | Core programming language |
| ![SpeechRecognition](https://img.shields.io/badge/SpeechRecognition-API-green) | Speech-to-text processing |
| ![PyAudio](https://img.shields.io/badge/PyAudio-Microphone-yellow) | Audio input handling |
| ![gTTS](https://img.shields.io/badge/gTTS-Text--to--Speech-red) | Voice output |
| ![BeautifulSoup](https://img.shields.io/badge/BeautifulSoup-Web%20Scraping-purple) | Extracting content online |
| ![Python Packages](https://img.shields.io/badge/Standard%20Libraries-OS%2C%20Subprocess%2C%20JSON-lightgrey) | System controls |

---

## 🧩 System Architecture / Workflow  

```text
               ┌──────────────────┐
               │   Microphone      │
               └─────────┬────────┘
                         │ Audio Input
                         ▼
                ┌──────────────────┐
                │ Speech Recognition│
                │  (STT Engine)     │
                └─────────┬────────┘
                         │ Command Text
                         ▼
              ┌──────────────────────┐
              │ Command Processor     │
              │ (Intent + Task Logic) │
              └──────────┬───────────┘
                         │ Output Text / Action
                         ▼
            ┌────────────────────────────┐
            │ Text-to-Speech Engine (TTS)│
            └────────────┬──────────────┘
                         │ Audio Output
                         ▼
                ┌──────────────────┐
                │   Speaker         │
                └──────────────────┘
