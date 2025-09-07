# Telco Customer Churn Analysis

## 📌 Project Overview
This project analyzes the **Telco Customer Churn dataset** to understand why customers leave a telecom company and to predict churn using machine learning models. The goal is to provide insights that can help improve customer retention strategies.

## 🗂️ Dataset
- **File:** `WA_Fn-UseC_-Telco-Customer-Churn.csv`
- **Source:** Kaggle / IBM Telco Customer Churn dataset
- **Features include:**  
  - Customer demographics (gender, age, etc.)  
  - Account information (contract type, payment method, tenure)  
  - Services subscribed (phone, internet, streaming, etc.)  
  - Churn indicator (`Yes`/`No`)  

## 📝 Project Workflow
1. **Data Cleaning & Preprocessing**  
   - Handle missing values  
   - Convert categorical variables into numerical values  
   - Remove unnecessary columns  

2. **Exploratory Data Analysis (EDA)**  
   - Analyze churn rates across different customer segments  
   - Visualize correlations between features  
   - Identify patterns and trends  

3. **Feature Engineering**  
   - Create meaningful features to improve model performance  

4. **Model Building & Evaluation**  
   - Test different classification models (e.g., Logistic Regression, Random Forest)  
   - Evaluate model performance using accuracy, precision, recall, and F1-score  

5. **Insights & Recommendations**  
   - Identify key factors contributing to customer churn  
   - Suggest actionable strategies to improve customer retention  

## 📊 Key Insights (Example)
- Customers with **month-to-month contracts** are more likely to churn.  
- **Long-term contracts** and **automatic payments** reduce churn probability.  
- High usage of multiple services increases the likelihood of retention.  

## 🛠️ Technologies Used
- Python 3 
- Jupyter Notebook  
- Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  
