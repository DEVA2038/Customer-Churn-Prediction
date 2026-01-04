# 📊 Customer Churn Prediction using Machine Learning

This project predicts **customer churn** using supervised machine learning models.  
It includes **data preprocessing, exploratory data analysis (EDA), model training, evaluation, and comparison** using multiple classifiers.

---

## 🚀 Project Overview

Customer churn prediction helps businesses identify customers who are likely to leave a service.  
This project uses the **Churn Modelling dataset** and compares the performance of different machine learning models to predict churn.

---

## 📂 Dataset

- **File Name:** `Churn_Modelling.csv`
- **Target Variable:** `Exited`
  - `0` → Customer stayed
  - `1` → Customer exited
- **Dropped Columns:**
  - `RowNumber`
  - `CustomerId`
  - `Surname`

---

## 🧹 Data Preprocessing

### Categorical Encoding
- **Geography**
  - France → 0  
  - Germany → 1  
  - Spain → 2
- **Gender**
  - Female → 0  
  - Male → 1

### Feature Scaling
- Applied **StandardScaler** to normalize numerical features

### Train-Test Split
- Training set: 70%
- Testing set: 30%
- `random_state = 42`

---

## 📊 Exploratory Data Analysis (EDA)

The following visualizations are included:

1. **Churn Distribution**
   - Distribution of churned vs retained customers
2. **Correlation Heatmap**
   - Correlation between numerical features
3. **Confusion Matrix**
   - For each classification model
4. **ROC Curve Comparison**
   - Combined ROC curves with AUC scores
5. **Feature Importance**
   - Top 10 important features for tree-based models

---

## 🤖 Machine Learning Models Used

- **Logistic Regression**
- **Random Forest Classifier**
- **Gradient Boosting Classifier**

---

## 📈 Model Evaluation Metrics

Each model is evaluated using:
- Classification Report
  - Precision
  - Recall
  - F1-score
- Confusion Matrix
- ROC Curve and AUC Score

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## ▶️ How to Run the Project

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/customer-churn-prediction.git
cd customer-churn-prediction
