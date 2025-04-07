# 🛠️ Predictive Maintenance System

A machine learning-based system that analyzes sensor data from industrial equipment to forecast failures and optimize maintenance schedules. This project helps industries reduce downtime, improve equipment lifespan, and transition from reactive to proactive maintenance.

---

## 📌 Features

- Real-time telemetry monitoring via UDP
- Historical data ingestion and preprocessing
- Supervised ML models for failure prediction (SVM, Random Forest, ANN, etc.)
- Performance metrics: Accuracy, Precision, Recall, F1-Score
- Dashboard-ready structure for visualization
- Scalable and modular codebase

---

## 🧠 Tech Stack

- **Programming Language:** Python
- **ML Libraries:** scikit-learn, pandas, numpy, matplotlib
- **Telemetry:** Custom UDP listener
- **Data:** Industrial sensor dataset (time-series)
- **Version Control:** Git

---

## 🧪 Machine Learning Models Used

| Model            | Description                          |
|------------------|--------------------------------------|
| Random Forest     | Ensemble tree-based classifier       |
| SVM               | Support Vector Machines              |
| ANN               | Simple Feedforward Neural Network    |
| Logistic Regression | Baseline performance model       |

---

## ⚙️ How It Works

1. Sensor data is collected from industrial machines.
2. A UDP listener captures real-time telemetry (optional).
3. Historical dataset is cleaned and preprocessed.
4. Features are selected and used to train ML models.
5. The model predicts potential failures.
6. Maintenance teams are alerted in advance.

---

## 📊 Results

The Random Forest classifier yielded the highest accuracy of **97%**, with excellent F1-Score and Recall. The system demonstrates reliable performance and can be integrated into existing CMMS/SCADA tools.

---

## 📂 Project Structure

