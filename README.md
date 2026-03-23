# 🤖 PyVA — Virtual Assistant & Emotional Analyzer

> A Python-powered voice-command virtual assistant with real-time facial emotion recognition, NLP, and automated reporting.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![DeepFace](https://img.shields.io/badge/DeepFace-4B0082?style=flat-square)
![NLTK](https://img.shields.io/badge/NLTK-76B900?style=flat-square)
![SpaCy](https://img.shields.io/badge/SpaCy-09A3D5?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)

---

## 📌 Overview

**PyVA** is a sophisticated virtual assistant built entirely in Python. It listens to voice commands, understands natural language, retrieves real-time information, and uniquely — analyzes your facial emotions via webcam using DeepFace and TensorFlow, then sends automated email reports summarizing the session.

---

## ✨ Features

| Feature | Description |
|---|---|
| 🗣️ **Voice Commands** | Speak naturally; PyVA understands and responds |
| 🧠 **NLP Processing** | Powered by NLTK & SpaCy for intent understanding |
| 😀 **Emotion Recognition** | Real-time facial emotion analysis via webcam using DeepFace |
| 🌤️ **Weather Info** | Fetches live temperature and weather data |
| 📰 **News Retrieval** | Gets latest headlines on demand |
| 🌐 **Wikipedia Search** | Answers knowledge queries instantly |
| 🌍 **IP Info** | Retrieves network/location information |
| 📧 **Automated Email Reports** | Sends session summaries via email |
| 💡 **Random Facts** | Delivers interesting facts on command |

---

## 🛠️ Tech Stack

- **Core Language**: Python 3.x
- **Emotion Recognition**: DeepFace, TensorFlow / PyTorch
- **NLP**: NLTK, SpaCy
- **Web Data**: Requests, BeautifulSoup
- **Voice**: SpeechRecognition, pyttsx3
- **Email**: smtplib

---

## 📸 Screenshots

### Temperature Information
![Temperature](./screenshots/temp.png)

### Random Facts
![Facts](./screenshots/facts.png)

### IP Address Info
![IP Info](./screenshots/ip.png)

### News
![News](./screenshots/news.png)

### Wikipedia Search
![Wiki](./screenshots/wiki.png)

### Emotion Analysis
![Emotion](./screenshots/emotion.png)

---

## ⚙️ Installation & Setup

### Prerequisites
- Python 3.8+
- Webcam (for emotion recognition)
- Microphone (for voice commands)

### 1. Clone the repository
```bash
git clone https://github.com/Rishabhx12/virtual-assistant.git
cd virtual-assistant
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Configure email (for automated reports)
Open `virtualAssitant.py` and update:
```python
EMAIL = "your_email@gmail.com"
PASSWORD = "your_app_password"  # Use Gmail App Password
```

### 4. Run the assistant
```bash
python virtualAssitant.py
```

---

## 📦 Requirements

```
tensorflow
deepface
nltk
spacy
speechrecognition
pyttsx3
requests
beautifulsoup4
opencv-python
```

> Install all at once: `pip install -r requirements.txt`

---

## 🗣️ Example Commands

```
"What's the weather today?"
"Tell me a random fact"
"Search Wikipedia for machine learning"
"What's my IP address?"
"Get me the latest news"
"Analyze my emotion"
```

---

## 🔮 Future Improvements

- [ ] Web dashboard for emotion history visualization
- [ ] Multi-language support
- [ ] Integration with Google Calendar
- [ ] Mobile app interface
- [ ] GPT-based conversational responses

---

## 👤 Author

**Rishabh Singh**
- LinkedIn: [rishabh-singh-40136821a](https://www.linkedin.com/in/rishabh-singh-40136821a/)
- Email: rishusingh1958@gmail.com
- GitHub: [@Rishabhx12](https://github.com/Rishabhx12)

---

## 📄 License

This project is licensed under the MIT License.
