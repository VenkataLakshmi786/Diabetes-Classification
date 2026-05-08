# Diabetes-Classification
# 🩺 Diabetes Prediction App

A Machine Learning web application built with **Streamlit** that predicts whether a patient is likely to have diabetes based on medical input parameters.

---

## 🚀 Project Overview

This project uses a trained **Machine Learning Classification Model** to analyze patient health details and predict diabetes risk.

Users can enter medical values such as glucose level, BMI, age, insulin, etc., and get an instant prediction.

---

## 🛠️ Technologies Used

- Python 🐍
- NumPy
- Scikit-learn
- Streamlit
- Pickle

---

## 📂 Project Structure

```bash
├── app.py                 # Streamlit App
├── diabetes_model.pkl     # Trained ML Model
├── README.md              # Project Documentation
└── requirements.txt       # Required Libraries

📊 Features
✅ Predict Diabetes Risk
✅ User-Friendly Streamlit Interface
✅ Instant Prediction Results
✅ Probability Score Display
✅ Real-Time Input Form

🧠 Input Features Used

The model predicts using these medical features:

Pregnancies
Glucose
Blood Pressure
Skin Thickness
Insulin
BMI
Diabetes Pedigree Function
Age
🎯 Output

The application predicts:

Likely Diabetic
Not Diabetic

With a probability/risk score.

▶️ How to Run Locally
1️⃣ Clone Repository
git clone https://github.com/your-username/diabetes-prediction-app.git
cd diabetes-prediction-app
2️⃣ Install Requirements
pip install -r requirements.txt
3️⃣ Run Streamlit App
streamlit run app.py
📦 requirements.txt
streamlit
numpy
scikit-learn
💻 App Preview

Add screenshot after deployment.

🌐 Deployment Options

You can deploy this app on:

Streamlit Cloud
Render
Railway
Hugging Face Spaces
📚 Learning Outcomes

Through this project, I learned:

Classification Algorithms
Model Deployment
Streamlit UI Development
Pickle Model Saving
End-to-End ML Workflow
