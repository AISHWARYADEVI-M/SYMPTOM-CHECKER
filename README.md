# 🤖 AI Symptom Checker

## 📌 Project Overview
A web-based AI-powered healthcare assistant that predicts possible diseases based on user-selected symptoms.  
Built using machine learning and deployed with Streamlit, the system provides probabilistic disease predictions along with downloadable reports and nearby doctor suggestions.

---

## 🎯 Features

- 🧠 Predicts top 3 possible diseases using ML model  
- 📊 Displays probability/confidence for each disease  
- 📄 Generates downloadable PDF health report  
- 🗺️ Finds nearby doctors using location coordinates  
- ⚠️ Includes medical disclaimer for safe usage  
- 💡 Shows random health tips for user engagement  

---

## 🛠 Technologies Used

- **Python**
- **Streamlit** – Web interface  
- **Scikit-learn / Joblib** – ML model loading  
- **Pandas & NumPy** – Data handling  
- **FPDF** – PDF report generation  
- **Requests API** – Location & doctor search  
- **OpenStreetMap (Nominatim API)** – Nearby doctor data  

---

## 📂 Dataset

- Cleaned symptom dataset (`cleaned_dataset.csv`)  
- Contains:
  - Various symptoms  
  - Disease labels  
- Used for training the classification model  

---

## ⚙️ How It Works

1. User selects symptoms from the interface  
2. Symptoms are converted into text format  
3. Text is vectorized using a trained vectorizer  
4. ML model predicts disease probabilities  
5. Top 3 diseases are displayed with confidence scores  

---

## 🩺 Disease Prediction Output

- Shows:
  - Disease name  
  - Confidence percentage  
- Ranked based on prediction probability  

---

## 📄 PDF Report Generation

The system generates a structured report including:

- User details (Name, Age, Gender)  
- Selected symptoms  
- Predicted diseases  
- Confidence scores  

Users can download this report instantly.

---

## 🗺️ Nearby Doctor Finder

- Uses latitude & longitude input  
- Fetches nearby doctors via OpenStreetMap API  
- Displays doctor names and locations  

---

## ⚠️ Disclaimer

This tool is for **informational purposes only** and does not replace professional medical advice.  
Users are advised to consult a certified doctor.

---

## 🚀 Future Enhancements

- Real-time location detection (GPS)  
- Integration with hospital APIs  
- More accurate deep learning models  
- Chatbot-based symptom interaction  
- User health history tracking  

---

## 💼 Project Value

This project demonstrates:

- End-to-end ML application deployment  
- Integration of AI with real-world APIs  
- Healthcare-based predictive analytics  
- Report automation and user-friendly UI  

---

## ❤️ Built With

Streamlit + Machine Learning + Python
