# Explainable Fake News Detection using NLP and XAI

## Overview

This project implements a fake news detection system using Natural Language Processing (NLP), machine learning, and Explainable AI techniques.

The system classifies news articles as fake or real using:
- TF-IDF vectorization
- Bag of Words
- Stylometric feature engineering
- Machine learning classifiers
- SHAP explainability analysis

The project also includes external validation and domain-shift analysis to evaluate model robustness on unseen contemporary news data.

---

## Features

- Leakage-aware preprocessing
- TF-IDF and Bag of Words comparison
- Stylometric credibility indicators
- Linear SVM, Logistic Regression, and Naive Bayes models
- SHAP explainability
- External validation on recent datasets
- Domain-shift visualization
- Sankey prediction flow analysis

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- SHAP
- Matplotlib
- Seaborn
- Plotly
- NLTK

---

## Project Workflow

Dataset Collection  
→ Preprocessing  
→ Feature Extraction  
→ TF-IDF / Bag of Words  
→ Model Training  
→ Explainability Analysis  
→ External Validation  
→ Domain Shift Analysis

---

## Dataset Sources

ISOT Fake News Dataset:  
https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset

External Validation Dataset:  
https://www.kaggle.com/datasets/mahdimashayekhi/fake-news-detection-dataset

---

## Repository Structure

```text
notebooks/   -> Jupyter notebook implementation
data/        -> dataset links
outputs/     -> generated outputs/results
```

---

## Installation

```bash
pip install -r requirements.txt
```

---

## Run

```bash
jupyter notebook
```

Open:

```text
notebooks/fake_news_detection.ipynb
```

---

## Key Findings

- Linear SVM achieved the best internal performance.
- Stylometric features improved interpretability.
- SHAP helped explain model predictions.
- External validation revealed domain-shift limitations.
- Dataset bias significantly affected generalization.

---

## Author

Aditya Kumar Kapar
