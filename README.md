# 📘 Athlete Injury Recovery Time Prediction – Machine Learning & Flask Application

## 📌 Project Overview
This project aims to build a Machine Learning–powered web application to predict the recovery time of athletes after an injury based on structured medical and training data.
The project currently includes:

- A Flask-based web application
- OTP-based authentication system (via SMS API)
- A structured dataset (injury1.csv) containing athlete injury records
- Backend routing and session management
- Project scaffolding prepared for ML model integration

🔧 The machine learning model is not yet integrated — this README outlines both the current system and upcoming ML workflow.

----
## 📂 Repository Structure
```
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
└── flask_session/
|               # Session storage for Flask
└── LICENSE
```

---
## 🚀 Current Functionality

### ✔ 1. OTP-Based Login System
The application includes:

- User phone number input
- OTP generation
- Session validation
- SMS API integration
- Login/logout routes

This ensures secure access to the future ML prediction tool.

---
## ⏳ Functionality (Machine Learning Module)
- You already have injury1.csv, which includes athlete injury–related fields.
- The next steps of the project will include:

### ✔ Building ML Pipeline
- Data cleaning
- Feature engineering
- Model training (Regression models like Random Forest, XGBoost, etc.)
- Evaluating MAE, RMSE, R²

### ✔ Saving trained ML model
- model.pkl or model.joblib

### ✔ Building Predict UI + Backend
- A Flask endpoint /predict
- A form (HTML) where users enter injury details
- Display predicted recovery time

---
## 📊 Dataset Description (injury1.csv)

The dataset contains fields such as:

- Type of injury
- Severity
- Body region
- Athlete demographics
- Recovery duration
- Training load indicators

(Actual field names will be listed after data preprocessing step.)

---
## 📦 Installation & Setup
1️⃣ Clone the Repository
```
git clone https://github.com/Ashwani4545/Athelete_Model_Injury_Recovery_time_Prediction_ML.git
cd Athelete_Model_Injury_Recovery_time_Prediction_ML
```

2️⃣ Install Required Libraries
```
pip install -r requirements.txt
```

3️⃣ Run the Flask Application
```
python application.py
```

4️⃣ Access the App
```
Open your browser at:
http://127.0.0.1:5000/
```

---
## ⚙️ Tech Stack

- Python
- Flask
- Flask-Session
- Requests API
- Pandas / NumPy (for upcoming ML model)
- Scikit-learn (for prediction model)

---
## 🔐 Security Notice
- Hardcoded API keys
- Hardcoded OTP credentials

✔ These will be moved into .env environment variables during correction.
✔ Sensitive keys will be removed from the public repo.

---
## 🧩 Features (Current vs Future)
| Feature               | Status                |
| --------------------- | --------------------- |
| OTP Login System      | ✅ Completed           |
| Frontend UI           | 🟡 Basic (index only) |
| Dataset Included      | ✅ Yes                 |
| ML Model Training     | ❌ Not yet implemented |
| Prediction Endpoint   | ❌ Missing             |
| Result Page           | ❌ Missing             |
| Environment Variables | ❌ Keys are hardcoded  |
| Deployment Ready      | ❌ Not yet             |

---
## 🎯 Project Goals

- Provide accurate estimation of recovery time for injured athletes

- Assist coaches, trainers, and medical staff in planning rehabilitation

- Build a scalable ML + Web solution

- Add visual analytics dashboards

---
## LICENSE
This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---
## 👨‍💻 Author
Ashwani Pandey

Machine Learning & Software Developer
