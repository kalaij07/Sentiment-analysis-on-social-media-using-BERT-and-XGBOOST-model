# Sentiment-analysis-on-social-media-using-BERT-and-XGBOOST-model
Hybrid sentiment analysis model combining BERT for contextual feature extraction and XGBoost for multi-class classification (Happy, Sad, Sarcasm, Irony) of social media comments. Achieved 93% accuracy and 92.6% F1-score on airline Twitter dataset with 32000 records, outperforming baseline models
Features
Contextual Understanding using BERT embeddings

High Accuracy Classification with XGBoost

Handles Imbalanced Data using SMOTE oversampling

Custom Keyword Dictionaries for improved sarcasm & irony detection

Visualization of sentiment trends, confusion matrices, and accuracy comparisons

Dataset
Source: Airline Twitter Sentiment Dataset

Size: 32,000+ comments

Format: CSV with text and sentiment labels

Tech Stack
Language: Python

Libraries: BERT, XGBoost, Scikit-learn, Pandas, Matplotlib

Preprocessing: Tokenization, Stopword Removal, SMOTE

Model Performance
Accuracy: 93%

F1-score: 92.6%

Outperformed traditional models such as SVM, Naive Bayes, and CNN-BiGRU
