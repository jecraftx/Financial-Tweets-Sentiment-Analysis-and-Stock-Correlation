# 📊 Financial Tweets Sentiment Analysis and Stock Correlation

This project explores the relationship between **Twitter sentiment** and **stock market returns** using state-of-the-art NLP models.  
We investigate whether investor sentiment on social media can be used to reliably predict short-term stock price movements.

## 🔍 Overview
- **Dataset**: [Tweet Sentiment’s Impact on Stock Returns](https://www.kaggle.com/datasets/sowinska/tweet-sentiments-impact-on-stock-returns) 
- **Models Tested**:
  - Bi-LSTM (baseline sequential model)
  - BERT (fine-tuned for financial sentiment)
  - RoBERTa-Twitter (pretrained on Twitter data)
  - FinBERT (domain-specific financial model)
  - Hybrid architectures combining NLP embeddings with market indicators
- **Evaluation Metrics**: Accuracy & F1 score across 1-, 2-, 3-, and 7-day return horizons.

## 🚀 Key Findings
- Transformer-based models (BERT, RoBERTa-Twitter) significantly outperform sequential baselines.
- Hybrid models (e.g., RoBERTa-Twitter + numeric features) achieve the best predictive accuracy.
- Sentiment signals provide valuable short-term predictive power, especially for highly sentiment-reactive stocks.



