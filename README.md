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

## 📂 Project Structure
forest_fire_deploy/ │── application.py │── requirements.txt │ ├── models/ │   ├── ridge.pkl │   └── scaler.pkl │ ├── templates/ │   ├── index.html │   └── home.html

---

## 🚀 How to Run the Project Locally

### 1️⃣ Clone the repository
```bash
git clone <your-github-repo-url>
    cd forest_fire_deploy

    conda create -n forest_fire_env python=3.12.12
    conda activate forest_fire_env
    pip install -r requirements.txt
    python application.py
    http://127.0.0.1:5000"# forestfire_ml" 
