# 📝 Whisper AI: Transcribe & Analyze Audio Effortlessly 🎧

Whisper AI is an **Automatic Speech Recognition (ASR) system** developed using **OpenAI's Whisper Model**. This project enables users to **transcribe audio**, **perform sentiment and emotion analysis**, **summarize content**, **translate transcriptions**, and even **search Google** using transcribed text.

---

## 📌 Key Features

✅ **Speech-to-Text (ASR)** – Convert speech from audio files into **highly accurate** text.  
✅ **Sentiment Analysis** – Detects whether the transcribed text is **positive, negative, or neutral**.  
✅ **Emotion Detection** – Identify emotions like **joy, sadness, anger, fear, surprise, etc.**.  
✅ **Summarization** – Generate a concise summary of transcriptions for quick insights.  
✅ **Language Translation** – Translate transcriptions into **multiple languages**.  
✅ **Text-to-Speech (TTS)** – Convert transcribed text **back into speech** for playback.  
✅ **Google Search Integration** – Instantly **search transcribed text** on Google.  
✅ **Noise Reduction** – Reduce background noise before transcription for **better accuracy**.  
✅ **Modern UI** – Elegant **black and gold theme** with a **structured layout**.  

---

## 💚 Live Demo
Try the live demo here: **[Whisper AI Live Demo]([https://your-demo-link.com](https://whisper-ai-transcription-kyzftj2omrkpacrk727nc4.streamlit.app/))**

---

## 💽 Installation & Setup

### 1️⃣ **Clone the Repository**
```sh
git clone https://github.com/YourUsername/Whisper-AI-Transcription.git
cd Whisper-AI-Transcription
```

### 2️⃣ **Install Dependencies**
Ensure Python is installed, then run:
```sh
pip install -r requirements.txt
```

### 3️⃣ **Run the Application**
```sh
streamlit run whisper_streamlit.py
```

---

## 🔧 Dependencies

This project requires the following **Python libraries**:
- `streamlit` – UI Framework
- `whisper` – OpenAI's ASR Model
- `torch` – Deep Learning Backend
- `transformers` – Hugging Face NLP Models
- `gtts` – Google Text-to-Speech
- `deep-translator` – For text translation
- `soundfile` & `numpy` – Audio processing
- `noisereduce` – Reduce background noise
- `textblob` – Sentiment analysis

**Install manually** (if needed):
```sh
pip install streamlit openai-whisper torch transformers gtts deep-translator soundfile numpy noisereduce textblob
```

---

## 🛠️ How to Use

1️⃣ **Upload an Audio File** (`.mp3`, `.wav`, `.m4a`).  
2️⃣ **Select Transcription Language** (English, Urdu, Spanish, etc.).  
3️⃣ **Click "Transcribe & Analyze"** – The app will:  
   - **Transcribe the audio**
   - **Analyze sentiment & emotion**
   - **Summarize the text**
   - **Translate the text (if selected)**
   - **Convert the text back to speech (TTS)**
4️⃣ **Perform Google Search** using transcribed text.  
5️⃣ **Listen or download** the transcribed audio.  

---

## 📸 Screenshots

### **📝 Transcription & Analysis**

![image](https://github.com/user-attachments/assets/ebd3f617-76b4-4344-8db8-1e85c5963a74)

![image](https://github.com/user-attachments/assets/888f962a-84cf-4c19-bef8-e7c0eef741b6)

![image](https://github.com/user-attachments/assets/cfce5e59-50b8-4c71-a2f6-dcc75badbc63)

---

## 🌐 Google Search Integration
Once transcription is completed, **click the Google Search button** to **instantly search the transcribed text** on Google.

---

## 🔧 Performance Benchmarks
| Model    | Size  | Speed  | Accuracy  |
|----------|-------|--------|-----------|
| **Tiny**  | 39M   | 🔥 Fast  | ✅ Good    |
| **Base**  | 74M   | ⚡ Medium | ✅ Better  |
| **Small** | 244M  | 🚀 Moderate | ✅ High  |
| **Medium** | 769M | 🏁 Slow  | ✅ Very High  |
| **Large**  | 1.55B | 🐢 Slowest | ✅✅ Best  |

---

## 🌟 Frequently Asked Questions (FAQ)

### 1️⃣ How do I fix CUDA Out of Memory Errors?
Try forcing CPU usage:
```sh
DEVICE="cpu"
```

### 2️⃣ What file formats does Whisper AI support?
- **Supported:** `.mp3`, `.wav`, `.m4a`
- **Not Supported:** `.ogg`, `.flac`, `.aac` (convert using `ffmpeg`)

### 3️⃣ Can I use this on mobile?
Currently, **only PC/Laptop** is supported. A **mobile version** may be released in the future.

---

## 🔧 Troubleshooting

### 🚫 **CUDA Memory Issues**
If you get a GPU memory error, force CPU usage:
```sh
DEVICE="cpu"
```

### ❗ **Missing Dependencies**
If you get a missing package error, reinstall:
```sh
pip install -r requirements.txt --force-reinstall
```

---

## 👨‍💻 Contributing
Contributions are **welcome**! Feel free to:
- **Fork** this repository.
- **Create a new feature branch**.
- **Submit a Pull Request**. 🚀

---

## 💜 Support the Project
If you like this project, please **⭐ star this repository** on GitHub!  
Let's **innovate AI-powered speech transcription together**! 🚀🎧

