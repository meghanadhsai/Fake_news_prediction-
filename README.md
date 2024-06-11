# Fake_news_prediction-
A fake news prediction model using logistic regression classifies news articles as fake or real. This involves several steps to ensure accurate predictions.

Importing libraries.

1) Data Collection:Gather articles from credible and fake news sources.
Label each article as "fake" or "real."

2) Data Preprocessing:Handling missing data

    Text Cleaning: Remove punctuation, stop words, and apply stemming.

    Feature Extraction:
    TF-IDF (Term Frequency-Inverse Document Frequency): Convert text into numerical vectors.

3) Model training:Logistic Regression model: Chosen for its simplicity, interpretability, and effectiveness.
  Regularization: Techniques like L2 prevent overfitting.
6)Evaluation:Train-Test Split: Divide the dataset for evaluation in 80 : 20

7) Prediction:The model predicts the probability of an article being fake or real.
8) accuracy of the model is 98% 

Deployment:Deploy as a web services for real-time predictions, flagging articles for review.


