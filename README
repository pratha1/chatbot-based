# AggieAssistant 🐾

<div align="center">

**A Python-based AI virtual assistant designed for Texas A&M University students**

*Combining voice interaction, AI-powered responses, and quick access to university resources in a user-friendly GUI*

</div>

---

## ✨ Features

### 🗣️ Voice Commands & Text-to-Speech
Interact naturally using your voice. The assistant responds using `pyttsx3` for seamless audio feedback.

### ❓ Ask Questions
Ask about TAMU or general queries. Uses **Hugging Face LLaMA-3 API** for AI-powered answers, with a fallback knowledge base for offline support.

### 🌐 Open Websites
Quickly access popular sites via voice commands:
- Google, YouTube
- TAMU Portal, Howdy
- Canvas LMS
- And more!

### 🔁 Repeat Phrase
Speak anything, and the assistant will echo it back using its voice.

### 📝 Conversation Logging
Tracks all interactions in a scrollable GUI display for easy reference and review.

### 🎨 Beautiful GUI with Logo
Built with `tkinter` and proudly displays the **Reveille logo** 🐕

---

## 🛠️ Technologies & Libraries

| Category | Technology |
|----------|------------|
| **Language** | Python 3.11+ |
| **GUI Framework** | `tkinter` + `tkinter.scrolledtext` |
| **Image Handling** | `Pillow (PIL)` |
| **Speech Recognition** | `speech_recognition` |
| **Text-to-Speech** | `pyttsx3` |
| **HTTP Requests** | `requests` |
| **AI Integration** | Hugging Face API (LLaMA-3) |
| **Concurrency** | Threading for non-blocking UI |

---

## 📦 Installation

### 1. Clone the repository
```bash
git clone https://github.com/yourusername/AggieAssistant.git
cd AggieAssistant
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

#### `requirements.txt` example:
```
tk
pillow
speechrecognition
pyttsx3
requests
```

---

## 🚀 Usage

### Run the assistant
```bash
python AggieAssistant.py
```

The GUI will launch with a welcome message and the **Reveille logo**.

### Interact with buttons
- **Open Website** 🌐: Voice-command to open popular sites
- **Ask A Question** 💬: Ask AI or fallback questions
- **Repeat the Phrase** 🔁: Speak something, and the assistant will repeat it

> **Note:** Make sure your microphone is enabled and working properly.

---

## ⚙️ Configuration

### Hugging Face API (Optional)
Enable AI responses by setting your API token:
```python
self.hf_token = "YOUR_HUGGING_FACE_TOKEN"
```

### Voice Settings
Customize speech rate and volume:
```python
self.engine.setProperty('rate', 150)     # Speed of speech
self.engine.setProperty('volume', 1.0)   # Volume level (0.0 to 1.0)
```

---

## 📌 Notes

- ✅ **Audio output** works best with TTS in separate threads to avoid conflicts with microphone input
- 🎓 Designed specifically for **Texas A&M University students**, but easily adaptable for general use
- ⚡ GUI operations are threaded for maximum responsiveness
- 🔊 Ensure your system audio and microphone permissions are properly configured

---

## 🎯 Future Enhancements

- 📅 Calendar integration with TAMU events
- 📚 Course schedule quick access
- 🗺️ Campus navigation assistance
- 📊 Grade tracking and GPA calculator
- 🤖 Enhanced AI responses with context memory

---


<div align="center">

**Gig 'em! 👍**

*Built with ❤️ for the Aggie community*

</div>
