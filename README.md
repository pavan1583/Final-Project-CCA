# Developing Web-Based Machine Learning Models for Customer Churn Prediction

Customer churn is one of the biggest challenges in the telecom industry. This project aims to predict whether a customer is likely to leave the service using machine learning techniques, and deploy the model in a web-based application using Flask.
---

## 📌 Introduction

This project combines the power of machine learning and web development to create an end-to-end solution for predicting customer churn. It allows business users to input customer data through a browser and instantly receive a churn prediction.

The model has been trained using customer demographics, services opted for, account information, and billing behavior from a telecom dataset. The entire system is lightweight, efficient, and user-friendly.

---

## ✅ Uses

- **Telecom Companies**: To proactively identify at-risk customers and take retention actions.
- **Customer Success Teams**: To prioritize outreach based on churn probability.
- **Business Analysts**: For understanding key drivers of churn.
- **Academia**: As a reference for deploying machine learning models on the web.

---

## 🚀 Features

- User-friendly web interface for inputting customer data.
- Real-time churn prediction using a pre-trained machine learning model.
- Visualized data exploration and preprocessing (via Jupyter Notebooks).
- Clean and modular folder structure.
- Easy to deploy locally or on cloud platforms like Heroku or Render.

---

## 📁 Project Structure

- `app.py`: Main Flask application file to run the web server.
- `templates/home.html`: Frontend HTML page used for input and displaying predictions.
- `model.sav`: Serialized machine learning model using `joblib`.
- `tel_churn.csv`, `first_telc.csv`, `WA_Fn-UseC_-Telco-Customer-Churn.csv`: Datasets used for training and testing the model.
- `Churn Analysis - EDA.ipynb`: Exploratory Data Analysis (EDA) notebook.
- `Churn Analysis - Model Building.ipynb`: Model building and evaluation notebook.
- `EDA_PP.pdf`: Report/summary of the EDA.
- `__pycache__/`: Stores compiled Python files.

---

## 🛠️ Tech Stack

- **Backend**: Python (Flask)
- **Frontend**: HTML (Jinja templating)
- **Machine Learning**: Scikit-learn
- **Data Handling**: Pandas, NumPy
- **Visualization**: Matplotlib, Seaborn
- **Notebook Environment**: Jupyter

---

## 📊 Model Features

The model uses the following features for churn prediction:

- Customer demographics (gender, senior citizen, etc.)
- Service details (internet, phone, streaming)
- Account information (tenure, contract type)
- Billing behavior (payment method, monthly charges)

---

## ▶️ Getting Started

1. **Clone the repo**:
   ```bash
   git clone https://github.com/yourusername/Final-Project-CCA.git
   cd Final-Project-CCA
