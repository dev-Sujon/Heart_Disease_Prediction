# ❤️ Heart Disease Prediction - Cleveland Dataset

This project aims to predict the **presence of heart disease** in a patient using machine learning techniques on the **Cleveland Heart Disease dataset**. This is a classic dataset in the medical ML field, originally contributed by multiple institutions and frequently used in ML research.

---

## 📊 Dataset Overview

The original dataset contains **76 attributes**, but only a subset of **14** features is commonly used in published experiments.

- **Source**: UCI Machine Learning Repository
- **Focus**: Cleveland database (most commonly used in ML research)
- **Target (`goal`)**: Indicates the presence of heart disease, with values from `0` (no disease) to `4` (severe condition).
    - For binary classification:
      - `0` = No disease
      - `1–4` = Disease presence

### 🏥 Acknowledgements

**Creators**:
- Hungarian Institute of Cardiology, Budapest — *Andras Janosi, M.D.*
- University Hospital, Zurich — *William Steinbrunn, M.D.*
- University Hospital, Basel — *Matthias Pfisterer, M.D.*
- V.A. Medical Center, Long Beach and Cleveland Clinic Foundation — *Robert Detrano, M.D., Ph.D.*

**Donor**:  
David W. Aha ([aha@ics.uci.edu](mailto:aha@ics.uci.edu))

---

## 🎯 Project Objective

Build a machine learning model to predict heart disease and identify potential **early signs** or **risk patterns** in cardiovascular data.

**Bonus Goal**: Explore if there are any trends or predictors related to **specific cardiovascular events** or **heart health** conditions.

---

## 🔍 Workflow

1. Data Cleaning & Preprocessing
2. Exploratory Data Analysis (EDA)
3. Feature Engineering (select the 14 key features)
4. Model Training (Logistic Regression, Random Forest, XGBoost, etc.)
5. Evaluation (Accuracy, Precision, Recall, ROC-AUC)
6. (Optional) Streamlit App for real-time predictions

---

## 📂 Features Used (Standard 14)

Typical attributes used in ML studies include:

- `age`
- `sex`
- `cp` (chest pain type)
- `trestbps` (resting blood pressure)
- `chol` (serum cholesterol)
- `fbs` (fasting blood sugar)
- `restecg` (resting electrocardiographic results)
- `thalach` (maximum heart rate)
- `exang` (exercise-induced angina)
- `oldpeak` (ST depression)
- `slope` (slope of the ST segment)
- `ca` (number of major vessels)
- `thal`
- `target` (presence of heart disease)

---

## 🛠 Tech Stack

- **Python**
- **Pandas, NumPy**
- **Matplotlib, Seaborn**
- **Scikit-learn**
- **XGBoost / LightGBM**
- **Streamlit** *(for app deployment)*

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clonehttps://github.com/dev-Sujon/Heart_Disease_Prediction
cd heart_Disease_Prediction
