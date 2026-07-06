# Task 2: End-to-End ML Pipeline with Scikit-learn Pipeline
# Customer Churn Prediction - End-to-End ML Pipeline

## 📌 Project Overview

This project is an End-to-End Machine Learning Pipeline developed as part of the AI/ML Engineering Internship at DevelopersHub Corporation.

The objective is to predict whether a customer is likely to churn using the Telco Customer Churn dataset. The project includes data preprocessing, model training, evaluation, hyperparameter tuning, and model deployment preparation.

---

## 🎯 Objective

To build a reusable and production-ready Machine Learning Pipeline that predicts customer churn accurately using different machine learning algorithms.

---

## 📂 Dataset

**Dataset:** Telco Customer Churn Dataset

Target Variable:

- Churn (Yes / No)

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Imbalanced-learn (SMOTE)
- XGBoost
- Joblib
- Pickle
- Jupyter Notebook

---

## 📊 Workflow

### 1. Data Loading

- Loaded the Telco Customer Churn dataset
- Checked data types and missing values

### 2. Data Preprocessing

- Removed unnecessary columns
- Converted TotalCharges to numeric
- Handled missing values
- Label Encoding of categorical features
- Feature Selection

### 3. Exploratory Data Analysis (EDA)

- Histograms
- Boxplots
- Correlation Heatmap
- Countplots

### 4. Train-Test Split

- 80% Training
- 20% Testing

### 5. Handling Imbalanced Data

- Applied SMOTE to balance customer churn classes

### 6. Model Training

The following models were trained:

- Decision Tree Classifier
- Random Forest Classifier
- XGBoost Classifier

### 7. Cross Validation

Performed 5-Fold Cross Validation for model comparison.

### 8. Model Evaluation

Evaluation metrics used:

- Accuracy Score
- Confusion Matrix
- Classification Report

### 9. Model Saving

The best-performing model was exported using Joblib/Pickle for future predictions.

---

## 📈 Results

The Random Forest model achieved the best overall performance for customer churn prediction.

Evaluation Metrics:

- Accuracy Score
- Precision
- Recall
- F1-Score

---

## 📁 Project Structure

```
customer-churn-ml-pipeline/
│
├── data/
│   └── WA_Fn-UseC_-Telco-Customer-Churn.csv
│
├── notebook/
│   └── Customer_Churn_Pipeline.ipynb
│
├── README.md
└── requirements.txt
```

---

## 🚀 How to Run

Clone the repository

```bash
git clone https://github.com/raheelanisar/customer-churn-ml-pipeline.git
```

Go to project folder

```bash
cd customer-churn-ml-pipeline
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run Jupyter Notebook

```bash
jupyter notebook
```

---

## 📦 Required Libraries

```text
pandas
numpy
matplotlib
seaborn
scikit-learn
imbalanced-learn
xgboost
joblib
pickle
```

---

## 📌 Future Improvements

- Hyperparameter Optimization using GridSearchCV
- Streamlit Deployment
- Feature Engineering
- Pipeline Automation
- Model Monitoring

---

## 👨‍💻 Author

**Raheela Nisar**

AI/ML Engineering Intern

DevelopersHub Corporation

---

## ⭐ Acknowledgement

This project was completed as part of the AI/ML Engineering Internship at DevelopersHub Corporation to gain hands-on experience in building production-ready Machine Learning pipelines.
