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
