# 📘 Athlete Injury Recovery Time Prediction – Machine Learning & Flask Application

📌 Project Overview
This project aims to build a Machine Learning–powered web application to predict the recovery time of athletes after an injury based on structured medical and training data.
The project currently includes:

A Flask-based web application

OTP-based authentication system (via SMS API)

A structured dataset (injury1.csv) containing athlete injury records

Backend routing and session management

Project scaffolding prepared for ML model integration

🔧 The machine learning model is not yet integrated — this README outlines both the current system and upcoming ML workflow.

----
📂 Repository Structure
Athelete_Model_Injury_Recovery_time_Prediction_ML/
│
├── application.py               # Flask app (OTP login, routing)
├── injury1.csv                  # Dataset for future ML model
├── README.md                    # Project documentation
├── requirements.txt             # Dependencies
│
├── templates/                   # HTML templates for Flask
│   ├── index.html               # Login / OTP page
│   └── (other UI files)
│
├── static/                      # CSS, JS, image assets
│
└── flask_session/               # Session storage for Flask

---
🚀 Current Functionality
✔ 1. OTP-Based Login System
The application includes:

User phone number input

OTP generation

Session validation

SMS API integration

Login/logout routes

This ensures secure access to the future ML prediction tool.

---
⏳ Upcoming Functionality (Machine Learning Module)

You already have injury1.csv, which includes athlete injury–related fields.

The next steps of the project will include:

✔ Building ML Pipeline
Data cleaning

Feature engineering

Model training (Regression models like Random Forest, XGBoost, etc.)

Evaluating MAE, RMSE, R²

✔ Saving trained ML model

model.pkl or model.joblib

✔ Building Predict UI + Backend

A Flask endpoint /predict

A form (HTML) where users enter injury details

Display predicted recovery time

---
