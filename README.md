# 🍕 Amazon Fine Food Reviews - Sentiment Analysis
📌 GitHub Repo · 📊 Kaggle Dataset · 🛠️ NLP · 🤖 ML/DL Models

## 📜 Project Overview
This project tackles sentiment analysis on Amazon food product reviews using NLP and machine learning. The goal is to classify reviews as positive (4-5 stars) or negative (1-2 stars) based on text content.

## 🔗 Dataset Source:
Kaggle - Amazon Fine Food Reviews

## 🎯 Problem Statement
Input: Review text (Text column) + metadata (e.g., Score, Helpfulness).

Output: Binary sentiment classification (Positive or Negative).

Extended Challenge: 5-class rating prediction (1-5 stars).

## 🛠️ Techniques Used
### 1. Data Preprocessing
Text cleaning (lowercase, HTML removal, contractions, stopwords).

Lemmatization (spaCy/NLTK).

Handling imbalanced data (if applicable).

### 2. Feature Extraction
Bag-of-Words (BoW) & TF-IDF.

Word Embeddings (Word2Vec, GloVe).

Transformer Embeddings (BERT, DistilBERT).

### 3. Models Implemented
Model	Accuracy (Sample)	Use Case
Logistic Regression	~89%	Baseline
Random Forest	~86%	Traditional ML
LSTM	~91%	Deep Learning
BERT (Hugging Face)	~93%	State-of-the-Art

### 4. Evaluation Metrics
Accuracy, F1-Score, ROC-AUC.

Confusion Matrix (False Positives/Negatives).

## 🚀 How to Run
Install dependencies:

```bash
Copy
pip install pandas numpy scikit-learn nltk spacy transformers tensorflow
python -m spacy download en_core_web_sm
```
### Download the dataset from Kaggle and place it in data/.

### Run notebooks in order:

`data_cleaning.ipynb` →`traditional_ml.ipynb` → `deep_learning.ipynb`.

## 📌 Key Takeaways
Compared traditional ML vs. deep learning for NLP.

Leveraged pretrained transformers (BERT) for high accuracy.

Built an end-to-end pipeline: text cleaning → feature engineering → modeling.

## 🔗 Useful Links
Kaggle Notebook: TF-IDF + Logistic Regression

Hugging Face BERT Tutorial

## 🎉 Credits
Dataset: Stanford Network Analysis Project (SNAP).

Inspired by Kaggle NLP competitions.
