# 💬 Sentiment Analysis & NLP Pipeline
> Applied to 15,000 Disneyland Reviews

[![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)]()
[![BERT](https://img.shields.io/badge/BERT-4285F4?style=flat&logo=google&logoColor=white)]()
[![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat)]()

## Overview
Comprehensive NLP pipeline on 15,000 Disneyland park reviews covering sentiment classification, text summarization, named entity recognition, and n-gram analysis using BERT and traditional ML.

## Dataset
- Source: Disneyland Reviews (Kaggle)
- Size: 15,000 reviews
- Task: Sentiment classification (1-5 star ratings)

## Results
- BERT: 89% sentiment classification accuracy
- 4-7% accuracy improvement via T5 summarization preprocessing pipeline
- NER identifies locations, organizations, entities
- Word cloud and n-gram analysis of key themes

## NLP Tasks
1. Text Preprocessing — contractions, tokenization, stopwords, lemmatization (NLTK + spaCy)
2. Exploratory Analysis — rating distribution, word clouds, n-gram analysis, NER
3. Sentiment Classification — BERT, Logistic Regression, SVM, Naive Bayes, TextBlob (TF-IDF)
4. Text Summarization — extractive (Summa) and abstractive (T5 transformer), ROUGE evaluation

## Tech Stack
Python | BERT | T5 | PyTorch | Hugging Face | NLTK | spaCy | Scikit-learn | Pandas | WordCloud

## How to Run
```bash
git clone https://github.com/Phoenixking-04/Sentiment-Analysis-NLP.git
pip install pandas scikit-learn nltk spacy transformers torch wordcloud textblob sumy rouge-score matplotlib seaborn
python -m spacy download en_core_web_sm
jupyter notebook NLP.ipynb
```

---
> 🔗 Developer: [Kalyankumar Sandireddy](https://kalyankumar-sandireddy.online)
