# 📊 Telecom Customer Churn Analysis
## 📌 Project Objective
To analyze and predict customer churn in the telecom industry and derive actionable retention strategies using SQL, Python, and Power BI.

## 🛠 Tools & Technologies
- Python: Pandas, NumPy, Scikit-learn
- SQL: MySQL (data aggregation & churn metrics)
- Power BI: Interactive dashboard & insights
- ML Model: Logistic Regression
- Explainability: Feature importance using model coefficients
 
## 📂 Project Structure
telecom-customer-churn-analysis/
- ├── WA_Fn-UseC_-Telco-Customer-Churn.csv
- ├── churn_analysis.sql
- ├── Telecom_Churn_Analysis.ipynb
- ├── Customer_Churn_Report.pptx
- ├── Telecom_Churn_Dashboard.pbix
- ├── README.md
- └── requirements.txt

## 🔍 Analysis Workflow
1. Data Aggregation (SQL)
 - Overall churn rate
 - Churn by contract type
 - Churn distribution (Yes/No)
2. Exploratory Data Analysis (Python)
 - Churn vs tenure
 - Churn vs monthly charges
 - Contract type impact
3. Churn Prediction Model
 - Binary classification using Logistic Regression
 - Model evaluation using accuracy score
4. Model Explainability
 - Feature importance using model coefficients
 - Key drivers: Contract type, tenure, monthly charges
5. Customer Segmentation
 - Loyal customers
 - Dormant customers
 - At-risk customers
6. Visualization
 - Interactive Power BI dashboard
 - Business-focused churn insights

## 📈 Power BI Dashboard Insights
- Overall churn percentage
- Churn rate by contract type
- Monthly charges vs churn
- Customer segmentation analysis
- Interactive filters for deeper insights

## 📌 Key Findings
- Month-to-month contract customers have the highest churn rate
- Short-tenure customers are more likely to churn
- Higher monthly charges increase churn probability

## 🎯 Final Outcome
- This project helps telecom companies:
- Identify high-risk customers
- Understand key churn drivers
- Improve customer retention strategies using data-driven insights

## 🚀 How to Run the Project
1. Install dependencies:
pip install -r requirements.txt
2. Open Jupyter Notebook:
Telecom_Churn_Analysis.ipynb
3. Open Power BI dashboard:
Telecom_Churn_Dashboard.pbix

## 📌 Dataset Source
- Kaggle – Telco Customer Churn Dataset
