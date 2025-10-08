# 📰 NewsPulse: Global News Trend Analyzer Using AI
```

## 🌍 Overview

**NewsPulse** is an **AI-powered global news analyzer** that uses **Natural Language Processing (NLP)** and **Google Gemini** to deliver real-time news insights, summaries, sentiment analysis, and interactive chatbot experiences.  
It helps users stay informed with meaningful data visualization and AI-powered Q&A on the latest trends.

```

```
## 🚀 Features

✨ **Fetch Live Global News**  
- Uses **GNews API** to fetch trending articles by topic, keyword, or country.

🧠 **AI-Powered Summaries**  
- Generates concise news summaries with **Google Gemini (1.5/2.0 Flash)**.

💬 **Interactive Gemini Chatbot**  
- Ask *any type of question* (who, what, when, why, full forms, etc.) about any news article.  
- Provides accurate contextual responses.

❤️ **Sentiment Analysis**  
- Detects tone (positive, negative, neutral) of trending articles.

🔍 **Named Entity Recognition (NER)**  
- Extracts names of people, places, and organizations using **spaCy**.

📊 **Beautiful Visualizations**  
- View sentiment distribution, top keywords, and source frequency with **Plotly** charts.

```

```
## 🧰 Tech Stack

### 🎨 Frontend
- **Streamlit** – Interactive UI for visualizing news insights and chatbot responses.

### ⚙️ Backend
- **Python** – Core backend language connecting APIs, models, and UI components.

### 🧠 AI / NLP
- **Google Gemini** – Generates intelligent summaries and contextual answers.  
- **spaCy** – Named Entity Recognition (NER) for extracting people, places, and organizations.  
- **TextBlob / NLTK** – Used for sentiment analysis and text preprocessing.

### 📊 Visualization
- **Plotly** – For creating dynamic and interactive charts (pie, bar, line).  
- **Matplotlib** – For static data visualizations and analysis plots.

### 🗄️ Database (Optional)
- **MongoDB** – Stores user profiles, chat history, and preferences securely.

### 🌐 API Source
- **GNews API** – Fetches real-time global news articles by category, keyword, or country.

### 🔒 Environment Management
- **python-dotenv** – Loads API keys and configuration securely from the `.env` file.

  ```

  ```
  
## 📁 Project Structure

newspulse/
│
├── newspulse_pkg/
│ ├── init.py
│ ├── gemini.py # Gemini AI chatbot logic
│ ├── news_api.py # News fetch and processing
│ ├── sentiment.py # Sentiment analysis functions
│ ├── ner.py # Entity extraction using spaCy
│ ├── preprocessing.py # Cleaning and keyword extraction
│ ├── viz.py # Plotly visualizations
│ ├── auth.py # User login (optional)
│ └── news_ui.py # Streamlit UI rendering
│
├── app.py # Main entry point
├── .env # API keys (Gemini, GNews)
├── requirements.txt
└── README.md

```


```

## 🔑 Environment Setup

Create a `.env` file in the root directory and add your credentials:

GEMINI_API_KEY=your_google_gemini_api_key
GNEWS_API_KEY=your_gnews_api_key

```

```


## ⚙️ Installation & Usage

1️⃣ **Clone the Repository**
```bash
git clone https://github.com/your-username/newspulse.git
cd newspulse

2️⃣ Create and Activate Virtual Environment

python -m venv .venv
.venv\Scripts\activate    # for Windows
source .venv/bin/activate # for Mac/Linux

3️⃣ Install Dependencies

pip install -r requirements.txt

4️⃣ Run the App

streamlit run app.py

```



