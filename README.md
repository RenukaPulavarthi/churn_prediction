# 🧠 Customer Churn Prediction using ANN

A machine learning project to predict customer churn using an Artificial Neural Network (ANN) with a Streamlit web interface.

---

## 🔗 Live Demo

👉 [Click here to use the deployed app](https://your-username-churn.streamlit.app)

---

## 📁 Project Structure
churn_prediction/
├── Churn_Modelling.csv # Dataset
├── Label_encoder_gender.pkl # LabelEncoder for Gender
├── one_ot_encoder_Geography.pkl # OneHotEncoder for Geography
├── scalar.pkl # StandardScaler for features
├── model.h5 # Trained ANN model
├── app.py # Streamlit frontend
├── code.ipynb # Model training notebook
├── prediction.ipynb # Model inference notebook
├── requirements.txt # Dependencies
└── README.md # Project info

## Features
-> Takes input through a Streamlit form:
-> Credit Score, Geography, Gender, Age, Tenure, Balance, Num of Products, Credit Card, Active Member, Estimated Salary
->Uses a trained ANN to predict if a customer will churn.
->Uses saved encoders and scaler for preprocessing.
->Shows prediction result instantly.

