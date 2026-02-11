# 🏦 Loan Default Prediction - End to End ML Pipeline

## 📌 Project Overview

This project builds a complete Machine Learning pipeline to predict whether a borrower is likely to default on a loan. The workflow follows industry best practices including preprocessing, feature encoding, pipeline creation, cross-validation, and model serialization.

---

## 📊 Dataset Description

The dataset contains borrower demographic, financial, and loan-related attributes used to predict **loan_default**.

### 🔑 Features

| Column Name                | Description                                                              |
| -------------------------- | ------------------------------------------------------------------------ |
| **name**                   | Applicant's name (not used for modeling)                                 |
| **identification_through** | Mode of identification submitted by the applicant                        |
| **cibil_score**            | Credit score representing creditworthiness                               |
| **age**                    | Age of the borrower                                                      |
| **annual_income**          | Yearly income of the applicant                                           |
| **employment_type**        | Employment category (e.g., salaried, self-employed)                      |
| **years_of_employment**    | Total years of employment                                                |
| **existing_loans**         | Number of active loans                                                   |
| **loan_amount**            | Amount requested by the borrower                                         |
| **loan_tenure_years**      | Loan repayment duration                                                  |
| **interest_rate**          | Interest rate applied to the loan                                        |
| **debt_to_income_ratio**   | Ratio of total debt to annual income                                     |
| **marital_status**         | Applicant's marital status                                               |
| **education_level**        | Highest education attained                                               |
| **property_owner**         | Whether the applicant owns property                                      |
| **loan_purpose**           | Reason for taking the loan                                               |
| **loan_default**           | **Target variable** — indicates if the borrower defaulted (1) or not (0) |

---

## 🚀 Key Features of This Project

✅ End-to-end Scikit-Learn pipeline
✅ Automated preprocessing using **ColumnTransformer**
✅ OneHotEncoding for categorical variables
✅ Train-test split for unbiased evaluation
✅ Stratified Cross Validation
✅ Decision Tree based classification
✅ Model persistence using **Pickle / Joblib**
✅ Clean, production-style workflow

---

## 🧠 Problem Statement

Loan defaults pose a major financial risk to lending institutions.
The goal of this project is to build a machine learning model that can **accurately classify high-risk borrowers**, enabling smarter lending decisions.

---

## ⚙️ Tech Stack

* Python
* Pandas
* NumPy
* Scikit-Learn
* Matplotlib

---

## 🔄 Machine Learning Workflow

1️⃣ Data Understanding
2️⃣ Feature Selection
3️⃣ Train-Test Split
4️⃣ Data Preprocessing with ColumnTransformer
5️⃣ Pipeline Creation
6️⃣ Model Training (Decision Tree)
7️⃣ Cross Validation
8️⃣ Model Export

---

## 📈 Model Performance

Cross-validation ensures the model generalizes well to unseen data.

👉 *(Update this after running CV)*

Example:

```
Average Accuracy: 0.80
Average F1 Score: 0.79
```

---

## 💾 Model Persistence

The trained pipeline is saved using Pickle/Joblib, allowing predictions without rebuilding preprocessing steps.

---

---

## 🔮 Future Improvements

* Hyperparameter tuning with GridSearchCV
* Try ensemble models like RandomForest and XGBoost
* Feature importance visualization
* Deploy the model using Flask/FastAPI
* Build an interactive prediction UI

---

## 👨‍💻 Author

**Uday Kumar Gupta**

⭐ If you found this project useful, consider starring the repository!
