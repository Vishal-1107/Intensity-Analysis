# Intensity-Analysis

### Intensity Analysis using NLP and Python

## Project Overview

The objective of this project is to develop an intelligent system using Natural Language Processing (NLP) to predict the intensity in text reviews. By analyzing various parameters and processing data, the system aims to predict intensity categories such as happiness, angriness, or sadness. This predictive capability will enable proactive process optimization and contribute to overall customer satisfaction.

## Models Used

The following machine learning models were employed in the project:

1. Naive Bayes
2. Random Forest
3. Logistic Regression

## Model Performance

The accuracy achieved based on each model during evaluation is as follows:

- Naive Bayes: 77%
- Random Forest: 61%
- Logistic Regression: 77%

## Getting Started

### Prerequisites

Make sure you have the following dependencies installed:

- **Python:**
   - Ensure that Python is installed on your system. You can download it from the [official Python website](https://www.python.org/downloads/).
- **Python Libraries:**
   -*Install the required Python libraries by running the following command:
   - import pandas as pd
   - import numpy as np
   - import nltk
   - import re
   - nltk.download("stopwords")
   - nltk.download("punkt")
- **Visualisation Library**
  -import matplotlib.pyplot as plt

- **Feature Transformation Library**
  -from sklearn.feature_extraction.text import CountVectorizer, TfidfVectorizer
  -from sklearn.model_selection import train_test_split
  -from sklearn.ensemble import RandomForestClassifier
  -from sklearn.linear_model import LogisticRegression
  -from sklearn.naive_bayes import MultinomialNB

- **Classification Report and model evaluation**
  -from sklearn.metrics import roc_auc_score, classification_report
     
