📊 Telco Customer Churn Prediction
📌 Project Overview

Customer churn is a critical problem in the telecom industry — retaining existing customers is often more cost-effective than acquiring new ones. This project uses the Telco Customer Churn Dataset (Kaggle) to predict whether a customer is likely to churn.

🔎 Objectives

Build a machine learning model to predict churn.

Identify the key factors driving churn.

Provide business insights for customer retention.

🛠 Tech Stack

Python

Libraries: pandas, numpy, seaborn, matplotlib, scikit-learn, XGBoost

📂 Dataset

Dataset: Telco Customer Churn

~7,000 customer records with demographics, services, and account information.

Target variable: Churn (Yes/No).

🔬 Approach

Data Preprocessing

Handled missing values (TotalCharges).

Encoded categorical features.

Scaled numerical features.

Exploratory Data Analysis (EDA)

Visualized churn distribution.

Compared churned vs non-churned by contract type, tenure, and monthly charges.

Modeling

Trained Logistic Regression, Random Forest, and XGBoost.

Logistic Regression gave the best performance.

Evaluation

Accuracy, Precision, Recall, F1-score, ROC-AUC.

Confusion Matrix to visualize prediction performance.

📈 Results

Logistic Regression achieved the best balance of accuracy and interpretability.

Key churn drivers:

Month-to-month contracts → higher churn risk.

Short tenure → higher churn risk.

Higher monthly charges → higher churn risk.

💡 Business Insights

Encourage customers to switch to longer-term contracts.

Provide discounts or bundled offers for high-charge customers.

Focus retention campaigns on new customers with short tenure.

