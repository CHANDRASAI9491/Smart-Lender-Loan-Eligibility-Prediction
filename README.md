# 🏦 Smart Lender – Loan Eligibility Prediction Using Machine Learning

## 📌 Project Overview

Smart Lender is a Machine Learning-based web application that predicts whether a loan applicant is eligible for loan approval based on personal and financial information.

The application uses a trained **XGBoost Machine Learning model** integrated with a Flask web application to provide real-time loan eligibility predictions. It helps reduce manual evaluation time and supports faster decision-making for financial institutions.

The application is successfully deployed on **Render Cloud Platform** for online access.

---

## 🌐 Live Demo

**Render Deployment**

https://smart-lender-loan-eligibility-prediction-8448.onrender.com

---

## 🎯 Objectives

- Predict loan eligibility using Machine Learning.
- Reduce manual loan approval effort.
- Provide accurate real-time predictions.
- Develop a user-friendly Flask web application.
- Deploy the application on Render Cloud.

---

## ✨ Features

- Loan Eligibility Prediction
- User-Friendly Web Interface
- Applicant Information Form
- Data Preprocessing
- Feature Engineering
- Machine Learning Model Integration
- XGBoost Prediction Model
- Real-Time Prediction
- Responsive Design
- Flask Backend
- Render Cloud Deployment
- GitHub Version Control

---

## 🛠 Technologies Used

| Category | Technology |
|----------|------------|
| Programming Language | Python |
| Framework | Flask |
| Machine Learning | Scikit-learn, XGBoost |
| Data Processing | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Frontend | HTML5, CSS3, JavaScript |
| Model Storage | Joblib |
| IDE | Visual Studio Code |
| Version Control | Git & GitHub |
| Deployment | Render |

---

## 📂 Project Structure

```text
Smart-Lender-Loan-Eligibility-Prediction/
│
├── 1. Brainstorming & Ideation/
├── 2. Requirement Analysis/
├── 3. Project Design Phase/
├── 4. Project Planning Phase/
├── 5. Project Development Phase/
├── 6.Project Testing/
├── 7.Project Documentation/
├── 8.Project Demonstration/
│
├── dataset/
│   └── loan_prediction.csv
│
├── flask/
│   ├── app.py
│   ├── model.pkl
│   ├── scaler.pkl
│   ├── templates/
│   └── static/
│
├── TRAINING/
│   ├── Smart_Lender.ipynb
│   ├── model.pkl
│   └── scaler.pkl
│
├── screenshots/
├── IBM/
├── README.md
├── requirements.txt
├── LICENSE
└── .gitignore
```

---

## 🏗 Solution Architecture

```text
User
   │
   ▼
Web Interface
   │
   ▼
Flask Backend
   │
   ▼
Data Preprocessing
   │
   ▼
XGBoost Model
   │
   ▼
Prediction Result
```

---

## 🔄 Project Workflow

```text
Loan Dataset
      │
      ▼
Data Preprocessing
      │
      ▼
Feature Engineering
      │
      ▼
Model Training
      │
      ▼
Model Evaluation
      │
      ▼
Save model.pkl & scaler.pkl
      │
      ▼
Flask Application
      │
      ▼
Deploy on Render
      │
      ▼
Loan Eligibility Prediction
      │
      ▼
Prediction Result
```

---

## 🤖 Machine Learning Models

The following classification algorithms were evaluated:

- Decision Tree Classifier
- Random Forest Classifier
- K-Nearest Neighbors (KNN)
- XGBoost Classifier

**Final Selected Model:** XGBoost Classifier

---

## 📊 Dataset Features

The model predicts loan eligibility using:

- Gender
- Married
- Dependents
- Education
- Self Employed
- Applicant Income
- Coapplicant Income
- Loan Amount
- Loan Amount Term
- Credit History
- Property Area

**Target Variable**

- Loan Status

---

## 📈 Exploratory Data Analysis

EDA includes analysis of:

- Loan Status Distribution
- Applicant Income Distribution
- Credit History Distribution
- Loan Amount Distribution
- Feature Relationships

---

## 💻 Installation

### Clone the Repository

```bash
git clone https://github.com/CHANDRASAI9491/Smart-Lender-Loan-Eligibility-Prediction.git
```

### Move to Project Folder

```bash
cd Smart-Lender-Loan-Eligibility-Prediction
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run the Application

If running locally:

```bash
cd flask
python app.py
```

### Open in Browser

```text
http://127.0.0.1:5000
```

---

## ☁️ Render Deployment

| Setting | Value |
|---------|-------|
| Root Directory | flask |
| Build Command | `pip install -r ../requirements.txt` |
| Start Command | `gunicorn app:app` |

---

## 📸 Application Screenshots

Available screenshots include:

- Home Page
- Prediction Page
- Approved Result
- Rejected Result
- About Page

---

## 📁 Repository Contents

- Brainstorming & Ideation
- Requirement Analysis
- Project Design Phase
- Project Planning Phase
- Project Development Phase
- Project Testing
- Project Documentation
- Project Demonstration
- Training Notebook
- Dataset
- Flask Application
- Machine Learning Model
- Project Screenshots
- Documentation

---

## 🚀 Future Enhancements

- Database Integration
- User Authentication
- REST API
- Explainable AI (XAI)
- Prediction History
- Dashboard & Analytics
- Model Retraining with Updated Data

---

## 👨‍💻 Author

**Pothuri Chandra Sai**

B.Tech – Computer Science & Engineering (AI & ML)

Anantha Lakshmi Institute of Technology and Sciences

**GitHub**

https://github.com/CHANDRASAI9491

**LinkedIn**

https://www.linkedin.com/in/chandra-sai-pothuri-a7a4852b6/

---

## ⭐ Acknowledgements

This project was developed as part of the AI & Machine Learning curriculum to demonstrate the practical implementation of Machine Learning, XGBoost, Flask, and Render Cloud deployment for solving real-world loan eligibility prediction problems.
