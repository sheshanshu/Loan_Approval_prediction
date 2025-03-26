# Loan_Approval_prediction

Open in Google Colab

Project Overview
This project aims to predict loan approval using EDA (Exploratory Data Analysis) and machine learning models such as Decision Trees, Random Forest, and Logistic Regression. The dataset is sourced from an Analytics Vidhya competition.

Problem Statement
Dream Housing Finance Company deals with home loans. Customers apply for loans, and the company determines their eligibility based on factors such as income, credit history, and demographics. The goal is to automate the loan approval process by identifying the key factors that influence eligibility.

Dataset Description
Variable	Description
Loan_ID	Unique Loan ID
Gender	Male/Female
Married	Applicant married (Y/N)
Dependents	Number of dependents
Education	Graduate/Undergraduate
Self_Employed	Self-employed (Y/N)
ApplicantIncome	Applicant income
CoapplicantIncome	Co-applicant income
LoanAmount	Loan amount (in thousands)
Loan_Amount_Term	Term of loan (in months)
Credit_History	Meets credit guidelines (1/0)
Property_Area	Urban/Semi-Urban/Rural
Loan_Status	Loan approved (Y/N)
Methodology
1️⃣ Data Preprocessing
Removed unnecessary columns (e.g., Loan_ID).

Handled missing values.

Encoded categorical features using one-hot encoding.

2️⃣ Exploratory Data Analysis (EDA)
Count Plots: Analyzed loan approval trends across various categorical features.

Box Plots: Explored relationships between numerical features and loan status.

3️⃣ Model Training & Evaluation
Implemented and compared the following machine learning models:
✔ Decision Tree Classifier
✔ Random Forest Classifier
✔ Logistic Regression

Performance metrics include accuracy, precision, recall, and F1-score.

Results & Insights
Credit History was the most important factor for loan approval.

Higher applicant income and loan amount correlated with higher approval chances.

Random Forest performed best among the models with the highest accuracy.

Installation & Usage
Install Dependencies
bash
Copy
Edit
pip install pandas numpy scikit-learn matplotlib seaborn
Run the Notebook
You can open and execute the Jupyter Notebook using:

bash
Copy
Edit
jupyter notebook Loan_Approval_Prediction.ipynb
Alternatively, use Google Colab.

Author
👤 Sheshanshu Kumar
LinkedIn | GitHub
