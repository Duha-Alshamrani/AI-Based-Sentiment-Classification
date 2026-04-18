# 💬 AI-Based Sentiment Classification for Customer Reviews

A deep learning project that classifies Amazon customer reviews into positive, neutral, or negative sentiment using NLP Transformers and BERT for deep contextual text understanding.

---

## Project Structure

| Notebook | Description |
|----------|-------------|
| `SentimentAnalysis.ipynb` | Baseline model using TF-IDF and classical ML |
| `BERT_Sentiment.ipynb` | Deep learning model using NLP Transformers and BERT *(in progress)* |

---

## Baseline Model

The baseline uses classical machine learning approaches to establish a performance benchmark:

- Random Forest
- Multinomial Naive Bayes
- LinearSVC
- Stacking Ensemble (combines all three)

---

## Deep Learning Model *(In Progress)*

Fine-tuning a pretrained BERT model for multi-class sentiment classification with:

- Transformer attention layers for contextual understanding
- Class weighting to handle imbalanced data
- AdamW optimizer with early stopping
- End-to-end inference pipeline

---

## Dataset

Amazon Reviews — Cell Phones and Accessories from Kaggle.
Download from: https://www.kaggle.com/datasets/kritanjalijain/amazon-reviews
Place `sample.json` in the same folder as the notebook before running.

---

## Built with

Python, PyTorch, HuggingFace Transformers, Scikit-learn, NLTK, Matplotlib, Seaborn

---

## How to run

1. Clone the repo
2. Run `pip install transformers torch scikit-learn nltk imbalanced-learn matplotlib seaborn`
3. Download the dataset and place it in the same folder
4. Open the notebook you want to run and run all cells

---

## About

A university team project at Umm Al-Qura University.
