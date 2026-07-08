# 📊 Customer Churn Prediction

### End-to-End Machine Learning Pipeline for Customer Retention Analysis

<p align="center">

<img src="https://img.shields.io/badge/Python-3.11-blue?style=for-the-badge&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas&logoColor=white"/>
<img src="https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white"/>
<img src="https://img.shields.io/badge/XGBoost-Gradient%20Boosting-EC6B23?style=for-the-badge"/>
<img src="https://img.shields.io/badge/LightGBM-Boosting-9ACD32?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Models-4-success?style=for-the-badge"/>
<img src="https://img.shields.io/badge/License-MIT-black?style=for-the-badge"/>

</p>

<p align="center">

<b>Machine Learning project for predicting customer churn in the telecommunications industry.</b>

Developed as an end-to-end Data Science pipeline covering data preparation, feature engineering, model training, evaluation, and visualization.

</p>

---

# 📌 Overview

Customer churn is one of the biggest challenges for subscription-based companies.

Acquiring a new customer is considerably more expensive than retaining an existing one, making churn prediction a valuable business application.

This project implements a complete **Machine Learning pipeline** using the **IBM Telco Customer Churn** dataset to identify customers at high risk of cancellation.

The project was designed following real-world Data Science practices, from data preprocessing to comparative evaluation of multiple machine learning algorithms.

---

# 🎯 Objectives

- Predict customer churn
- Compare multiple machine learning models
- Perform Exploratory Data Analysis (EDA)
- Engineer informative features
- Evaluate models using multiple classification metrics
- Produce publication-quality visualizations

---

# 🧠 Machine Learning Pipeline

```text
                    IBM Telco Customer Churn Dataset
                                   │
                                   ▼
                        Data Cleaning & Validation
                                   │
                                   ▼
                     Exploratory Data Analysis (EDA)
                                   │
                                   ▼
                         Feature Engineering
                                   │
                                   ▼
                  Label Encoding + One-Hot Encoding
                                   │
                                   ▼
                           Feature Scaling
                                   │
                                   ▼
        ┌─────────────────────────────────────────────────────┐
        │ Logistic Regression │ Random Forest │ XGBoost │ LGBM│
        └─────────────────────────────────────────────────────┘
                                   │
                                   ▼
                     Comparative Model Evaluation
                                   │
                                   ▼
ROC Curves • Precision-Recall Curves • Confusion Matrices • Feature Importance
```

---

# 📊 Dataset

**IBM Telco Customer Churn Dataset**

| Feature | Description |
|----------|-------------|
| Customers | 7,043 |
| Features | Demographic, contract, billing and service information |
| Target | Customer Churn |
| Task | Binary Classification |

---

# ⚙️ Feature Engineering

Several additional variables were created to improve predictive performance.

| Feature | Description |
|----------|-------------|
| TenureGroup | Customer lifetime category |
| NumServices | Number of subscribed services |
| AvgMonthlySpend | Average monthly spending |
| IsNewHighValue | High-value new customers |
| HasInternetNoProtection | Internet users without protection services |
| MonthToMonthElectronicCheck | High-risk contract/payment combination |

---

# 🤖 Models

| Model | Description |
|--------|-------------|
| Logistic Regression | Linear baseline classifier |
| Random Forest | Ensemble of decision trees |
| XGBoost | Gradient Boosting |
| LightGBM | Histogram-based Gradient Boosting |

---

# 📈 Evaluation Metrics

The models are evaluated using multiple performance metrics.

| Metric | Purpose |
|----------|----------|
| Accuracy | Overall performance |
| Precision | False positive control |
| Recall | Churn detection capability |
| F1-score | Precision/Recall balance |
| ROC-AUC | Ranking performance |
| PR-AUC | Performance on imbalanced data |

---

# 📷 Visualizations

The project automatically generates several visualizations.

## 📊 Exploratory Data Analysis

<p align="center">
  <img src="01_distribuicao_churn.png" width="48%">
  <img src="02_churn_por_categoria.png" width="48%">
</p>

<p align="center">
  <img src="03_numericas_por_churn.png" width="48%">
  <img src="04_correlacao.png" width="48%">
</p>

<p align="center">
  <img src="05_tenure_vs_monthly.png" width="70%">
</p>

---

## 📈 Model Evaluation

<p align="center">
  <img src="06_comparacao_metricas.png" width="48%">
  <img src="07_curvas_roc.png" width="48%">
</p>

<p align="center">
  <img src="08_curvas_precision_recall.png" width="48%">
  <img src="09_matrizes_confusao.png" width="48%">
</p>

<p align="center">
  <img src="10_feature_importance.png" width="48%">
  <img src="11_radar_comparativo.png" width="48%">
</p>

---

# 📂 Repository Structure

```text
customer-churn-prediction/

│

├── README.md

├── LICENSE

├── requirements.txt

├── churn_prediction.py

├── metrics_comparison.csv

├── figures/

├── models/

└── notebooks/
```

---

# 🚀 Installation

Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/customer-churn-prediction.git
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run

```bash
python churn_prediction.py
```

---

# 🛠 Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- XGBoost
- LightGBM

---

# 📌 Highlights

✅ End-to-End Data Science Pipeline

✅ Data Cleaning

✅ Exploratory Data Analysis

✅ Feature Engineering

✅ Feature Scaling

✅ Four Machine Learning Models

✅ Comparative Evaluation

✅ Publication-quality Figures

✅ Automatic Metrics Comparison

---

# 🔮 Future Improvements

- Hyperparameter Optimization (Optuna)
- SHAP Explainability
- Streamlit Dashboard
- FastAPI API
- Docker Deployment
- MLflow Integration
- Automated Unit Tests
- CI/CD with GitHub Actions

---

# 📚 References

IBM Telco Customer Churn Dataset

Scikit-Learn Documentation

XGBoost Documentation

LightGBM Documentation

---

# 👨‍💻 Author

**Vinícius Nunes Leal**

Physicist | Scientist Researcher
