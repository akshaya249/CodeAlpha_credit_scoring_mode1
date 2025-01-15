# Credit Scoring Model

This project aims to develop a credit scoring model to predict the creditworthiness of individuals based on historical financial data. The model uses machine learning classification algorithms (Random Forest) to make predictions.

## Files Included:
- credit_data.csv: The dataset containing financial information.
- Credit_Scoring_Model.ipynb: The Jupyter notebook with the code for data preprocessing, model training, and evaluation.
- credit_scoring_model.pkl: The trained machine learning model.

## Steps Followed:
1. *Data Preprocessing*: Handled missing values and encoded categorical variables.
2. *Model Training*: Trained a Random Forest Classifier to predict creditworthiness.
3. *Model Evaluation*: Evaluated the model using accuracy, classification report, and AUC-ROC score.
4. *Model Deployment*: Saved the trained model for future use.

## How to Use the Model:
1. Load the model using joblib or pickle.
2. Preprocess new input data in the same way as the training data.
3. Use the model's predict() method to make predictions on new data.
