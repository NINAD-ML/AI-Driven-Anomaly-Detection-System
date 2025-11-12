## Anomaly Detection

**Author:** Ninad Sarang  


---

### Overview
This notebook implements a multi-method anomaly detection pipeline for simulated sales dataset (2010–2018), which spans **7 unique stores** and **10 unique products**.  
The goal is to detect unusual sales patterns across time using both classical and generative approaches.

---

### Contents
1. **Exploratory Data Analysis (EDA):**  
   Visualizes overall trends, seasonality, and distribution of daily sales.

2. **Anomaly Detection Methods:**
   - **Rolling Z-Score:** Statistical deviation from moving mean.  
   - **Isolation Forest:** Unsupervised tree-based anomaly isolation.  
   - **STL Residuals:** Seasonality-aware decomposition and residual analysis.  
   - **Autoencoder & LSTM Autoencoder:** Reconstruction-based anomaly detection (Generative approach).

3. **Evaluation:**
   - Cross-validation between generative and classical models.  
   - Threshold tuning (e.g., 95th percentile, mean + 3σ).  
   - Ensemble insights to improve reliability.

---

###  Environment & Dependencies
Developed in **Python 3.10+** using the following libraries:  
`pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `statsmodels`, and `tensorflow`.

Install dependencies via:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn statsmodels tensorflow
```

---

### Notes
- All code runs end-to-end in Google Colab or Jupyter Notebook.  
- Outputs and plots are embedded in the final notebook.  
- The analysis is self-contained and reproducible.

---

### Submission Structure
```
│Anomaly Detection .zip
├── Anomaly Detection .ipynb
├── train.csv
└── README.md
```

---


