# Customer Churn Prediction Using Logistic Regression

## Description
This project uses Logistic Regression to predict customer churn for a telecommunications company. The goal is to identify customers likely to leave, enabling targeted retention strategies. The dataset contains customer demographics, account details, service subscriptions, and churn status, providing a comprehensive basis for modeling.

---

## Dataset Information

The dataset captures historical customer information where each row represents a unique customer. It includes:

- **Churn:** Whether the customer left within the last month (target variable)  
- **Services:** Subscriptions such as phone service, multiple lines, internet, online security, online backup, device protection, tech support, streaming TV and movies  
- **Account Information:** Customer tenure, contract type, payment method, paperless billing, monthly charges, and total charges  
- **Demographics:** Gender, age range, presence of partners and dependents  

This data supports analysis to uncover behaviors and factors contributing to customer retention or churn, helping businesses design focused retention programs.

---

## Methodology
- Data cleaning and preprocessing, including handling missing values and encoding categorical variables  
- Exploratory data analysis to identify important features  
- Training a Logistic Regression model to classify churn vs. retention  
- Evaluating model performance with metrics such as accuracy, precision, recall, F1-score, and ROC-AUC  
- Interpretation of model coefficients to understand feature impact  

---

## Results
The Logistic Regression model provides actionable insights into factors driving customer churn, assisting telecom providers in minimizing loss and improving customer loyalty.

---

## Usage

Clone the repository and install dependencies:

```bash
git clone https://github.com/AbuOmayed/customer-churn-logistic-regression.git
cd customer-churn-logistic-regression
pip install -r requirements.txt
jupyter notebook notebooks/customer_churn_logistic_regression.ipynb
