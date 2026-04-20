# NLP-Based Product Review Sentiment Analysis

## Project Overview
This project performs Aspect-Based Sentiment Analysis (ABSA) on Amazon product reviews using Natural Language Processing and Machine Learning techniques.

The system automatically processes customer reviews, extracts discussed product features, identifies sentiment associated with each feature, and classifies reviews as Positive or Negative.

## Problem Statement
Manual analysis of thousands of customer reviews is inefficient and makes it difficult for businesses to identify specific customer dissatisfaction points, product weaknesses, and customer preferences.

## Solution
Developed a complete NLP pipeline that:

- Loads and balances Amazon review datasets using stratified sampling
- Cleans and preprocesses raw review text
- Extracts product-related aspects using POS tagging
- Performs dependency parsing for syntax understanding
- Detects feature–sentiment relationships
- Classifies reviews using Machine Learning models
- Generates visual insights for business decision-making

## Features
- Balanced Dataset Sampling
- Text Cleaning and Noise Removal
- Tokenization, Stopword Removal, Lemmatization
- POS Tagging for Aspect Extraction
- Dependency Parsing Visualization
- Feature–Sentiment Pair Detection
- TF-IDF Feature Vectorization
- Logistic Regression Classification
- Confusion Matrix Evaluation
- Business Insight Generation

## Tech Stack
- Python
- Pandas
- NumPy
- NLTK
- spaCy
- Scikit-learn
- Matplotlib
- Seaborn

## Machine Learning Model
- Algorithm: Logistic Regression
- Vectorization: TF-IDF
- Classification Type: Binary Sentiment Classification
- Accuracy Achieved: 82%

## Workflow Pipeline
- Data Collection
- Stratified Sampling
- Text Preprocessing
- Aspect Extraction
- Dependency Parsing
- TF-IDF Vectorization
- Model Training
- Prediction & Evaluation

## Business Applications
- Identify major customer pain points
- Track sentiment for specific product features
- Improve product design decisions
- Analyze large-scale customer feedback automatically
- Support e-commerce product optimization

## Future Improvements
- Multi-Class Sentiment Classification
- Transformer/BERT-based Models
- Real-Time Dashboard Integration
- Deep Learning Enhancement
- Recommendation Engine Integration

## Run

```bash
jupyter notebook
