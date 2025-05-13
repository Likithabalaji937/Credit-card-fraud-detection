# 💳 Credit Card Fraud Detection System

This project is a **Credit Card Fraud Detection System** built using **XGBoost** for fraud prediction, **Flask** as the backend framework, and an **HTML-based frontend** for user interaction. It uses geolocation filters (latitude and longitude) and transaction data to detect potential fraud.

---

## 🚀 Features

- Detects fraudulent credit card transactions using ML
- Uses **XGBoost** model trained on imbalanced dataset
- Input form for transaction details through web UI
- Geo-fencing based on **latitude (8.0–13.5)** and **longitude (76.0–80.3)** bounds
- Hosted using **Flask**
- Easily extendable to include more parameters or APIs

---

## 🧠 Machine Learning Model

- **Model:** XGBoost Classifier
- **Dataset:** Credit card transaction dataset (imbalanced)
- **Training platform:** Google Colab
- **Preprocessing:** Feature scaling, handling imbalanced data using SMOTE (optional), train-test split
- **Metrics used:** Accuracy, Precision, Recall, F1-Score, AUC-ROC

---

## 🧾 Input Parameters

- Transaction Amount
- Transaction Time
- Latitude
- Longitude
- Other relevant anonymized features (V1, V2, ..., V28)

---

## 🌐 Web Interface

- Built using **HTML5, CSS3**
- Connected to Flask backend via POST request
- Displays prediction result: Fraud or Not Fraud
- User uploads input or enters data via form

---

## 📁 Project Structure

