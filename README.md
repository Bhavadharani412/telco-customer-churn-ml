# Customer Churn Prediction using Machine Learning

## 📌 Project Overview

Customer churn prediction is a critical business problem where organizations aim to identify customers who are likely to discontinue their services. This project focuses on building and evaluating multiple machine learning classification models to predict customer churn based on demographic, service usage, and billing-related features.

The goal is to compare different algorithms, analyze their performance, and identify the most suitable model for churn prediction.

---

## 📊 Dataset

- **Source:** Kaggle (Telco / Customer Churn Dataset)
- **Type:** Supervised classification
- **Target Variable:** `Churn` (Yes / No)

### Key Features
- Customer demographics (gender, senior citizen status)
- Account information (tenure, contract type, payment method)
- Service usage (internet service, streaming services)
- Billing details (monthly charges, total charges)

---

## ⚙️ Project Workflow

1. Data Loading and Exploration
2. Data Preprocessing
   - Handling missing values
   - Encoding categorical features
   - Feature scaling
3. Train–Test Split
4. Model Training
5. Model Evaluation
6. Model Comparison
7. Best Model Selection

---

## 🧠 Machine Learning Models Used

The following models were trained and evaluated:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Decision Tree
- Random Forest
- Gradient Boosting
- AdaBoost
- XGBoost
- Naive Bayes

---

## 📈 Model Performance (Test Accuracy)

| Model | Test Accuracy |
|------|---------------|
| Logistic Regression | 91.2% |
| K-Nearest Neighbors | 96.5% |
| Support Vector Machine | 94.8% |
| Decision Tree | 91.4% |
| Random Forest | 96.2% |
| Gradient Boosting | 93.5% |
| AdaBoost | 90.3% |
| XGBoost | 95.7% |
| Naive Bayes | 84.4% |

---

## 🏆 Best Model

- **Model:** K-Nearest Neighbors (KNN)
- **Configuration:** `n_neighbors = 3`, `weights = 'distance'`
- **Test Accuracy:** **96.5%**

KNN performed best on this dataset due to strong similarity patterns and locally separable feature space.

---

## 📉 Evaluation Metrics

- Accuracy
- Confusion Matrix
- Precision, Recall, F1-score

Accuracy was used as the primary metric for comparison, with additional metrics analyzed to understand classification behavior.

---

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Scikit-learn
- XGBoost
- Matplotlib / Seaborn

---

## 🚀 How to Run the Project

1. Clone the repository
   ```bash
   git clone https://github.com/Bhavadharani412/telco-customer-churn-ml.git
