# AI-Driven Anomaly Detection System 🔍
_A Data-Driven Approach Combining Statistical, ML, and Generative Models_

[![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)]()
[![Framework](https://img.shields.io/badge/TensorFlow-2.10+-orange.svg)]()
[![License](https://img.shields.io/badge/License-MIT-green.svg)]()

---

### 🧠 Overview
This project demonstrates a complete anomaly-detection pipeline for simulated retail sales data (2010–2018) spanning **multiple stores and products**.  
The objective is to identify unusual sales patterns using both classical and generative modeling techniques.

---

### 📊 Contents
1. **Exploratory Data Analysis (EDA):**  
   Visualizes overall trends, seasonality, and distribution of daily sales.

2. **Anomaly Detection Methods:**
   - **Rolling Z-Score:** Detects deviations from a local moving average.  
   - **Isolation Forest:** Unsupervised tree-based outlier detection.  
   - **STL Residuals:** Seasonality-aware decomposition and residual analysis.  
   - **Autoencoder & LSTM Autoencoder:** Reconstruction-based anomaly detection (Generative approach).

3. **Evaluation & Insights:**
   - Cross-validation between classical and generative models.  
   - Threshold tuning (percentile-based and statistical).  
   - Ensemble voting for reliable anomaly consensus.

---

### ⚙️ Environment & Dependencies
Developed in **Python 3.10+** using:
`pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `statsmodels`, `tensorflow`

Install dependencies:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn statsmodels tensorflow
```

---

### 🧩 Project Highlights
- Integrates statistical, machine-learning, and neural-network-based methods in one unified workflow.  
- Demonstrates data validation, seasonality handling, and interpretability.  
- Ready for deployment or extension with live time-series feeds.  

---

### 📂 Folder Structure
```
AI-Driven-Anomaly-Detection-System/
│
├── anomaly_detection.ipynb      # Main notebook
├── train.csv                    # Dataset
├── README.md                    # Documentation
└── requirements.txt             # Optional dependency file
```

---

### 🧾 Author
**Ninad Sarang**  
Email: [your.email@example.com]  
Date: November 2025  

---

### 🧠 License
Released under the MIT License.  
Feel free to fork, modify, and build upon this work.

---
