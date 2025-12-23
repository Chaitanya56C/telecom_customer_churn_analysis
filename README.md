📊 Telecom Customer Churn Analysis
📌 Project Objective
To analyze and predict customer churn in the telecom industry and derive actionable retention strategies using SQL, Python, and Power BI.
🛠 Tools & Technologies
Python: Pandas, NumPy, Scikit-learn
SQL: MySQL (data aggregation & churn metrics)
Power BI: Interactive dashboard & insights
ML Model: Logistic Regression
Explainability: Feature importance using model coefficients
📂 Project Structure
Copy code

telecom-customer-churn-analysis/
│
├── data/
│   └── WA_Fn-UseC_-Telco-Customer-Churn.csv
│
├── sql/
│   └── churn_analysis.sql
│
├── notebook/
│   └── Telecom_Churn_Analysis.ipynb
│
├── report/
│   ├── Customer_Churn_Report.pptx
│   └── Telecom_Churn_Dashboard.pbix
│
├── README.md
└── requirements.txt
🔍 Analysis Workflow
Data Aggregation (SQL)
Overall churn rate
Churn by contract type
Churn distribution (Yes/No)
Exploratory Data Analysis (Python)
Churn vs tenure
Churn vs monthly charges
Contract type impact
Churn Prediction Model
Binary classification using Logistic Regression
Model evaluation using accuracy score
Model Explainability
Feature importance using model coefficients
Key drivers: Contract type, tenure, monthly charges
Customer Segmentation
Loyal customers
Dormant customers
At-risk customers
Visualization
Interactive Power BI dashboard
Business-focused churn insights
📈 Power BI Dashboard Insights
Overall churn percentage
Churn rate by contract type
Monthly charges vs churn
Customer segmentation analysis
Interactive filters for deeper insights
📌 Key Findings
Month-to-month contract customers have the highest churn rate
Short-tenure customers are more likely to churn
Higher monthly charges increase churn probability
🎯 Final Outcome
This project helps telecom companies:
Identify high-risk customers
Understand key churn drivers
Improve customer retention strategies using data-driven insights
🚀 How to Run the Project
Install dependencies:
Copy code

pip install -r requirements.txt
Open Jupyter Notebook:
Copy code

Telecom_Churn_Analysis.ipynb
Open Power BI dashboard:
Copy code

Telecom_Churn_Dashboard.pbix
📌 Dataset Source
Kaggle – Telco Customer Churn Dataset
