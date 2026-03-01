YouTube → Blog Post Generator
Convert YouTube videos into professional blog posts using CrewAI multi-agent system + Groq Llama 3.3 (free tier)

[
[
[

🚀 Features
Feature	Status
🎬 YouTube Channel Search	✅ Any public channel
🤖 Multi-Agent AI	✅ Researcher + Writer agents
⚡ Groq Llama 3.3 70B	✅ Free tier, blazing fast
📱 Streamlit UI	✅ Clean, professional interface
📥 Markdown Download	✅ Professional .md export
🔧 Custom Channels	✅ Paste any /videos URL
🎯 How It Works
text
1. User inputs: Topic + YouTube Channel URL
2. Researcher Agent → Scrapes & finds top 3 relevant videos
3. Writer Agent → Creates engaging blog post from video research
4. Streamlit → Renders & downloads Markdown
📦 Quick Start
1. Clone & Install
bash
git clone <your-repo>
cd youtube-blog-generator
pip install -r requirements.txt
2. Get Free Groq API Key
Go to console.groq.com

Sign up (free tier: 1M+ tokens/day)

Copy your gsk_... API key

3. Run App
bash
streamlit run app.py
4. Generate Blog
text
Topic: "Data Science Mentorship Program"
Channel: https://www.youtube.com/@krishnaik06/videos
[Generate] → 📝 Blog Post + ⬇️ Download
🎛️ Streamlit Interface
text
┌─────────────────────┬─────────────────────────────────┐
│ Sidebar:            │ 🎬 YouTube → Blog Post          │
│ • 🔑 Groq API Key   │                                 │
│ • 📌 Topic          │ [FULL WIDTH CLEAN BLOG]         │
│ • 📺 Channel URL    │                                 │
│ • 🤖 Groq Model     │ ⬇️ Download blog_post.md        │
│ • 🚀 [Generate]     │                                 │
└─────────────────────┘─────────────────────────────────┘
🛠️ Project Structure
text
youtube-blog-generator/
├── app.py              # Streamlit UI
├── tools.py           # YouTube scraping tool
├── agents.py          # CrewAI agents (optional)
├── tasks.py           # CrewAI tasks (optional)
├── requirements.txt   # Dependencies
├── README.md         # This file!
└── new_blog_post.md  # Generated output
