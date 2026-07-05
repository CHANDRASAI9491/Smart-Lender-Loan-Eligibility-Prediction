# 🏦 Smart Lender – Loan Eligibility Prediction Using Machine Learning

## 📌 Project Overview

Smart Lender is a Machine Learning-based web application that predicts whether a loan applicant is eligible for loan approval based on personal and financial information.

The application uses a trained Machine Learning model integrated with a Flask web application to provide real-time loan eligibility predictions. It helps reduce manual evaluation time and supports faster decision-making for financial institutions.

---

## 🎯 Objectives

- Predict loan eligibility using Machine Learning.
- Reduce manual loan approval effort.
- Provide accurate real-time predictions.
- Develop a user-friendly web application.
- Demonstrate Machine Learning deployment using Flask.

---

## ✨ Features

- Loan Eligibility Prediction
- User-Friendly Web Interface
- Applicant Information Form
- Data Preprocessing
- Machine Learning Model Integration
- Real-Time Prediction
- Responsive Design
- Flask Backend
- GitHub Version Control

---

## 🛠 Technologies Used

| Category | Technology |
|----------|------------|
| Programming Language | Python |
| Framework | Flask |
| Machine Learning | Scikit-learn |
| Data Processing | Pandas, NumPy |
| Frontend | HTML5, CSS3, JavaScript |
| IDE | Visual Studio Code |
| Version Control | Git & GitHub |

---

## 📂 Project Structure

```text
Smart-Lender-Loan-Eligibility-Prediction/
│
├── TRAINING/
├── dataset/
├── flask/
├── screenshots/
├── README.md
├── requirements.txt
└── .gitignore
```

---

## 🏗 Solution Architecture

```
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
Machine Learning Model
   │
   ▼
Prediction Result
```

---

## 🔄 Project Workflow

```
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

The best-performing model was selected and integrated into the Flask application.

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

Target Variable:

- Loan Status

---

## 📈 Exploratory Data Analysis

EDA includes analysis of:

- Loan Status Distribution
- Applicant Income Distribution
- Credit History Distribution
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

```bash
python app.py
```

### Open in Browser

```
http://127.0.0.1:5000
```

---

## 📸 Application Screenshots

Place your screenshots inside the `screenshots` folder.

Suggested screenshots:

- Home Page
- Prediction Page
- Approved Result
- Rejected Result
- About Page

---

## 📁 Repository Contents

- Training Code
- Flask Application
- Dataset
- Screenshots
- Machine Learning Model
- Project Documentation

---

## 🚀 Future Enhancements

- Cloud Deployment
- Database Integration
- User Authentication
- REST API
- Explainable AI
- Improved Machine Learning Models
- Prediction History

---

## 👨‍💻 Author

**Pothuri Chandra Sai**

B.Tech – Computer Science & Engineering (AI & ML)

Anantha Lakshmi Institute of Technology and Sciences

GitHub:
https://github.com/CHANDRASAI9491

LinkedIn:
https://www.linkedin.com/in/chandra-sai-pothuri-a7a4852b6/

---

## ⭐ Acknowledgements

This project was developed as part of the AI & Machine Learning curriculum to demonstrate the practical application of Machine Learning and Flask in solving real-world loan eligibility prediction problems.
