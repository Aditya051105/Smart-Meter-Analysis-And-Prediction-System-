# ⚡ Smart Meter Analysis & Energy Consumption System

## 📌 Project Description  
This project is a **Smart Energy Monitoring System** that tracks electricity usage in real-time using sensors and analyzes the data using basic Machine Learning techniques.

The system helps users understand their electricity consumption, detect unusual usage, and reduce energy waste.

---

## 🎯 Objectives  

- Monitor real-time electricity consumption  
- Analyze daily and monthly usage  
- Detect abnormal energy usage  
- Predict future consumption  
- Help users save electricity  

---

## 🚀 Key Features  

- 🔌 Real-time energy monitoring  
- 📊 Usage dashboard (daily / monthly)  
- ⚠️ High consumption alerts  
- 🤖 Basic AI-based prediction  
- 📉 Graph visualization of usage  
- 🔍 Anomaly detection (theft or unusual usage)  

---

## 🏗️ System Architecture  

Sensors → Microcontroller → Backend (Django) → Database → Frontend Dashboard  

---

## ⚙️ Technologies Used  

- **Hardware:** Arduino / ESP32  
- **Backend:** Django (Python)  
- **Frontend:** HTML, CSS, JavaScript  
- **Database:** MySQL / SQLite  
- **Machine Learning:** scikit-learn  

---

## 🔄 How It Works  

1. Sensors measure voltage and current  
2. Microcontroller sends data to backend  
3. Backend stores data in database  
4. Dashboard shows:
   - Energy usage  
   - Graphs  
   - Alerts  
5. ML model:
   - Predicts future usage  
   - Detects abnormal patterns  

---

## 🤖 Machine Learning Part  

- **Prediction Model:** Linear Regression  
- **Anomaly Detection:** Isolation Forest  

Example:  
If electricity usage suddenly increases at an unusual time → system generates alert ⚠️  

---

## 📁 Project Structure  

smart-meter-system/
│
├── backend/
├── frontend/
├── models/
├── data/
├── templates/
├── static/
└── README.md

---

## 🛠️ Setup Instructions  

### 1. Clone Repository  
```bash
git clone https://github.com/your-username/smart-meter-system.git
cd smart-meter-system
