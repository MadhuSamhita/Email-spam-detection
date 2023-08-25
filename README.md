## Email Spam Classification using NLP
This project involves classifying emails as spam or ham (legitimate) using Natural Language Processing (NLP) techniques. The process can be summarized as follows:

### Data Loading and Preprocessing:
*Loaded an email dataset containing text and spam/ham labels.
(dataset link): https://www.kaggle.com/datasets/williambruno/email-classifier-dataset
*Preprocessed the text data by tokenizing, converting to lowercase, and removing stopwords and punctuation.

### Feature Extraction:
*Utilized the CountVectorizer from scikit-learn to convert preprocessed text into numerical features.
*Transformed both training and testing data using the fitted vectorizer.

### Model Training and Evaluation:
*Employed the Multinomial Naive Bayes classifier to train the model on the vectorized training data.
*Evaluated the model's accuracy and generated a classification report for performance assessment.

### Non-Zero Word Frequencies:
*Displayed non-zero indices and corresponding word frequencies for a sample using the vectorized representation.
*Gained insights into the distribution of word frequencies in the vectorized data.

This project provides a practical introduction to NLP techniques, showcasing the process of text preprocessing, feature extraction, and model training for email spam classification. The project serves as a starting point for delving into NLP applications and data analysis.
