# Omicron-sentiment-analysis
# Overview
This project analyzes public sentiment on the Omicron COVID-19 variant using Twitter data.
It applies Natural Language Processing (NLP) techniques to classify tweets into positive, negative, and neutral sentiments.
# Key Highlights
Processed 17,000+ tweets
Implemented VADER sentiment analysis (NLTK)
Achieved insight: ~92% tweets are neutral
Built complete NLP pipeline for social media data
# Tech Stack
Python, Pandas, NumPy, NLTK (VADER), Matplotlib, Seaborn, WordCloud
# Workflow
Data Loading → EDA → Text Preprocessing → Sentiment Analysis → Visualization
# Data Preprocessing
Removed URLs, mentions, punctuation
Lowercased text
Removed stopwords
Applied lemmatization
Converted emojis to sentiment words
# Sentiment Analysis
Used VADER (lexicon-based model)
Generated scores: positive, negative, neutral, compound
Classified tweets based on sentiment scores
# Results
Neutral: ~92%
Positive & Negative: very low
Indicates tweets were mostly informational
# Visualizations
Tweets per hour
Country-wise distribution
WordCloud
Sentiment distribution
# Future Improvements
Use BERT / Transformer models
Real-time data using Twitter API
Build dashboard using Streamlit
# Key Learnings
NLP preprocessing techniques
Sentiment analysis using VADER
Handling real-world noisy text data
