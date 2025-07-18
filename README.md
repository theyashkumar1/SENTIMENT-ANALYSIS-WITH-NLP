# SENTIMENT-ANALYSIS-WITH-NLP

COMPANY: CodTech IT Solutions

NAME: Yash Kumar

INTERN ID: CT06DG602

DOMAIN: Machine Learning

DURATION: 6 Weeks

MENTOR: Neela Santosh

This project performs sentiment analysis on movie reviews using the IMDB Dataset and the TF-IDF approach for feature extraction.

📁 Dataset

Dataset used: https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews

To run this notebook:

1.Download the dataset from the above link.

2.Place the file (IMDB Dataset.csv) in the same folder as this notebook.

3.Run the notebook in Jupyter, Colab, or any Python environment.

IMDB Movie Review Sentiment Analysis

📌Overview

This project aims to classify IMDB movie reviews as positive or negative using traditional machine learning and natural language processing (NLP) techniques. By leveraging TF-IDF vectorization and Logistic Regression, we create a lightweight yet highly accurate sentiment analysis model, suitable for both educational purposes and real-world applications.

1. Text Preprocessing

Convert to lowercase

Remove punctuation and numbers

Remove HTML tags

Clean the text using regex

2. Feature Extraction

Apply TF-IDF Vectorizer to convert textual data into numerical features

Use max_features=5000 and stop_words='english' to reduce dimensionality and focus on important terms

3. Label Encoding
   
Sentiments are mapped: positive → 1, negative → 0

4. Model Training

Use Logistic Regression, a binary classifier known for its speed and effectiveness

Split dataset into 80% training and 20% testing

5. Evaluation Metrics
   
Accuracy Score: ~88%

Classification Report: Includes precision, recall, F1-score

Confusion Matrix: Gives insight into true/false positives and negatives

6. Word Importance
   
Extract top 10 positive and negative keywords based on logistic regression coefficients

Top Positive Words: great, excellent, amazing, perfect, wonderful

Top Negative Words: worst, awful, boring, waste, poor

💡Model Performance

Metric	Score
Accuracy	88.39%
Precision	~0.88
Recall	~0.88
F1 Score	~0.88

The model performs consistently across both sentiment classes.

👨‍💻Tech used

Python

Pandas

NumPy

Scikit-learn: For ML pipeline, model training, and evaluation

Regex (re): For text cleaning

TF-IDF Vectorizer: To handle textual data

⚡Key Highlights
 
Clean and minimal code using only traditional ML — no deep learning

Interactive review prediction function

Insightful feature extraction showing most influential words

Lightweight model, fast training, good accuracy — ideal for small-scale NLP projects

