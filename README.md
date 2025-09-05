# 🎨 AI Emotion-to-Art Team2

Transform Your Emotions into **AI-Generated Artworks**
تبدیل احساسات شما به **آثار هنری تولیدشده توسط هوش مصنوعی**

---

## 📌 Table of Contents | فهرست مطالب

* [👋 Introduction | مقدمه](#-introduction--مقدمه)
* [⚙️ How It Works | نحوه عملکرد](#-how-it-works--نحوه-عملکرد)
* [🖼️ Samples | نمونه‌ها](#-samples--نمونه‌ها)
* [📥 Installation & Setup | نصب و راه‌اندازی](#-installation--setup--نصب-و-راه‌اندازی)
* [🛠️ Debug / Troubleshooting | خطاها و اشکال‌زدایی](#-debug--troubleshooting--خطاها-و-اشکال‌زدایی)
* [👥 Team Members | اعضای تیم](#-team-members--اعضای‌تیم)
* [🏆 Achievements | افتخارات](#-achievements--افتخارات)

---

## 👋 Introduction | مقدمه

**English:**
AI Emotion-to-Art Team2 is a **gold-medal winner** in the **AI Section** of the **Innoverse 2025 International Invention & Innovation Expo**. Held on **August 24, 2025**, this expo focused on Metaverse and blockchain technologies and featured over 30 judging categories. Our project converts user emotions (text, voice, image) into symbolic visual artworks using advanced AI technologies:

* **Whisper** (speech-to-text)
* **Ollama (Gemma3:4b)** (emotion recognition)
* **Replicate (Imagen backend)** (art generation)

Visit the official expo site for more information: [Innoverse 2025](http://innoverse.world)

**فارسی:**
تیم AI Emotion-to-Art Team2 موفق به کسب **مدال طلا در بخش هوش مصنوعی** در **نمایشگاه بین‌المللی Innoverse 2025** شد. این رویداد در تاریخ **۲۴ آگوست ۲۰۲۵** برگزار شد و تمرکز آن بر فناوری‌های متاورس و بلاک‌چین بوده و در بیش از ۳۰ بخش داوری انجام شد. پروژه ما با استفاده از فناوری‌های پیشرفته هوش مصنوعی، احساسات کاربر (متن، صدا، تصویر) را به آثار بصری نمادین تبدیل می‌کند:

* **Whisper** (تبدیل گفتار به متن)
* **Ollama (Gemma3:4b)** (تشخیص احساسات)
* **Replicate (Imagen backend)** (تولید اثر هنری)

برای کسب اطلاعات بیشتر به سایت رسمی مراجعه کنید: [Innoverse 2025](http://innoverse.world)

---

## ⚙️ How It Works | نحوه عملکرد

**English:**

1. Provide an emotion (text, voice, or image)
2. Emotion recognition via **Gemma3:4b** (Ollama)
3. Generate a symbolic prompt
4. Use **Replicate** to generate AI artwork

**فارسی:**
۱. دریافت احساس (متن، صدا، تصویر)
۲. تشخیص احساس با مدل **Gemma3:4b** (از طریق Ollama)
۳. تولید یک پرامپت نمادین
۴. ارسال به **Replicate** برای تولید اثر هنری

---

## 🖼️ Samples | نمونه‌ها

**English / فارسی (Example):**

| Input                              | Generated Artwork                                   |
| ---------------------------------- | --------------------------------------------------- |
| من قهرمان مسابقات برنامه نویسی شدم | <img src="1.png" alt="Sample Artwork" width="600"/> |

---

## 📥 Installation & Setup | نصب و راه‌اندازی

### Requirements | پیش‌نیازها

* Python **3.13**
* Ollama with **Gemma3:4b** model installed
* Replicate API token

### Setup | راه‌اندازی

```bash
# Install Ollama → https://ollama.com/
# Run: ollama run gemma3:4b

python -m venv env
source env/bin/activate   # (Windows → .\env\Scripts\activate)

pip install openai-whisper replicate ollama gradio

# Set Replicate API token
export REPLICATE_API_TOKEN="your_token_here"
# or (Windows)
setx REPLICATE_API_TOKEN "your_token_here"

# Run Gradio application
```

---

## 🛠️ Debug / Troubleshooting | خطاها و اشکال‌زدایی

```bash
# Ollama / Gemma3:4b Errors
“Model not found” → Gemma3:4b model not installed
Fix: ollama run gemma3:4b

“Cannot connect to Ollama” → Ollama service not active
Fix: Launch Ollama app or run ollama serve

# Replicate API Errors
HTTP 401 Unauthorized → Invalid or expired token
Fix: Generate new token at https://replicate.com/account

Model failed to load → Imagen may be temporarily unavailable
Fix: Wait and retry, or switch to another model
```

---

## 👥 Team Members | اعضای تیم

* **Mohammad Mahdi Omidvar**
* **Mahyar Alizadeh**
* **Sogol Tarnabi**
* **Arad Chizari**

---

## 🏆 Achievements | افتخارات

**English:**

* Gold Medal Winner in **AI Section**, Innoverse 2025 ([Official Results PDF](http://innoverse.world/innoverse%202025%20challenges%20result.pdf))
* Recognized internationally for an innovative AI project converting emotions into artworks

**فارسی:**

* مدال طلا در **بخش هوش مصنوعی**، Innoverse 2025 ([فایل نتایج رسمی](http://innoverse.world/innoverse%202025%20challenges%20result.pdf))
* شناخته‌شده در سطح بین‌المللی برای پروژه‌ای نوآورانه که احساسات را به آثار هنری تبدیل می‌کند

---

© 2025 **AI Emotion-to-Art Team2** — *Gold Medal Winner, AI Section, Innoverse 2025*


  
