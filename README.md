# 🚀 AI YouTube Influencer Intelligence Platform

An AI-powered analytics platform that helps marketing teams analyze YouTube channels, discover trending topics, predict engagement, and optimize content strategy.  
Built during the **AI Agent Hackathon (3 days)** by Product Space.

---

## ✨ Features
- 📊 Advanced channel analytics (views, likes, comments, engagement trends)  
- 🔍 Trending topics extraction & optimal posting time prediction  
- 🤖 AI-powered content recommendations  
- 🎯 Competitor analysis & benchmarking  
- 😊 Sentiment analysis on video comments  
- 🔥 Future trend predictions for creators  

---

## ⚙️ Tech Stack
- **Frontend:** Streamlit  
- **Data & Visualization:** Pandas, NumPy, Plotly, Seaborn, Altair, WordCloud, Matplotlib  
- **AI & NLP:** Hugging Face API, TextBlob  
- **Database (Optional):** MongoDB for search history & caching  
- **APIs:** YouTube Data API v3, Hugging Face Transformers  

---

## 📦 Installation
Clone the repo and install dependencies:

git clone https://github.com/<your-username>/youtube-analytics-app.git
cd youtube-analytics-app
pip install -r requirements.txt

---

## 🔑 API Setup
**1. YouTube Data API v3**
- Go to Google Cloud Console
- Enable YouTube Data API v3
- Create an API key

**2. Hugging Face API**
- Sign up at Hugging Face
- Navigate to Settings → Access Tokens
- Create a Read access token

**3. Environment Variables**
- Create a .env file in the project root and add:
YOUTUBE_API_KEY=your_youtube_api_key
HF_API_TOKEN=your_huggingface_token

## ▶️ Run the App
streamlit run app.py

--

The app will open in your browser at http://localhost:8501.
