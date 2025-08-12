
***

# 🎙️ AI Voice Assistant with Real-Time Conversations

A **smart NLP-powered Voice Assistant** that listens, understands, thinks, and talks back in **real-time** — all powered by **Groq’s ultra-fast LLM inference (LLaMA 3.3–70B)** and deployed via **Streamlit**.  

This assistant features **speech-to-text**, **humorous personality-driven responses**, and **text-to-speech** output — creating a natural, interactive conversational experience.  

***

## ✨ Features

- 🧠 **NLP Core:** Powered by **LLaMA 3.3–70B** via Groq API for lightning-fast responses.
- 🎙️ **Real-Time Speech Recognition** using Python’s `speech_recognition` package.
- 😂 **Custom Personality Mode** — responds in the style of **Brahmanandam**, the iconic South Indian comedy actor, delivering short, witty replies.
- 🗣 **Voice Synthesis** with `pyttsx3` for instant audio responses.
- 🌐 **Streamlit Web UI** for an interactive browser-based voice chat.

***

## 🛠 Technologies Used

- **Python** — NLP + Audio Processing  
- **Groq API** — LLaMA 3.3–70B ultra-fast inference  
- **Streamlit** — Web-based UI framework  
- **SpeechRecognition** — Speech-to-text (STT)  
- **Pyttsx3** — Text-to-speech (TTS)  
- **Prompt Engineering** — For humorous, character-driven responses  

***

## 📚 How It Works

1. **Voice Input (STT):** Listens to your voice and transcribes it using `speech_recognition`.
2. **LLM Interaction:** Sends the transcription to **Groq’s LLaMA 3.3–70B** for intelligent, personalized replies.
3. **Custom Humor Personality:** Prompt engineering ensures replies sound like **Brahmanandam**.
4. **Voice Output (TTS):** Generates human-like voice using `pyttsx3` and plays it back in real time.
5. **Web UI:** Interact via a clean **Streamlit** interface.

***

## 🚀 Installation & Setup

### 1️⃣ Clone this Repository
```bash
git clone https://github.com/yourusername/ai-voice-assistant.git
cd ai-voice-assistant
```

### 2️⃣ Create & Activate Virtual Environment
```bash
python -m venv venv
source venv/bin/activate  # For Mac/Linux
venv\Scripts\activate     # For Windows
```

### 3️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 4️⃣ Set Your API Key Securely  
Create a `.env` file in the project root and add your Groq API key:
```env
GROQ_API_KEY=your_api_key_here
```
⚠ **Never commit your API keys to GitHub**. Ensure `.env` is listed in `.gitignore`.

### 5️⃣ Run the App
```bash
streamlit run app.py
```

***

## 🖼 Demo Screenshot  
<img width="1919" height="1012" alt="image" src="https://github.com/user-attachments/assets/ec68bae3-73cb-4025-b74b-df55e68ab496" />


***

## 🔍 Example Conversation

**You:** "Hello, how are you?"  
**Assistant:** "Ahh! Nenu baagane unna… meeru coffee ivvaraa?" ☕ 😄  

***

## 📌 Future Improvements
- Support for multiple personality modes  
- Integration with real-time streaming STT for zero-latency input  
- More expressive voice synthesis  
- Mobile version using Kotlin or React Native  

***

## 📜 License
This project is licensed under the **MIT License** — free to use, modify, and share.

***

## 🙌 Acknowledgements
- [Groq](https://groq.com) for lightning-fast LLM inference  
- [Streamlit](https://streamlit.io/) for the UI magic  
- [SpeechRecognition](https://pypi.org/project/SpeechRecognition/) and [pyttsx3](https://pypi.org/project/pyttsx3/) for enabling the voice interface  

***
