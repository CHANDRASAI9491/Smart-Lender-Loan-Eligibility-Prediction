# 🏦 Smart Lender – Loan Eligibility Prediction Using Machine Learning

<p align="center">

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)
![Flask](https://img.shields.io/badge/Flask-Web%20Framework-black?logo=flask)
![XGBoost](https://img.shields.io/badge/XGBoost-ML-green)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-orange?logo=scikitlearn)
![Render](https://img.shields.io/badge/Deployed%20on-Render-46E3B7?logo=render)
![License](https://img.shields.io/badge/License-MIT-blue)

</p>

---

# 📌 Project Overview

Smart Lender is a **Machine Learning-powered Loan Eligibility Prediction System** developed using **Python**, **Flask**, and **XGBoost**.

The application predicts whether a loan applicant is eligible for loan approval based on personal and financial information. It enables banks and financial institutions to make faster, more consistent, and data-driven lending decisions.

The trained Machine Learning model is integrated into a Flask web application and deployed on the **Render Cloud Platform** for real-time prediction.

---

# 🌐 Live Demo

### 🚀 Render Deployment

https://smart-lender-loan-eligibility-prediction-8448.onrender.com

---

# 🎥 Project Demo Video

### 📺 Watch the complete demonstration

https://drive.google.com/file/d/1vQt5JWlmK6AjpRLzCWL68qxj6XZfPPzT/view?usp=drive_link

---

# 🎯 Objectives

- Predict loan eligibility using Machine Learning.
- Reduce manual loan approval effort.
- Improve decision consistency.
- Provide instant prediction results.
- Deploy a real-world Flask application.
- Demonstrate end-to-end Machine Learning deployment.

---

# ✨ Features

- Loan Eligibility Prediction
- XGBoost Classification Model
- User-Friendly Web Interface
- Real-Time Prediction
- Applicant Information Form
- Data Preprocessing
- Feature Engineering
- Flask Backend
- Responsive Frontend
- Render Cloud Deployment
- Git Version Control

---

# 🛠 Technologies Used

| Category | Technology |
|------------|-----------------------------|
| Programming Language | Python |
| Backend Framework | Flask |
| Machine Learning | Scikit-learn, XGBoost |
| Data Processing | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Frontend | HTML5, CSS3, JavaScript |
| Model Storage | Joblib |
| IDE | Visual Studio Code |
| Version Control | Git & GitHub |
| Deployment | Render |

---

# 📂 Project Structure

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

# 🏗 Solution Architecture

```text
                User
                  │
                  ▼
          Flask Web Interface
                  │
                  ▼
          Input Validation
                  │
                  ▼
        Data Preprocessing
                  │
                  ▼
       XGBoost Prediction Model
                  │
                  ▼
          Loan Eligibility
                  │
                  ▼
      Approved / Rejected
```

---

# 🔄 Project Workflow

```text
Loan Dataset
      │
      ▼
Data Collection
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
Flask Web Application
      │
      ▼
Deploy on Render
      │
      ▼
Real-Time Prediction
```

---

# 🤖 Machine Learning Models Evaluated

- Decision Tree Classifier
- Random Forest Classifier
- K-Nearest Neighbors (KNN)
- XGBoost Classifier

### ✅ Final Selected Model

**XGBoost Classifier**

---

# 📊 Model Performance

| Model | Accuracy |
|------------|-----------|
| Decision Tree | Evaluated |
| Random Forest | Evaluated |
| KNN | Evaluated |
| **XGBoost** | **Best Performing Model** |

---

# 📊 Dataset Features

### Input Features

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

### Target Variable

- Loan Status

---

# 📈 Exploratory Data Analysis

EDA includes

- Loan Status Distribution
- Applicant Income Distribution
- Credit History Distribution
- Loan Amount Distribution
- Feature Correlation
- Class Distribution

---

# 💼 Project Scenarios

### Scenario 1 – Individual Applicant

Applicants can enter their details and instantly check their loan eligibility.

### Scenario 2 – Bank Loan Officer

Loan officers can quickly evaluate multiple loan applications with consistent predictions.

### Scenario 3 – Financial Institution

Banks can use the application as an initial screening system before manual verification.

---

# 💻 Installation

### Clone Repository

```bash
git clone https://github.com/CHANDRASAI9491/Smart-Lender-Loan-Eligibility-Prediction.git
```

### Navigate to Project

```bash
cd Smart-Lender-Loan-Eligibility-Prediction
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Locally

```bash
cd flask
python app.py
```

### Open Browser

```
http://127.0.0.1:5000
```

---

# ☁️ Render Deployment

| Setting | Value |
|----------|----------------------------|
| Root Directory | flask |
| Build Command | pip install -r ../requirements.txt |
| Start Command | gunicorn app:app |

---

# 📸 Application Screenshots

- Home Page
- Prediction Page
- Loan Approved Result
- Loan Rejected Result
- About Page

---

# 📁 Repository Contents

- Brainstorming & Ideation
- Requirement Analysis
- Project Design Phase
- Project Planning Phase
- Project Development Phase
- Project Testing
- Project Documentation
- Project Demonstration
- Dataset
- Training Notebook
- Flask Application
- Machine Learning Model
- Screenshots
- Documentation

---

# 🚀 Future Enhancements

- User Authentication
- Database Integration
- REST API
- Explainable AI (XAI)
- Prediction History
- Dashboard & Analytics
- Model Retraining
- Multi-Bank Support

---

# 👨‍💻 Author

**Pothuri Chandra Sai**

B.Tech – Computer Science & Engineering (AI & ML)

Anantha Lakshmi Institute of Technology and Sciences

### GitHub

https://github.com/CHANDRASAI9491

### LinkedIn

https://www.linkedin.com/in/chandra-sai-pothuri-a7a4852b6/

---

# 🙏 Acknowledgements

This project was developed as part of the Artificial Intelligence & Machine Learning curriculum to demonstrate the practical implementation of Machine Learning, Flask, XGBoost, and cloud deployment using Render for solving real-world loan eligibility prediction problems.

---

## ⭐ If you found this project useful, consider giving it a Star on GitHub!
