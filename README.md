# Task 4: Sentiment Analysis using NLP

This repository contains Task 4 of the CodTech Data Analysis Internship. It involves analyzing the sentiment of customer reviews using basic NLP techniques.

## 🎯 Objective
To classify customer reviews into **positive**, **neutral**, or **negative** sentiments using NLP.

## 📁 Files Included
- `customer_reviews.csv` — Synthetic dataset of 500 text reviews
- `sentiment_analysis.ipynb` — Jupyter notebook with data generation, sentiment classification, and visualization
- `README.md` — Description of the task and how to run it

## 🧪 Sentiment Analysis Method
- Used `TextBlob` to compute sentiment polarity scores
- Classified sentiment based on score ranges:
  - polarity > 0.1 → positive
  - polarity < -0.1 → negative
  - otherwise → neutral

## 📊 Outputs
- Bar chart of predicted sentiment distribution
- Confusion matrix comparing actual vs predicted labels
- Classification report with precision, recall, F1-score

## 🚀 How to Run
1. Install required libraries:
- Pandas
- Numpy
- Matplotlib
- Seaborn
- Textblob
- Scikit-learn

2.Open the Jupyter notebook:

-Then run `jupyter notebook sentiment_analysis.ipynb`
