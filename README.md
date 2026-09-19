# Credit_card_fraud_detection

This project focuses on detecting fraudulent credit card transactions using machine learning. The dataset contains transaction records that are analyzed to identify patterns associated with fraudulent and legitimate transactions.

## Project Objectives

* Analyze and preprocess credit card transaction data.
* Explore the distribution of fraudulent and legitimate transactions.
* Identify important patterns and features related to fraud.
* Train a machine learning model to classify transactions.
* Evaluate the model using multiple performance metrics.

## Machine Learning Model

A **Random Forest Classifier** is used for fraud detection. The model learns patterns from historical transaction data and predicts whether a transaction is fraudulent or legitimate.

## Model Evaluation

The project evaluates the classification model using:

* Accuracy
* Precision
* Recall
* F1-Score
* Matthews Correlation Coefficient (MCC)
* Confusion Matrix

These metrics provide a broader assessment of fraud-detection performance, particularly for an imbalanced classification problem.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Jupyter Notebook

## Project Workflow

1. Load the credit card transaction dataset.
2. Perform data exploration and analysis.
3. Preprocess the transaction data.
4. Separate features and target variable.
5. Train the Random Forest classification model.
6. Generate predictions on test data.
7. Evaluate model performance using classification metrics.
8. Analyze the results using visualizations and a confusion matrix.

## Disclaimer

This project is intended for educational and machine-learning demonstration purposes. It should not be considered a production-ready financial fraud detection system.

