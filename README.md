# 🦾 Iron Man J.A.R.V.I.S. Assistant

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python)
![Voice](https://img.shields.io/badge/Voice-Recognition-green?style=for-the-badge&logo=google)
![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20Linux-lightgrey?style=for-the-badge&logo=windows)

An AI-powered personal assistant inspired by Tony Stark’s J.A.R.V.I.S.  
This project integrates **voice recognition**, **machine learning models**, and **automation** to create a futuristic assistant experience.

> **⚠️ DISCLAIMER:**  
> Developed by **Magne Dina Neves** strictly for **educational purposes** and personal experimentation.  
> It demonstrates natural language processing, system automation, and AI integration.  
> Usage is allowed only on authorized systems. **Malicious use is prohibited.**

---

## ✨ Features

- **🎙️ Voice Commands:** Control your system and applications hands-free.  
- **🤖 AI Responses:** Context-aware replies powered by trained ML models.  
- **💻 System Automation:** Open apps, manage files, and execute tasks.  
- **🌐 Web Integration:** Search the internet and fetch information.  
- **🧠 Machine Learning:** Uses trained models (`chat_model.h5`, `tokenizer.pkl`, `label_encoder.pkl`) for intent recognition.  

---

## 🛠️ Tech Stack

- **Language:** Python 3  
- **Libraries:**  
  - `speech_recognition` – voice input  
  - `pyttsx3` – text-to-speech output  
  - `tensorflow/keras` – deep learning models  
  - `pickle` – model serialization  
  - `os` – system control  
  - `requests` – API integration  
- **Infrastructure:** Local execution with optional cloud APIs  

---

## 📂 Project Structure



Ensure you have Python installed. Then install the required dependencies:

```bash
pip install -r requirements.txt
