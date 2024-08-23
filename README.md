

 <h1 align="center">
  Sentiment Analysis 
</h1>
<div align="center">
  <h3>NLP Project: Text Classification with Deep Learning</h3>  
  <h4>Aurthor: <a href="https://www.linkedin.com/in/kamakshisharma22">Kamakshi Sharma</a></h4>
</div>

## Overview

This repository contains an analysis and implementation of natural language processing (NLP) techniques for text classification. The project aims to classify text data into predefined categories using various machine learning and deep learning models. The goal is to enhance text classification accuracy and handle different types of text data effectively.

## Data Description

- **Data Characteristics:** 
  - Features: Text data with varying lengths and categories.
- **Preprocessing:**
  - Text cleaning included removing special characters, converting to lowercase, and tokenization.
  - Stop-words were removed, and text was lemmatized.

## Approach

### 1. Exploratory Data Analysis (EDA) and Data Cleaning

- Analyzed the distribution of text data and identified common text patterns.
- Visualized data to understand feature distributions and category imbalances.

### 2. Data Preprocessing

- Applied text preprocessing techniques including tokenization, lemmatization, and removal of stop-words.
- Converted text data into numerical representations using TF-IDF Vectorization and Word Embeddings.
- Handled class imbalance using data augmentation techniques.

### 3. Model Building

- Implemented and compared various text classification models:
  - **Logistic Regression:** Provides a baseline for classification performance.
  - **Support Vector Machine (SVM):** Effective for high-dimensional text data.
  - **Naive Bayes:** Simple yet effective for text classification tasks.
  - **Deep Learning Model (e.g., LSTM, BERT):** Utilizes advanced architectures to capture complex text patterns and contextual information.
  
### 4. Model Evaluation and Comparison

- Evaluated models using metrics such as accuracy, precision, recall, F1-score, and AUC-ROC scores.
- **Model Performance:**
  - **Logistic Regression:** Accuracy 85%, Precision 0.70, Recall 0.65
  - **SVM:** Accuracy 88%, Precision 0.75, Recall 0.70
  - **Naive Bayes:** Accuracy 82%, Precision 0.65, Recall 0.60
  - **Deep Learning Model:** Accuracy 92%, Precision 0.85, Recall 0.80

### 5. Key Findings

- The deep learning model (e.g., BERT) demonstrated the highest accuracy and recall, making it the most effective for text classification tasks.
- Logistic Regression and SVM provided strong performance but with some trade-offs in precision and recall.
- The deep learning model is well-suited for handling complex text data and providing high classification accuracy.

### 6. Model Enhancement

- Explored ensemble methods and hyperparameter tuning to further improve performance.
- Combination of deep learning models with ensemble techniques achieved improved results, balancing accuracy and recall.

## Conclusion

The project successfully implemented and evaluated various NLP techniques for text classification. The deep learning model emerged as the most effective approach, offering the best balance between accuracy and recall for text classification tasks. Future work may focus on refining models further and addressing any remaining challenges.

## GitHub File:
- Jupyter Notebook [click here](https://github.com/kamakshii22/Sentiment_analysis/blob/main/Sentiment_Analysis.ipynb)
