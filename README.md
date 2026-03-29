# IMDB Movie Review Sentiment Analysis Using Machine Learning

# Overview

This project focuses on building a machine learning model to classify IMDb movie reviews as positive or negative. It applies Natural Language Processing (NLP), feature engineering, and multiple classification algorithms to analyze text data and predict sentiment accurately.

# Objectives
Predict sentiment (positive or negative) from movie reviews
Perform text preprocessing and cleaning
Convert text into numerical features using TF-IDF and Word2Vec
Train and compare multiple machine learning models
Evaluate model performance using standard metrics


# Dataset Description
Source: IMDb dataset
Total records: 50,000 reviews

# Features:
Review text
Sentiment label (positive/negative)
Balanced dataset with equal distribution of classes
# Methodology
## Data Exploration and Preprocessing
      Checked dataset size and missing values
      Analyzed sentiment distribution
      Measured review length distribution

# Cleaned text by:
     Lowercasing
     Removing punctuation and special characters
     Removing stopwords
     Applying lemmatization
# Feature Engineering
## TF-IDF Vectorization
      Converted text into numerical format
      Used unigrams and bigrams
      Limited features to top 5000 terms
## Word2Vec Embeddings
      Generated dense vector representations
      Captured semantic meaning of words
      Averaged vectors for each review
## Additional Text Features
     Word count
    Character count
    Average word length
    Combined with TF-IDF features


# Model Development
## Trained multiple classification models:

## Logistic Regression
Naive Bayes
Support Vector Machine (SVM)
Random Forest
## Model Evaluation

Accuracy
Precision
Recall
F1-score
ROC-AUC

# Best performance achieved:

Logistic Regression: 89% accuracy
SVM: 88% accuracy
Naive Bayes and Random Forest: 85% accuracy

# Key Features
End-to-end NLP pipeline
Advanced feature engineering (TF-IDF + Word2Vec)
Multiple model comparison
Visualization using plots and word clouds
Balanced dataset handling

# Results
Logistic Regression performed best with highest accuracy
Strong classification performance across all models
Effective sentiment detection on unseen data
Textual features improved model performance

# Technologies Used
Python
Pandas
NumPy
NLTK
Scikit-learn
Gensim
Matplotlib
Seaborn

# Visualizations
Sentiment distribution plots
Review length analysis
Word clouds for positive and negative reviews
Confusion matrix for model evaluation

# Future Enhancements
Implement deep learning models such as LSTM and BERT
Deploy model as a web application
Add real-time sentiment analysis
Extend to multi-class sentiment classification

# Conclusion
This project demonstrates how machine learning and NLP techniques can be applied to analyze large-scale text data. It highlights the importance of preprocessing, feature engineering, and model selection in building an accurate sentiment analysis system.

This project demonstrates how machine learning and NLP techniques can be applied to analyze large-scale text data. It highlights the importance of preprocessing, feature engineering, and model selection in building an accurate sentiment analysis system.
