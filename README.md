# Hate-speech-prediction
## Overview
This project aims to analyze and mitigate hate speech in online platforms using a comprehensive approach. The goal is to enhance our understanding of hate speech dynamics, identify patterns and trends, profile users prone to engaging in hate speech, analyze geographic distributions, evaluate model performance, and ultimately develop effective strategies to detect and mitigate hate speech online.


1. **Data Understanding**
    -  Features:
        - File_id: Unique identifier for each file containing textual context.
        - User_id: Identifier for the user posting the context.
        - Subforum_id: Identifier for the subforum where the context was posted.
        - Num_contexts: Number of contexts associated with each file.
        - Label: Label indicating whether the context contains hate speech or not.

2. **Approach**
    - Analyzing textual context using natural language processing (NLP) techniques.(Tokens, stopwords,stemmer)
    - Utilizing word embeddings and tfidfVectorizer to identify key themes within hate speech.
    - Investigating temporal patterns, profiling users, and evaluating model performance.
            
3 Model Accuracy:
Random forest under sampler
              precision    recall  f1-score   support

        hate       0.34      0.69      0.46       234
      noHate       0.96      0.83      0.89      1880

    accuracy                           0.82      2114
   macro avg       0.65      0.76      0.67      2114
weighted avg       0.89      0.82      0.84      2114

Model Accuracy: 81.79%
Confusion Matrix:
[[ 161   73]
 [ 312 1568]]
