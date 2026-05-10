# Bank-Credit-Classification-System
This project focuses on building an end-to-end machine learning system for predicting customer credit classifications using historical banking data. The system combines data preprocessing, feature engineering, machine learning model development, API deployment using FastAPI, and interactive visualization through Streamlit.

The project was designed to simulate a real-world ML workflow, including model training, evaluation, deployment, logging, and containerization using Docker.

Dataset

Source: Bank credit classification dataset containing customer financial and credit-related information.

Features include:

Income
Loan Amount
Credit Score
Employment Information
Financial History
Other customer-related attributes
Data Preprocessing
Handled missing values and inconsistent data.
Encoded categorical variables.
Applied feature scaling techniques.
Performed feature engineering.
Detected and handled outliers.
Addressed class imbalance using SMOTE.
Analyzed and reduced multicollinearity.
Performed exploratory data analysis (EDA).
Models Used
Traditional Machine Learning Models
Decision Tree Classifier
Random Forest Classifier
Logistic Regression
Ensemble Learning Models
LightGBM
XGBoost
Model Evaluation
Applied Cross-Validation techniques.
Used Hyperparameter Tuning with GridSearchCV and Random Search.
Evaluated models using:
Accuracy
Precision
Recall
F1-Score
Confusion Matrix
FastAPI Backend

Developed RESTful APIs using FastAPI to:

Accept customer input features
Generate credit classification predictions
Return prediction probabilities
Serve trained machine learning models
Streamlit Dashboard

Built an interactive Streamlit application to:

Display EDA visualizations
Demonstrate preprocessing steps
Compare model performance
Allow real-time predictions through user input
Docker & Deployment
Containerized the application using Docker
Configured multi-service setup using docker-compose
Organized the project using modular architecture
Added logging and configuration management
Technologies Used
Python
Scikit-learn
Pandas
NumPy
FastAPI
Streamlit
Docker
Machine Learning
SMOTE
LightGBM
XGBoost
Project Structure
api/               -> FastAPI backend
config/            -> Configuration files
model/             -> Saved trained models
src/               -> ML pipeline and preprocessing
streamlit_app/     -> Streamlit frontend
