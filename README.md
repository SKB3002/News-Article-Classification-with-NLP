# News Article Classification

This project implements a multi-class text classification system to automatically categorize news articles into domains such as **Business, Politics, Sports, Entertainment, and Wellness**.

## Overview
- Multi-class classification on real-world news data
- Designed for scalable and automated content categorization
- Emphasis on both performance and interpretability

## Approach
- Text preprocessing and exploratory data analysis (EDA)
- Feature extraction: Bag of Words, TF-IDF, Word2Vec
- Models evaluated: Logistic Regression, Naive Bayes, SVM
- Cross-model comparison using Accuracy and F1-score

## Results
- **Best model:** Support Vector Machine (SVM) with TF-IDF
- Consistent performance across diverse categories
- Clear separation driven by domain-specific vocabulary

## Key Insights
- Topic classification is driven more by named entities and institutional language than writing style
- Sparse TF-IDF features preserved discriminative signals better than semantic embeddings
- Feature analysis revealed intuitive, category-specific keywords

## Tech Stack
Python, scikit-learn, Gensim, NumPy, Matplotlib, Docker, FastAPI

## How to Run
```bash
pip install -r requirements.txt
jupyter notebook notebook.ipynb
