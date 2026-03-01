# 🎗 Breast Cancer Classification – Machine Learning Model Comparison

A machine learning project that predicts whether a tumor is **malignant or benign** using supervised classification algorithms.

This project compares multiple models and evaluates performance using industry-standard metrics such as **Accuracy, Precision, Recall, F1-Score, and ROC-AUC**.

---

## 🚀 Key Features

- Binary classification (Malignant vs Benign)
- Exploratory Data Analysis (EDA)
- Feature preprocessing and scaling
- Model comparison:
  - Logistic Regression
  - Random Forest
  - XGBoost
- Evaluation metrics:
  - Accuracy
  - Precision
  - Recall
  - F1-Score
  - ROC-AUC
- Feature importance analysis
- Confusion matrix visualization

---

## 📊 Dataset

- **Wisconsin Breast Cancer Dataset**
- Features extracted from digitized breast mass images
- Target variable:
  - `0` → Benign
  - `1` → Malignant

---

## 🛠 Tech Stack

- Python
- Pandas
- NumPy
- Scikit-Learn
- XGBoost
- Matplotlib / Seaborn
- Jupyter Notebook

---

## 📈 Model Performance

| Model               | Accuracy | ROC-AUC |
|---------------------|----------|---------|
| Logistic Regression | 96%      | 0.98    |
| Random Forest       | 97%      | 0.99    |
| XGBoost             | 98%      | 0.99    |


---

## 📌 Key Insights

- Ensemble models outperformed linear models.
- ROC-AUC close to 1 indicates strong classification capability.
- Feature importance analysis identified top predictive features influencing diagnosis.

---

## ⚠️ Disclaimer

This project is for educational purposes only and does not provide medical diagnosis.
