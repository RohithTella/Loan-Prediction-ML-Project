# Loan-Prediction-ML-Project
# 📊 Prediction of Modernized Loan Approval System Based On Machine Learning Approach

This project is a machine learning-based solution developed to predict whether a loan application will be approved or not. It uses multiple machine learning algorithms to evaluate historical customer data such as income, employment status, loan amount, credit history, and property area. Based on this, the system predicts the loan status (Approved or Not Approved). The project is useful for both banks and customers to make the loan process smarter, faster, and more reliable without human bias.

## 🧠 Algorithms Used
- Decision Tree Classifier ✅ (Best Accuracy)
- Random Forest Classifier
- Logistic Regression
- Support Vector Machine (SVM)

## 📂 Project Folder Structure

Loan-Prediction-ML-Project/
├── ML_Model.ipynb # Model training and testing notebook
├── app.py # Main web app file (Flask or Streamlit)
├── dataset.csv # Loan approval dataset used for model
├── templates/ # HTML templates (if Flask is used)
├── static/ # CSS or images (if required)
├── requirements.txt # Python libraries used in the project
└── README.md # Project overview and folder explanation


## 🔍 Project Features
- Takes loan-related inputs from the user (like Gender, Income, Loan Amount, etc.)
- Predicts loan approval status instantly
- Compares accuracy of 4 different ML algorithms
- Displays confusion matrix and bar chart for accuracy visualization
- Allows admin to upload new datasets and retrain models
- Includes download option for predicted result dataset
- User-friendly interface for both Remote Users and Service Provider
- Removes manual decision-making and bias in loan approval process

## 📌 Conclusion
This system automates the traditional loan approval process by implementing intelligent machine learning techniques. It enables faster decision-making, reduces workload for banks, and gives transparency and fairness to applicants. Among all tested models, the Decision Tree algorithm showed the highest accuracy and was chosen as the final predictive model.
