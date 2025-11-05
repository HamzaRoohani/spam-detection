This small script trains a TF-IDF + Logistic Regression model on `spam.csv` dataset and runs a few hardcoded checks.

`train_logistic_regression.py` — loads `spam.csv` dataset, balances the dataset, vectorizes the sectences, trains the model, prints evaluation and runs hardcoded message checks.

Outputs: trained model files `tfidf_vectorizer.joblib` and `logreg_model.joblib` and printed evaluation and hardcoded predictions.
