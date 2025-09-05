# 🎨 AI Emotion-to-Art Team2

✨ Transform Your Emotions into Stunning **AI-Generated Artworks** ✨

---

## 📌 Table of Contents
- [👋 Introduction](#-introduction)
- [⚙️ How It Works](#️-how-it-works)
- [🖼️ Samples](#️-samples)
- [📥 Installation & Setup](#-installation--setup)
- [🛠️ Debug / Troubleshooting](#️-debug--troubleshooting)
- [👥 Team Members](#-team-members)

---

## 👋 Introduction
**AI Emotion-to-Art Team2** is an innovative project that converts user emotions (**text, voice, or image**) into symbolic visual art using cutting-edge AI technologies:

- 🎤 **Whisper** → Converts speech to text  
- 🤖 **Ollama (Gemma3:4b)** → Emotion recognition  
- 🖼️ **Replicate (Imagen backend)** → AI art generation  

---

## ⚙️ How It Works
1️⃣ **Provide Emotion** → Input a sentence, record your voice, or upload an image.  
2️⃣ **Emotion Recognition** → A locally running **Gemma3:4b** model through Ollama classifies your emotion.  
3️⃣ **Prompt Generation** → The system builds a symbolic prompt *(under 20 words)* for visualization.  
4️⃣ **Art Generation** → The prompt is sent to **Replicate (Imagen backend)** and a square artwork is generated.  

---

## 🖼️ Samples
Here’s an example of how emotions transform into AI-generated art:  

| Input | Generated Artwork |
|-------|-------------------|
| من قهرمان مسابقات برنامه نویسی شدم | ![Sample](assest/1.png) |

---

## 📥 Installation & Setup

### ✅ Requirements
- Python **3.13**
- Ollama installed with **Gemma3:4b** model
- Replicate API token

### ⚡ Quick Setup
```bash
# Install Ollama → https://ollama.com/
# Run: ollama run gemma3:4b

python -m venv env
source env/bin/activate   # (Windows → .\env\Scripts\activate)

pip install openai-whisper replicate ollama gradio

# Export Replicate token
export REPLICATE_API_TOKEN="your_token_here"
# or (Windows)
setx REPLICATE_API_TOKEN "your_token_here"

# Run Gradio UI
```

---

## 🛠️ Debug / Troubleshooting

Common issues and fixes:  

```bash
# 🚫 Ollama / Gemma3:4b Errors
“Model not found” → You haven't installed Gemma3:4b  
✅ Fix: ollama run gemma3:4b

“Cannot connect to Ollama” → Ollama service not running  
✅ Fix: Open Ollama desktop app or run ollama serve


# 🚫 Replicate API Errors
HTTP 401 Unauthorized → Invalid/expired token  
✅ Fix: Generate new token at https://replicate.com/account

Model failed to load → Imagen temporarily unavailable  
✅ Fix: wait or switch to another model
```

---

## 👥 Team Members
We proudly present our awesome team:  

- 🧑‍💻 **Mohammad Mahdi Omidvar**  
- 🧑‍💻 **Mahyar Alizadeh**  
- 🧑‍💻 **Sogol Tarnabi**  
- 🧑‍💻 **Arad Chizari**  

---

© 2025 **AI Emotion-to-Art Team2** — *Innoverse Submission* 🚀  

  
