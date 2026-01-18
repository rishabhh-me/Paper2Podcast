# 🎙️ Paper2Podcast

Convert PDFs into podcast-style audio using AI.

Paper2Podcast transforms research papers, articles, and documents into
listener-friendly audio summaries, making long-form content easy to consume
on the go.

---

## 🚀 Features

- Upload PDF documents
- Generate podcast-style audio narration
- Focused summaries based on user queries
- Adjustable tone and length
- Transcript generation
- Clean Gradio-based UI

---

## 🧠 How It Works

1. Upload a PDF file
2. Optionally provide:
   - A URL for context
   - A specific question or topic
3. The AI model:
   - Extracts text
   - Summarizes key content
   - Converts it into natural-sounding speech
4. Audio and transcript are returned to the user

---

## 🛠️ Tech Stack

- Python
- Gradio
- Hugging Face (remote inference)
- Generative AI models

---

## ▶️ Run Locally

```bash
git clone https://github.com/rishabhh-me/Paper2Podcast.git
cd Paper2Podcast
pip install -r requirements.txt
python podcast_app.py
