# 🏦 Loan Approval Prediction Using Machine Learning

An end-to-end Machine Learning project that analyzes applicant information and predicts whether a loan application is likely to be approved.

## 📌 Project Overview

This project focuses on predicting loan approval outcomes using applicant financial and demographic information.

The project covers data preprocessing, exploratory data analysis, feature engineering, model training, and model evaluation.

## 🎯 Objectives

- Understand the factors associated with loan approval.
- Handle missing values and prepare the dataset.
- Perform Exploratory Data Analysis (EDA).
- Apply categorical encoding and feature scaling.
- Train and compare multiple Machine Learning models.
- Evaluate models using classification metrics.

## 🛠️ Technologies & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## 📂 Project Structure

```text
Loan-Approval-Prediction/
│
├── data/
│   └── loan_approval_data.csv
│
├── notebooks/
│   └── Loan_Approval_Model.ipynb
│
├── images/
│
├── README.md
├── requirements.txt
└── .gitignore
```

## 📊 Dataset Information

- Total records: 1,000
- Total columns: 20
- Target variable: `Loan_Approved`

The dataset contains information related to:

- Applicant income
- Co-applicant income
- Employment status
- Credit score
- Existing loans
- Debt-to-income ratio
- Savings
- Collateral value
- Loan amount and term
- Loan purpose
- Property area

## ⚙️ Project Workflow

1. Data Loading and Understanding
2. Missing Value Treatment
3. Exploratory Data Analysis (EDA)
4. Outlier Analysis
5. Categorical Encoding
6. Correlation Analysis
7. Train-Test Split
8. Feature Scaling
9. Machine Learning Model Training
10. Model Evaluation
11. Feature Engineering
12. Model Comparison

## 🤖 Machine Learning Models

Three classification algorithms were implemented:

1. Logistic Regression
2. K-Nearest Neighbors (KNN)
3. Gaussian Naive Bayes

## 📈 Model Evaluation

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

Based on the saved notebook results:

| Model | Accuracy | Precision | Recall | F1-Score |
|---|---:|---:|---:|---:|
| Logistic Regression | 86.50% | 78.33% | 77.05% | 77.69% |
| KNN | 79.00% | 73.17% | 49.18% | 58.82% |
| Naive Bayes | 86.50% | 80.36% | 73.77% | 76.92% |

Naive Bayes achieved the highest precision, while Logistic Regression achieved the highest recall and F1-score.

## 🚀 How to Run This Project

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/Loan-Approval-Prediction.git
```

### 2. Navigate to the project directory

```bash
cd Loan-Approval-Prediction
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

### 5. Open the notebook

Navigate to:

`notebooks/Loan_Approval_Model.ipynb`

Run the cells to explore the analysis and model training.

## 🔮 Future Improvements

- Build an interactive loan prediction web application.
- Perform hyperparameter tuning.
- Improve model generalization.
- Use Scikit-learn Pipelines to prevent preprocessing data leakage.
- Deploy the model using Streamlit or Flask.

## 👨‍💻 Author

**Ranveer Singh**

MCA Student | Machine Learning | Python | Data Science

[GitHub Profile](https://github.com/ranveersinghh99)

---

⭐ If you find this project interesting, consider giving the repository a star!

*Disclaimer: This is an educational machine learning project, not a real-world loan approval system.*