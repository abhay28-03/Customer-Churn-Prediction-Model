# 📉 Customer Churn Prediction (Telco Dataset)

This project focuses on building a Customer Churn Prediction model using the Telco Customer Churn dataset from Kaggle. The goal is to predict whether a customer is likely to discontinue a telecom service based on their demographic details, service usage, and billing information.

# 🔍 Project Overview

Customer churn is a critical business problem in the telecom industry. This project applies machine learning classification techniques to identify customers who are at risk of churning, helping businesses take proactive retention measures.

# 🛠️ Technologies & Libraries Used

Python
NumPy – Numerical computations
Pandas – Data manipulation and analysis
Matplotlib & Seaborn – Data visualization
Scikit-learn – Model building and evaluation
Imbalanced-learn (SMOTE) – Handling class imbalance
XGBoost – Gradient boosting classifier
Pickle – Model serialization

# ⚙️ Workflow

Data Preprocessing
Handling categorical variables using LabelEncoder
Train-test split
Addressing class imbalance using SMOTE
Model Training
Decision Tree Classifier
Random Forest Classifier
XGBoost Classifier
Model Evaluation
Accuracy Score
Confusion Matrix
Classification Report
Cross-validation for performance validation
Model Saving
Trained model saved using pickle for future deployment or inference

# 📊 Results

The models were evaluated and compared to determine the best-performing classifier for churn prediction, with ensemble and boosting techniques showing strong performance.

# 🚀 Future Improvements

Hyperparameter tuning
Feature importance analysis
Deployment using Flask or FastAPI
Integration with a real-time customer analytics system

# 📁 Dataset

Source: Kaggle – Telco Customer Churn Dataset
