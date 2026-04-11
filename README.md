# NLP-Based Product Review Sentiment Analysis

## Project Overview

This project performs Aspect-Based Sentiment Analysis (ABSA) on Amazon product reviews using Natural Language Processing and Machine Learning techniques.

The system automatically processes customer reviews, extracts discussed product features, identifies sentiment associated with each feature, and classifies reviews as Positive or Negative.

---

## Problem Statement

Manual analysis of thousands of customer reviews is inefficient and makes it difficult for businesses to identify specific customer dissatisfaction points.

---

## Solution

Developed a complete NLP pipeline that:

- Loads and balances Amazon product review data using stratified sampling
- Cleans and preprocesses raw review text
- Extracts product-related features using POS tagging
- Performs dependency parsing for syntax analysis
- Identifies feature–sentiment relationships
- Classifies sentiment using Machine Learning models

---

## Features

- Stratified Sampling for Balanced Dataset
- Text Cleaning and Noise Removal
- Tokenization, Stopword Removal, Lemmatization
- POS Tagging for Product Feature Extraction
- Dependency Parsing Visualization
- Feature–Sentiment Pair Extraction
- TF-IDF Feature Vectorization
- Logistic Regression Sentiment Classification
- Confusion Matrix and Model Evaluation
- Business Insight Generation

---

## Tech Stack

- Python
- Pandas
- NumPy
- NLTK
- spaCy
- Scikit-learn
- Matplotlib
- Seaborn
- NetworkX

---

## Machine Learning Model

**Algorithm Used:** Logistic Regression  

**Vectorization Technique:** TF-IDF  

**Classification Type:** Binary Sentiment Classification  
- Positive
- Negative

---

## Workflow Pipeline

1. Data Ingestion  
2. Stratified Sampling  
3. Text Preprocessing  
4. Feature Extraction via POS Tagging  
5. Dependency Parsing  
6. TF-IDF Vectorization  
7. Logistic Regression Training  
8. Evaluation & Prediction  

---

## Business Applications

This project can help businesses:

- Identify major customer pain points
- Track sentiment for individual product aspects
- Improve product development decisions
- Automate large-scale review analysis

---

## Future Improvements

- Multi-Class Sentiment Classification
- Transformer/BERT-based Sentiment Models
- Real-Time Dashboard Integration
- Deep Learning Enhancement

---

## Author

**Pothula Sahithya**  
Reg No: 23BLC1041
