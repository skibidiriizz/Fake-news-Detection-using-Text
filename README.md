# 📰 Fake News Detection Using Text

**Duration**: February 2025 – March 2025  
**Technologies**: PyTorch, Matplotlib, NumPy, VADER, NLP

## 🔍 Overview

This project focuses on detecting fake news based purely on textual content using a custom-designed Convolutional Neural Network (CNN). The model leverages natural language processing techniques and feature engineering to classify news as real or fake with high accuracy.

## 🧠 Key Features

- 🏗️ **Custom CNN Architecture**: Implemented using PyTorch with Tanh activation and the Adagrad optimizer for effective and adaptive learning.
- 📊 **Feature Engineering**:
  - Transformed news titles and headings into 7 informative attributes.
  - Extracted features including:
    - Keyword frequency (adverbs, adjectives, gerunds, nouns, verbs)
    - Punctuation patterns
    - Grammar structure and analysis
- 🧪 **Training & Evaluation**:
  - Trained on 30,000+ labeled news samples.
  - Achieved **99% accuracy** on a 10,000-entry test dataset, showcasing strong generalization and precision.

## 📈 Libraries Used

- **PyTorch** – Model creation and training  
- **NumPy** – Numerical operations  
- **Matplotlib** – Data visualization  
- **VADER (Sentiment Analysis)** – Supplementary text polarity insights  
- **NLP Techniques** – Tokenization, POS tagging, grammar analysis

## 📁 Files

- `Fake News Detection.ipynb`: Full implementation in Jupyter Notebook

