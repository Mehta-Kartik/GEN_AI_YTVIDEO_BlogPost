text
# YouTube → Blog Post Generator

![Demo Screenshot](demo.gif)

> **Convert YouTube videos into professional blog posts using CrewAI multi-agent system + Groq Llama 3.3 (free tier)**

[![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=Streamlit&logoColor=white)](https://streamlit.io)
[![CrewAI](https://img.shields.io/badge/CrewAI-596CFF?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMzIiIGhlaWdodD0iMzIiIHZpZXdCb3g9IjAgMCAzMiAzMiIgZmlsbD0ibm9uZSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KPGNpcmNsZSBjeD0iMTYiIGN5PSIxNiIgcj0iMTYiIGZpbGw9IiM1OTZDQ0YiLz4KPC9zdmc+Cg==)](https://crewai.com)
[![Groq](https://img.shields.io/badge/Groq-00D2FF?style=for-the-badge&logo=Groq&logoColor=white)](https://groq.com)

## 🚀 Features

| Feature | Status |
|---------|--------|
| 🎬 **YouTube Channel Search** | ✅ Any public channel |
| 🤖 **Multi-Agent AI** | ✅ Researcher + Writer agents |
| ⚡ **Groq Llama 3.3 70B** | ✅ Free tier, blazing fast |
| 📱 **Streamlit UI** | ✅ Clean, professional interface |
| 📥 **Markdown Download** | ✅ Professional .md export |
| 🔧 **Custom Channels** | ✅ Paste any `/videos` URL |

## 🎯 How It Works

User inputs: Topic + YouTube Channel URL

Researcher Agent → Scrapes & finds top 3 relevant videos

Writer Agent → Creates engaging blog post from video research

Streamlit → Renders & downloads Markdown

text

## 📦 Quick Start

### 1. Clone & Install
```bash
git clone <your-repo>
cd youtube-blog-generator
pip install -r requirements.txt
2. Get Free Groq API Key
Go to console.groq.com

Sign up (free tier: 1M+ tokens/day)

Copy your gsk_... API key

3. Run App
streamlit run app.py
4. Generate Blog
Topic: "Data Science Mentorship Program"
Channel: https://www.youtube.com/@krishnaik06/videos
[Generate] → 📝 Blog Post + ⬇️ Download
🎛️ Streamlit Interface
┌─────────────────────┬─────────────────────────────────┐
│ Sidebar:            │ 🎬 YouTube → Blog Post          │
│ -  🔑 Groq API Key   │                                 │
│ -  📌 Topic          │ [FULL WIDTH CLEAN BLOG]         │
│ -  📺 Channel URL    │                                 │
│ -  🤖 Groq Model     │ ⬇️ Download blog_post.md        │
│ -  🚀 [Generate]     │                                 │
└─────────────────────┘─────────────────────────────────┘
🛠️ Project Structure
youtube-blog-generator/
├── app.py              # Streamlit UI
├── tools.py           # YouTube scraping tool
├── agents.py          # CrewAI agents (optional)
├── tasks.py           # CrewAI tasks (optional)
├── requirements.txt   # Dependencies
├── README.md          # This file!
└── new_blog_post.md   # Generated output
