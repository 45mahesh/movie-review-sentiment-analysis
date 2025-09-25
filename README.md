# 🎬 Movie Review Sentiment Analysis 📊

[![Python](https://img.shields.io/badge/Python-3.9-blue)](https://www.python.org/)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)
[![Status](https://img.shields.io/badge/Project-Completed-brightgreen)]()

A machine learning project that uses NLP and Naive Bayes to classify IMDb movie reviews as **positive** or **negative** 🎯

---

## 🧠 Project Overview

This project applies natural language processing (NLP) to perform sentiment analysis on the [IMDB dataset](https://ai.stanford.edu/~amaas/data/sentiment/).

**Model used**: Multinomial Naive Bayes  
**Accuracy**: ~85% on test data

---

## 🗃️ Dataset

- `IMDB_small.csv` — 10,000 movie reviews
- Originally 50,000 reviews, trimmed to avoid GitHub size limits

---

## 🛠️ Technologies Used

- Python 🐍
- Scikit-learn
- NLTK
- Pandas
- Matplotlib
- Jupyter Notebook

---

## 📁 Project Structure

```bash
movie-review-sentiment-analysis/
│
├── data/
│   └── IMDB_small.csv
├── notebooks/
│   └── sentiment_analysis.ipynb
├── .gitignore
├── LICENSE
└── README.md
