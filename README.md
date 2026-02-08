# Customer Churn Prediction System

A **full-stack Machine Learning project** that predicts customer churn probability using a trained ML model and provides real-time predictions through a web interface.

This project demonstrates **end-to-end ML application development**, including:
- Model training
- Backend API development
- Frontend UI
- Cloud deployment
- Proper documentation

---

## 🔍 Project Overview

Customer churn prediction helps businesses identify customers who are likely to stop using a service.  
This system allows users to input customer details and instantly receive:
- **Churn probability**
- **Risk category** (Low / Moderate / High)

---

## 🧠 Architecture

User → React Frontend → FastAPI Backend → ML Model → Prediction



- **Frontend**: React + Vite (Vercel)
- **Backend**: FastAPI (Render)
- **Model**: Scikit-learn
- **Data Processing**: Pandas, NumPy

---

## 🌐 Live Demo

- **Frontend UI**:  
  👉 https://customer-churn-ui-vm2k.vercel.app/

- **Backend API**:  
  👉 https://customer-churn-backend-7hly.onrender.com/

---

## 📸 Screenshots


<img width="1912" height="867" alt="Screenshot 2026-02-08 233011" src="https://github.com/user-attachments/assets/4ae0eda9-bacd-4402-9ae3-e629e7292001" />




---

## 🎥 Project Demo Video

![ScreenRecording2026-02-08234907-ezgif com-optimize](https://github.com/user-attachments/assets/12f59b56-fbfd-4b37-b5ef-893c45ebd99a)



---

## 📊 Machine Learning Notebook

The ML model was trained and evaluated using a Jupyter / Colab notebook.

- **Notebook / Blog**:  
  👉 https://colab.research.google.com/drive/1iIzi4ln8iJiOkc3QF-I1IQkJ6RiD-Q2r#scrollTo=zmAdjrRhDxXz

The notebook covers:
- Data preprocessing  
- Feature engineering  
- Model training  
- Threshold selection  
- Performance evaluation  

---

## 📁 Repositories

### Backend Repository
FastAPI API serving churn predictions.

👉 https://github.com/Rabindrajena/customer-churn-backend

**Tech:** FastAPI, Scikit-learn, Pandas  
**Deployment:** Render

---

### Frontend Repository
User interface for interacting with the prediction system.

👉 https://github.com/Rabindrajena/customer-churn-ui

**Tech:** React, Vite  
**Deployment:** Vercel

---

## ⚙️ How to Run Locally (Quick Setup)

### 1️⃣ Backend
```bash
git clone https://github.com/Rabindrajena/customer-churn-backend.git
cd customer-churn-backend
pip install -r requirements.txt
uvicorn main:app --reload
```
---

### 2️⃣ Frontend

```bash
git clone https://github.com/Rabindrajena/customer-churn-ui.git
cd customer-churn-ui
npm install
npm run dev
```

---

## ✅ Key Highlights

* End-to-end ML deployment

* Clean separation of frontend & backend

* Real-time predictions

* Cloud-hosted & production-ready

* Fully documented & reproducible

  ---

## 🚀 Future Improvements

* Authentication & user history

* Interactive charts for churn trends

* Model retraining pipeline

* Monitoring & logging

  ---

### 👤 Author

**Rabindra Jena**

⭐ If you found this project useful, feel free to star the repositories!
