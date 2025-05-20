# Sentiment Analysis of Tweets

This project demonstrates a complete pipeline for analyzing the sentiment of tweets using NLP techniques and visualizing sentiment trends using Plotly. The project focuses on classifying tweets as **positive** or **negative** using the VADER sentiment analysis tool from the `nltk` library.

---

## 📌 Abstract

Social media platforms like Twitter generate a vast amount of data reflecting public opinions. This project aims to classify such tweet data into positive and negative sentiments using Natural Language Processing (NLP) techniques. It involves preprocessing tweets, applying sentiment analysis using VADER, and visualizing sentiment trends over time.

---

## 📁 Dataset

- **Source**: [Kaggle - Data Science Tweets](https://www.kaggle.com/ruchi798/data-science-tweets)
- **Format**: CSV
- **Size**: 16.9 MB (approx. 39,000 tweets)
- **Language**: English

---

## 🔍 Methodology

### 1. Data Preprocessing
- Remove usernames, links, hashtags
- Clean unnecessary characters
- Tokenize and filter using English words from NLTK

### 2. Sentiment Analysis
- Use VADER (Valence Aware Dictionary for Sentiment Reasoning)
- Custom dictionary of terms added to improve context-specific accuracy
- Classify each tweet into:
  - Positive
  - Negative
  - Neutral
- Convert compound score to sentiment category

### 3. Data Visualization
- Count tweets by sentiment per day
- Visualize sentiment trends using Plotly
  - Green line for positive tweets
  - Red line for negative tweets

---

## 📊 Final Output

- Visual representation of tweet sentiments over time.
- Insights on how positive and negative sentiments have changed historically.

---

## ✅ Conclusion

The visualization shows:
- An **upward trend in positive sentiment** from 2010 to 2022.
- A relatively **flat trend in negative sentiment**, suggesting minimal change.

This kind of analysis is useful in:
- Brand monitoring
- Public opinion tracking
- Event-based sentiment shifts
- Marketing and audience targeting

---

## 🛠️ Tools & Libraries Used

- Python
- Pandas
- NLTK (VADER,
