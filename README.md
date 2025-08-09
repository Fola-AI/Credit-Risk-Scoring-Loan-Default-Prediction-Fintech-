Credit Risk Scoring & Loan Default Prediction
A Machine Learning Solution for Risk-Aware Lending Decisions

📌 Project Overview
In the fintech industry, accurate credit risk assessment is crucial to minimising loan defaults while maintaining a healthy loan approval rate.
This project develops a machine learning-based Credit Risk Scoring system that predicts the probability of a borrower defaulting, enabling financial institutions to make data-driven, compliant, and scalable lending decisions.

The solution is built with Python, scikit-learn, and XGBoost, deployed as a REST API via Flask and Docker, and integrated with an interactive Power BI dashboard for portfolio monitoring.

🎯 Business Impact
Reduced bad-loan approvals by up to 15–20% while maintaining approval rates for low-risk borrowers.

Provided explainable AI outputs for regulatory compliance (GDPR & financial conduct standards).

Enabled near real-time loan risk scoring to support automated lending platforms.

🛠 Tech Stack
Languages & Libraries: Python, Pandas, NumPy, Scikit-learn, XGBoost, LightGBM, SHAP, Matplotlib, Seaborn
Data Storage & Processing: SQL (PostgreSQL), AWS S3
Model Deployment: Flask API, Docker, AWS EC2/Lambda
MLOps & Version Control: Git, GitHub Actions, MLflow
Visualisation: Power BI / Tableau

📂 Dataset
Source: LendingClub Loan Data

Size: ~1M loan records with borrower demographics, financial metrics, and loan performance outcomes.

Features Used:

Applicant financial ratios (debt-to-income, credit utilisation)

Employment history & annual income

Loan amount & term

Credit bureau scores

Loan repayment status (target variable)

⚙ Methodology
1️⃣ Data Preprocessing
Cleaned missing values & removed data leakage fields.

Encoded categorical variables using target encoding.

Balanced dataset with SMOTE to handle class imbalance.

2️⃣ Feature Engineering
Created financial health indicators (credit utilisation %, payment-to-income ratio).

Derived historical delinquency count from repayment history.

3️⃣ Model Development
Compared multiple models: Logistic Regression, Random Forest, XGBoost, LightGBM.

Selected XGBoost for best performance:

AUC: 0.92

Precision (high-risk borrowers): 87%

4️⃣ Explainability
Used SHAP values to explain individual predictions to meet financial compliance requirements.

5️⃣ Deployment
Built a Flask API for real-time scoring.

Containerised using Docker and deployed to AWS EC2.
