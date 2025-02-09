# AI-Based Anomaly Detection in Industrial Equipment Sensors

## Overview
This project applies **machine learning** to detect **anomalies in industrial equipment sensor data**, preventing failures and optimizing maintenance schedules. Using **NASA’s Turbofan Engine Degradation Dataset**, we train models to identify early failure risks.

## Features
✔ **Preprocessing & Feature Engineering** – Cleaning and transforming sensor data.  
✔ **Exploratory Data Analysis (EDA)** – Identifying key sensor anomalies.  
✔ **Anomaly Detection (Isolation Forest, Local Outlier Factor)** – Detecting unusual patterns.  
✔ **Fault Classification (Random Forest, XGBoost)** – Predicting machine failures.  
✔ **Interactive Dashboard (Streamlit)** – Real-time anomaly predictions.  

## 📂 Project Structure
```plaintext
AI_Anomaly_Detection_NASA/
├── data/
│   ├── train_FD001.txt      # Training Data
│   ├── test_FD001.txt       # Test Data
│   ├── RUL_FD001.txt        # Remaining Useful Life (RUL) labels
│   ├── README.md            # Dataset description
├── notebooks/
│   ├── anomaly_detection.ipynb
├── src/
│   ├── preprocessing.py
│   ├── model_training.py
│   ├── inference.py
├── requirements.txt
├── README.md
```

## 🚀 Installation & Setup
```bash
pip install -r requirements.txt
```

## 📊 Running the Project
```bash
python src/preprocessing.py
python src/model_training.py
python src/inference.py
```

## 📚 Dataset
🔗 **[NASA C-MAPSS Dataset](https://www.nasa.gov/content/prognostics-center-of-excellence-data-set-repository)**

## 📬 Contact
**Author:** Prabhani Gunasekera  
🔗 LinkedIn: [LinkedIn Profile](https://www.linkedin.com/in/prabhanigunasekera/)  
💻 GitHub: [GitHub Profile](https://github.com/prabhanig)  

