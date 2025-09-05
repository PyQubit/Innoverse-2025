# 🎨 AI Emotion-to-Art Team2

Transform Your Emotions into **AI-Generated Artworks**  
تبدیل احساسات شما به **آثار هنری تولید شده توسط هوش مصنوعی**

---

## 📌 Table of Contents | فهرست مطالب
- [👋 Introduction | مقدمه](#-introduction--مقدمه)
- [⚙️ How It Works | نحوه عملکرد](#️-how-it-works--نحوه-عملکرد)
- [🖼️ Samples | نمونه‌ها](#️-samples--نمونهها)
- [📥 Installation & Setup | نصب و راه‌اندازی](#-installation--setup--نصب-و-راهاندازی)
- [🛠️ Debug / Troubleshooting | خطاها و اشکال‌زدایی](#️-debug--troubleshooting--خطاها-و-اشکالزدایی)
- [👥 Team Members | اعضای تیم](#-team-members--اعضای-تیم)

---

## 👋 Introduction | مقدمه
**English:**  
AI Emotion-to-Art Team2 is a project that converts user emotions (**text, voice, or image**) into symbolic visual artworks using modern AI technologies:  

- **Whisper** (speech-to-text)  
- **Ollama (Gemma3:4b)** (emotion recognition)  
- **Replicate (Imagen backend)** (art generation)  

**فارسی:**  
پروژه AI Emotion-to-Art Team2 احساسات کاربر (**متن، صدا یا تصویر**) را به آثار هنری نمادین تبدیل می‌کند. این پروژه از فناوری‌های هوش مصنوعی مدرن استفاده می‌کند، شامل:  

- **Whisper** (تبدیل گفتار به متن)  
- **Ollama (Gemma3:4b)** (تشخیص احساسات)  
- **Replicate (Imagen backend)** (تولید اثر هنری)  

---

## ⚙️ How It Works | نحوه عملکرد
**English:**  
1. Provide Emotion → Input a sentence, record your voice, or upload an image.  
2. Emotion Recognition → The **Gemma3:4b** model classifies your emotion.  
3. Prompt Generation → A symbolic prompt (under 20 words) is created.  
4. Art Generation → The prompt is sent to **Replicate** to generate artwork.  

**فارسی:**  
۱. دریافت احساس → وارد کردن یک جمله، ضبط صدا یا بارگذاری تصویر.  
۲. تشخیص احساس → مدل **Gemma3:4b** احساس شما را طبقه‌بندی می‌کند.  
۳. تولید پرامپت → یک پرامپت نمادین (کمتر از ۲۰ کلمه) ساخته می‌شود.  
۴. تولید هنر → پرامپت به **Replicate** ارسال شده و اثر هنری ایجاد می‌شود.  

---

## 🖼️ Samples | نمونه‌ها
**Example | مثال:**  

| Input | Generated Artwork |
|-------|-------------------|
| من قهرمان مسابقات برنامه نویسی شدم | ![Sample](1.png) 

---

## 📥 Installation & Setup | نصب و راه‌اندازی

### ✅ Requirements | پیش‌نیازها
- Python **3.13**
- Ollama with **Gemma3:4b** model installed
- Replicate API token

### ⚡ Setup | راه‌اندازی
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

## 🛠️ Debug / Troubleshooting | خطاها و اشکال‌زدایی

```bash
# Ollama / Gemma3:4b Errors
“Model not found” → You haven't installed Gemma3:4b
Fix: ollama run gemma3:4b

“Cannot connect to Ollama” → Ollama service not running
Fix: Start Ollama desktop app or run ollama serve

# Replicate API Errors
HTTP 401 Unauthorized → Invalid/expired token
Fix: Generate new token at https://replicate.com/account

Model failed to load → Imagen temporarily unavailable
Fix: wait or switch to another model
```


## 👥 Team Members | اعضای تیم
**English:**  
- **Mohammad Mahdi Omidvar**  
- **Mahyar Alizadeh**  
- **Sogol Tarnabi**  
- **Arad Chizari**  

---

© 2025 **AI Emotion-to-Art Team2** — *Innoverse Submission*    

  
