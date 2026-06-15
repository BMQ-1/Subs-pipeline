> ## 📋 Requirements

| Tool | Purpose | Install |
|------|---------|---------|
| Python 3.10+ | Runs the script | [python.org](https://www.python.org/downloads/) |
| faster-whisper | Transcription | `pip install faster-whisper` |
| gst-translator | Translation via Gemini | `pip install gemini-srt-translator` |
| FFmpeg | Remux/embed subtitles | [ffmpeg.org](https://ffmpeg.org/download.html) |
| Gemini API Key | Powers translation | [aistudio.google.com](https://aistudio.google.com/app/apikey) (free) |

FFmpeg must be in your system PATH. GPU recommended, falls back to CPU automatically.

---

> ### ⚠️ Before You Run

> [!IMPORTANT]
> Place **pipeline.py** and **pipeline.bat** in the **same folder as your videos** before running. The script only processes videos it finds next to it.

---

> ## 🌐 Open the Interactive Guide

The full setup guide (bilingual EN/AR, with step-by-step instructions) is hosted here:

🔗 [(https://bmq-1.github.io/Subs-pipeline/)] ←

It covers every install step, the API key setup, and troubleshooting.



<br><br><br><br><br><br>



### 📋 المتطلبات

| الأداة | الغرض | التثبيت |
|--------|-------|---------|
| Python 3.10+ | تشغيل السكربت | [python.org](https://www.python.org/downloads/) |
| faster-whisper | النسخ الصوتي | `pip install faster-whisper` |
| gst-translator | الترجمة عبر Gemini | `pip install gemini-srt-translator` |
| FFmpeg | دمج الترجمة داخل الفيديو | [ffmpeg.org](https://ffmpeg.org/download.html) |
| Gemini API Key | تشغيل الترجمة | [aistudio.google.com](https://aistudio.google.com/app/apikey) (مجاني) |

لازم يكون FFmpeg مضاف إلى PATH في جهازك. وجود GPU أفضل، لكن السكربت يرجع تلقائياً إلى CPU إذا ما كان متوفر.

---

### ⚠️ قبل ما تشغّل السكربت

> [!IMPORTANT]
> حط **pipeline.py** و **pipeline.bat** في **نفس مجلد الفيديوهات** قبل ما تشغّل أي شيء. السكربت يعالج فقط الفيديوهات الموجودة في نفس مكانه

---

### 🌐 افتح الدليل التفاعلي

الدليل الكامل للإعداد (عربي/إنجليزي، خطوة بخطوة) موجود هنا:

🔗 [(https://bmq-1.github.io/Subs-pipeline/)] ←

فيه كل خطوات التثبيت، إعداد مفتاح الـ API، وحلول أكثر المشاكل الشائعة.
