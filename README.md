# AI-Powered Predictive Maintenance System

## 📖 Overview
This repository contains my capstone project for **ITAI2277**, focused on building an intelligent **predictive maintenance (PdM)** solution for industrial equipment.  
The system leverages **machine learning** and **deep learning** to forecast equipment failures, estimate remaining useful life (RUL), and optimize maintenance schedules — reducing downtime and operational costs.

---

## 🚀 Key Features
- **Data Integration**
  - Real-time IoT sensor streams (vibration, temperature, pressure)
  - Historical maintenance logs
- **Hybrid Modeling**
  - Random Forests for failure classification
  - LSTM neural networks for time-series forecasting
  - Ensemble voting for balanced accuracy + interpretability
- **Explainability**
  - SHAP visualizations for transparent predictions
- **Interactive Dashboard**
  - Streamlit app with real-time monitoring, alerts, and scenario testing
- **Deployment Ready**
  - Dockerized pipeline with CI/CD integration
  - Kafka streaming support for scalability

---

## 📊 Impact
- Achieved **>85% prediction accuracy** on the NASA Turbofan Engine Degradation dataset  
- Simulated **40% downtime reduction** and **25% maintenance cost savings**  
- Promotes sustainability by reducing unnecessary part replacements and energy waste  

---

## 🛠️ Tech Stack
- **Languages & Libraries:** Python, Pandas, NumPy, Scikit-learn, TensorFlow, SHAP, Streamlit  
- **Data:** NASA CMAPSS dataset + synthetic edge cases  
- **Infrastructure:** Flask API, PostgreSQL, Apache Kafka, Docker, GitHub Actions  
- **Experiment Tracking:** MLflow  

---

## 📂 Repository Structure
