# 🧠 Logistic Regression: Binary Classification on Breast Cancer Dataset

## 📌 Objective
This project demonstrates how to build a **binary classifier** using **Logistic Regression**. The goal is to classify whether a tumor is **benign** or **malignant** using the **Breast Cancer Wisconsin Dataset**.

## 📊 Dataset
- **Source**: Built-in dataset from `scikit-learn`
- **Features**: 30 numeric features describing tumor characteristics
- **Target**: Binary labels (`0` = malignant, `1` = benign)
- **Samples**: 569

## 🛠️ Tools and Libraries
- `scikit-learn`: for model building and evaluation
- `pandas`, `numpy`: for data manipulation
- `matplotlib`: for visualization

## 📈 Steps Performed

### 1. Load and Explore Dataset
- Loaded from `sklearn.datasets`
- Printed shape, features, and label distribution

### 2. Preprocessing
- Split into training and testing sets (80/20)
- Standardized features using `StandardScaler`

### 3. Model Training
- Trained a **Logistic Regression** model using training data

### 4. Evaluation Metrics
- **Confusion Matrix**
- **Precision, Recall, F1-score**
- **ROC-AUC Score**
- **ROC Curve Visualization**

### 5. Sigmoid Function
- Plotted the **sigmoid** curve to explain logistic regression probability output

### 6. Threshold Tuning
- Changed the default threshold from 0.5 to 0.4
- Compared **precision** and **recall** at the new threshold

## 📊 Results Summary

| Metric           | Value         |
|------------------|---------------|
| Accuracy         | ~96%          |
| ROC-AUC Score    | ~0.99         |
| Precision (0.4)  | ~0.94         |
| Recall (0.4)     | ~0.99         |
