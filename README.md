# SMS-Spam-Detection
This project implements a Machine Learning model for classifying SMS messages as spam or ham (legitimate). It demonstrates how Natural Language Processing (NLP) techniques can be applied to text data to build a reliable spam filter.

🔑 Key Features :

1.Data Preprocessing
Loaded SMS dataset (spam.csv) with messages and labels.
Removed unnecessary columns and renamed to label and message.

2.Engineered additional features:
msg_len → Length of the message
punct_count → Number of punctuation marks
word_count → Number of words

3.Exploratory Data Analysis (EDA)
Visualized spam vs. ham distribution using count plots.
Explored message length, word count, and punctuation usage differences.

4.Feature Extraction
Used TF-IDF Vectorizer to transform SMS text into numerical features.

5.Machine Learning Models
Implemented and compared:
Naive Bayes (MultinomialNB)
Logistic Regression
Support Vector Machine (LinearSVC)

Evaluated models with:
Confusion Matrix
Classification Report (Accuracy, Precision, Recall, F1-score)
ROC Curve & AUC Score

6.Performance Insights
Naive Bayes provided a strong baseline.
SVM and Logistic Regression achieved higher accuracy and robustness.

📊 Results : 
Models achieved high accuracy (>95%), making them effective for spam filtering.
TF-IDF + SVM gave the best performance on this dataset.

🚀 Applications : 
Can be integrated into SMS apps or email systems to automatically detect spam.
Provides a foundation for building real-time spam detection services
