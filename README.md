# 📰 Fake News Detection Using Machine Learning
This project implements a machine learning pipeline to detect fake news based on article text. With the growing concern over misinformation, especially across digital media, this project demonstrates how data science can be used to classify news articles as either real or fake using natural language processing (NLP) and classification algorithms.

🎯 Project Objectives
Clean and preprocess news data

Vectorize text data using NLP techniques

Build and evaluate classification models

Deploy a fake news detector using machine learning

🧰 Tools & Technologies Used
Python 3

Jupyter Notebook

Pandas – data loading and manipulation

NumPy – numerical operations

NLTK – natural language processing and text cleaning

Scikit-learn (sklearn) – model building, evaluation, and pipeline creation

TfidfVectorizer – for converting text into numerical features

🔄 Steps in the Project
1. Data Loading
Loaded the dataset using pandas, which contains article title, text, and label (fake or real).

2. Text Cleaning & Preprocessing
Removed nulls and irrelevant characters

Tokenized text

Removed stopwords using NLTK

Applied stemming or lemmatization for word normalization

3. Feature Engineering
Used TfidfVectorizer to convert text into numerical feature vectors suitable for machine learning

4. Model Training & Evaluation
Built classification models including:

Logistic Regression

Passive Aggressive Classifier

Evaluated models using accuracy, confusion matrix, and classification reports

5. Model Testing
Tested the pipeline with sample inputs to check prediction output (FAKE or REAL)

✅ Project Outcome
The fake news detection model was successfully trained and evaluated with high accuracy. The final pipeline demonstrates how text data can be processed, vectorized, and used in supervised learning to flag misinformation automatically.

📌 Future Improvements
Integrate a front-end UI for user input

Expand dataset with recent news

Add deep learning models like LSTM for improved results

