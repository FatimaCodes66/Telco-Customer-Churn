# Telco Customer Churn Analysis & Prediction

## Project Overview
This project analyzes customer behavior to identify factors leading to churn and builds a predictive model using Python. The goal is to provide actionable business insights to reduce customer churn.

## Dataset
The dataset can be downloaded from:  
[Telco Customer Churn Dataset](https://raw.githubusercontent.com/blastchar/telco-customer-churn/master/Telco-Customer-Churn.csv)

---

## Tools & Libraries
- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-Learn
- Joblib

---

## Steps Performed
1. **Data Loading & Cleaning**  
   - Checked for missing values  
   - Converted data types  
   - Handled missing and inconsistent data  

2. **Exploratory Data Analysis (EDA)**  
   - Countplots for churn distribution  
   - Churn by contract type, gender, and payment method  
   - Correlation heatmap  

3. **Feature Engineering & Encoding**  
   - Converted categorical variables to numeric using get_dummies  
   - Dropped unnecessary columns  

4. **Model Training**  
   - Split data into training and test sets  
   - Trained Random Forest Classifier  

5. **Model Evaluation**  
   - Accuracy, Precision, Recall, F1-Score, ROC-AUC  
   - Confusion matrix visualization  

6. **Feature Importance Analysis**  
   - Identified top features contributing to churn  

7. **Business Insights & Recommendations**  
   - Strategies to reduce churn based on analysis  

---

## Key Insights
- **Month-to-month contract** customers churn the most.  
- Customers with **short tenure (0–6 months)** are more likely to churn.  
- **Fiber optic internet** customers churn more frequently.  
- **High monthly charges** increase churn risk.  
- Customers **without online security or tech support** churn more.  

---

## Business Recommendations
- Promote **long-term contracts** with incentives  
- Offer **loyalty discounts** for high-charge customers  
- Improve **fiber optic service quality**  
- Bundle **online security and tech support services**  
- Target **new customers** with retention campaigns  

---

## Model Performance
- **Accuracy:** (insert your value here, e.g., 88%)  
- **ROC-AUC:** (insert your value here, e.g., 0.82)  

---

## Notebook
The full project notebook is available:  
`Customer_Churn_Prediction_Project.ipynb`  

---

## How to Run
1. Download the dataset from the link above  
2. Open `Customer_Churn_Prediction_Project.ipynb` in Jupyter Notebook  
3. Run all cells step by step to reproduce the analysis and visualizations
