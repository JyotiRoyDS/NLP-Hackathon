# NEWSIFY: Real time story tracker with sentiment analysis and narrative intelligence​ 

Event Unfolder is an interactive intelligence dashboard developed to transform real-time news streams from the Amplyfi API into an explorable, analytical platform. Designed to help analysts, researchers, and decision-makers effectively manage information overload, Newsify provides dynamic narrative tracking and AI-powered summaries.

## The Problem

In finance, public relations, and market research, rapidly tracking and understanding developing news stories is crucial yet challenging. Traditional methods involve extensive manual searches and reading, causing delays, missed opportunities, and late crisis responses.

## Our Solution

Newsify addresses these issues with a multi-layered, interactive dashboard, offering instant insights and streamlined news analysis through:

### Core Features

* **Sentiment Trend & Momentum Analysis:** Visualizes sentiment scores and their rate of change, highlighting emerging trends and shifts.
* **Dynamic Filtering:** Users can filter news streams instantly by time range, keywords, entities (people and organizations).
* **Interactive Deep Dives:** Click any news article for a detailed view, including full summaries, sentiment analysis, and key highlights.
* **AI-Powered Executive Briefings:** Quickly generates concise, insightful executive summaries using Google Gemini's generative AI capabilities.

## Technology Stack

* **Data Source:** Amplyfi API
* **Backend & NLP:** Python, pandas, spaCy (NER), NLTK (VADER sentiment analysis)
* **Frontend & Visualizations:** Streamlit, Plotly
* **AI Summaries:** Google Gemini API

## Installation & Running the Application

### Step-by-step Guide:

**1. Clone the Repository**

```bash
git clone https://github.com/YOUR_USERNAME/event-unfolder.git
cd event-unfolder
```

**2. Install Dependencies**

```bash
pip install -r requirements.txt
```

**3. Run Data Collection Script** *(ensure `articles.csv` is generated)*

```bash
python data_collector.py
```

**4. Launch the Streamlit Dashboard**

```bash
streamlit run app.py
```

## Hackathon Information

This project was developed within 48 hours during the Cardiff NLP Hackathon 2025, sponsored by Amplyfi.

