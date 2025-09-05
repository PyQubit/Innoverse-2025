# 🎨 AI Emotion-to-Art Team2

Transform Your Emotions into Stunning **AI-Generated Artworks**

---

## 📌 Navigation
- [Introduction](#-introduction)
- [How It Works](#-how-it-works)
- [Samples](#-samples)
- [README & Installation](#-readme--installation)
- [Debug](#-debug--troubleshooting)

---

## 👋 Introduction
**AI Emotion-to-Art Team2** converts user emotions (**text, voice, or image**) into symbolic visual art using AI technologies such as:

- **Whisper**
- **Ollama (Gemma3:4b)**
- **Replicate (Imagen backend)**

---

## ⚙️ How It Works
### Step 1 – Provide Emotion
Input a sentence, record your voice, or upload an image.  

### Step 2 – Emotion Recognition
A locally running **Gemma3:4b** model through Ollama classifies your emotion.  

### Step 3 – Prompt Generation
The system builds a symbolic prompt *(under 20 words)* for visualization.  

### Step 4 – Art Generation
The prompt is sent to **Replicate (Imagen backend)** and a square artwork is generated.  

---

## 🖼️ Samples
| Input | Generated Artwork |
|-------|-------------------|
| من قهرمان مسابقات برنامه نویسی شدم | ![Sample](assest/1.png) |

---

## 📥 README & Installation

### Requirements
- Python **3.13**
- Ollama installed with **Gemma3:4b** model
- Replicate API token

### Setup
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

```bash
# Ollama / Gemma3:4b Errors
“Model not found” → You haven't installed Gemma3:4b
Fix: ollama run gemma3:4b

“Cannot connect to Ollama” → Ollama service not running
Fix: Open Ollama desktop app or run ollama serve

# Replicate API Errors
HTTP 401 Unauthorized → Invalid/expired token
Fix: Generate new token at https://replicate.com/account

# Model failed to load → Imagen temporarily unavailable
Fix: wait or switch to another model
```

---

## 👥 Team Members
- **Mohammad Mahdi Omidvar**
- **Mahyar Alizadeh**
- **Sogol Tarnabi**
- **Arad Chizari**

---

© 2025 **AI Emotion-to-Art Team2** — *Innoverse Submission*
  
