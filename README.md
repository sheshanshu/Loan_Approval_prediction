# Loan Approval Prediction

## Overview
The **Loan Approval Prediction** project uses machine learning to predict whether a loan application should be approved or rejected based on various applicant details. The objective is to assist financial institutions in making data-driven decisions while minimizing risk.

## Project Objectives
- **Data Cleaning & Preprocessing:** Handle missing values, outliers, and categorical variables.
- **Exploratory Data Analysis (EDA):** Understand patterns and correlations.
- **Feature Engineering:** Optimize input variables for better model performance.
- **Model Training & Evaluation:** Train and test different machine learning models.
- **Prediction & Insights:** Provide an accurate model for loan approval.

## Dataset
The dataset consists of information about loan applicants, including:
- **Applicant Income**
- **Coapplicant Income**
- **Loan Amount & Term**
- **Credit History**
- **Property Area**
- **Employment & Education Details**
- **Loan Approval Status (Target Variable)**

## Methodology
### 1. Data Preprocessing
- Handling missing values and outliers
- Encoding categorical variables
- Standardizing numerical features

### 2. Exploratory Data Analysis (EDA)
- Distribution of loan statuses
- Income and loan amount relationships
- Impact of credit history on approvals

### 3. Model Training & Evaluation
- **Logistic Regression**
- **Decision Tree Classifier**
- **Random Forest Classifier**
- **Support Vector Machine (SVM)**
- **XGBoost**
- **Evaluation Metrics:** Accuracy, Precision, Recall, F1-score

### 4. Model Performance Comparison
- Selecting the best model based on accuracy and other metrics
- Hyperparameter tuning for optimization

## Key Findings
- Applicants with a **credit history** have a significantly higher chance of loan approval.
- **Self-employed applicants** tend to have a lower approval rate.
- Higher **applicant income and lower loan amounts** increase approval chances.
- **Random Forest** and **XGBoost** models performed best.

## Technologies Used
- **Python:** Data analysis & machine learning
- **Jupyter Notebook:** Code execution & visualization
- **Pandas, NumPy:** Data manipulation
- **Matplotlib, Seaborn:** Data visualization
- **Scikit-Learn, XGBoost:** Model training & evaluation

## Repository Structure
```
├── dataset/                   # Raw dataset
├── notebooks/                 # Jupyter Notebook files
├── models/                    # Trained models
├── visuals/                   # Saved plots & visualizations
├── README.md                  # Project documentation
```

## How to Run the Notebook
1. Clone the repository:
   ```bash
   git clone https://github.com/sheshanshu/Loan_Approval_Prediction.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
4. Run the `Loan_Approval_Prediction.ipynb` file.

## Links
- **GitHub Repository:** [Project Repo](https://github.com/sheshanshu/Loan_Approval_Prediction)
- **Research Resources:** Wikipedia, ResearchGate, Academia.edu, W3Schools, GeeksforGeeks

## Author
**Sheshanshu Kumar**  
📧 sheshanshu1996@gmail.com  
🎓 Uttaranchal University, Uttarakhand

## Acknowledgments
Thanks to YHills Edutech Private Limited for the opportunity to work on this project.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
