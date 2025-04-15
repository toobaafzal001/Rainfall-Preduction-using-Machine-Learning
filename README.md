# Rainfall-Preduction-using-Machine-Learning
Rainfall Prediction App
A Streamlit-based web application for predicting rainfall using machine learning models.

Features
Loads and preprocesses rainfall data from Rainfall.csv
Supports Logistic Regression, XGBoost, and SVC models
Interactive UI for model selection and preprocessing options
Displays model performance metrics and confusion matrix
Enables predictions for existing dates and manual input
Saves and loads best-performing model

Requirements
Python 3.8+
Streamlit
Pandas
NumPy
Scikit-learn
XGBoost
Matplotlib
Joblib
Imbalanced-learn

Installation
Clone the repository
Install dependencies: pip install -r requirements.txt
Place Rainfall.csv in the project directory

Usage
Run the app: streamlit run app.py
Access the web interface in your browser
Select preprocessing options and models in the sidebar
Train models and view results
Make predictions using date lookup or manual input

Data Format
Expected input: Rainfall.csv with columns including 'day', 'rainfall', and weather features
'rainfall' column should contain 'yes'/'no' or 1/0 values

Notes
Ensure Rainfall.csv is present before running
Model performance is evaluated using ROC AUC score
Best model is automatically saved as best_model.pkl
