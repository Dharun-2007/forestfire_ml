# 🔥 Forest Fire Prediction Web Application

## 📌 Project Overview
This project predicts the possibility of forest fires based on environmental parameters using a Machine Learning model.  
The trained ML model is integrated into a Flask-based web application that allows users to input values and get real-time predictions.

This project demonstrates the **complete ML lifecycle**:
data preprocessing → model training → model saving → model loading → web deployment.

---

## 🧠 Machine Learning Details
- **Algorithm Used:** Ridge Regression
- **Preprocessing:** Standard Scaler
- **Model Storage:** Pickle (`.pkl`)
- **ML Library:** Scikit-learn

---

## 🛠 Tech Stack
- Python
- Flask
- NumPy
- Pandas
- Scikit-learn
- HTML / CSS

---

forest_fire_deploy/ │── application.py │── requirements.txt │ ├── models/ │   ├── ridge.pkl │   └── scaler.pkl │ ├── templates/ │   ├── index.html │   └── home.html
Copy code

---

## 🚀 How to Run the Project Locally

### 1️⃣ Clone the repository

git clone <your-github-repo-url>
cd forest_fire_deploy

### 2. Create and activate environment


conda create -n forest_fire_env python=3.11
conda activate forest_fire_env
3️⃣ Install dependencies

pip install -r requirements.txt
4️⃣ Run the application

 ```bash python application.py ```bash
5️⃣ Open in browser


http://127.0.0.1:5000
📊 Application Features
User-friendly web interface
Real-time prediction
Clean ML pipeline
Deployment-ready structure
🌍 Deployment Ready
This project can be deployed on:
AWS EC2
Render
Railway
Relative paths are used for model loading, making it platform-independent.
📌 Learning Outcomes
End-to-end ML project implementation
Flask web deployment
Model persistence using pickle
Environment and dependency management
👤 Author
Dharun
AIML Student