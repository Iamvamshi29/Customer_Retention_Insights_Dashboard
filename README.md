📊 Customer_Retention_Insights_Dashboard


This project focuses on analyzing customer churn patterns for a telecom company using Power BI and Exploratory Data Analysis (EDA) in Python.
The goal is to identify key factors influencing churn and provide actionable insights to improve customer retention.

🚀 Project Overview

Dataset: Telco Customer Churn (7,043 records, 22 columns).

Churn Rate: ~27% (0.27).

Tech Stack:

🐍 Python (EDA, preprocessing)

📊 Power BI (dashboards, visualizations)

📝 Microsoft Excel/SQL (data handling)

🔍 Key Insights
1. Customer Demographics

Gender distribution is balanced (≈50% Male, 50% Female).

Dependents: Majority (≈70%) have no dependents.

Partners: Split is nearly equal (No: 3.6K, Yes: 3.4K).

2. Churn Analysis

Churn Rate: 27% (1 in 4 customers leave).

Contract Type:

Month-to-Month customers have the highest churn.

Two-Year contracts show lowest churn.

Payment Methods:

Customers paying via electronic check churn more compared to auto-payment methods.

3. Tenure Analysis

Median Tenure: 29 months.

Average Tenure: 32.4 months.

Churned customers generally have much lower tenure than retained customers.

4. Risk Indicators (EDA)

High Monthly Charges → Higher churn probability.

Senior Citizens → More likely to churn.

Longer Tenure & Higher Total Charges → Lower churn risk.

📈 Dashboards

Interactive Power BI dashboards provide:
![Dashboard1](https://github.com/user-attachments/assets/4ee12e30-3c2f-4778-83cf-2f6d9657b79e)
![Dashboard2](https://github.com/user-attachments/assets/2f116bf5-449f-40dc-89c5-7b414ef1222e)


Customer breakdown by gender, partner, and dependent status.
![Task1](https://github.com/user-attachments/assets/194d02a1-3473-49fc-b31f-70fe59b64263)


Tenure distribution (box plot, histogram).
![Task2](https://github.com/user-attachments/assets/46f06c14-ca8e-4064-a1d6-4cfb06bed345)


Churn comparison by tenure, contract type, and payment method.

![Task3](https://github.com/user-attachments/assets/1f1357d7-aa2b-4b2e-a587-b893ab0e5335)

Key retention KPIs.
![Task4](https://github.com/user-attachments/assets/cbf06d5a-60be-4610-8d7e-7c7793465912)


Sample Visuals:

![Dashboard1](https://github.com/user-attachments/assets/4ee12e30-3c2f-4778-83cf-2f6d9657b79e)
![Dashboard2](https://github.com/user-attachments/assets/2f116bf5-449f-40dc-89c5-7b414ef1222e)




📂 Project Files

Project Report.pdf → Summary of dashboards & insights

Telco_EDA_Summary_Report_EN.docx → EDA findings & correlations

project.pbix → Power BI dashboard file

ProjectVideo.mp4 → Walkthrough of the dashboard

Task1.jpg - Task4.jpg → Screenshots of dashboard sections

🛠 Next Steps

Feature engineering (e.g., tenure buckets, bundled services).

Build predictive churn models (Logistic Regression, Random Forest, XGBoost).

Implement explainability (e.g., SHAP values) for decision support.

Recommend retention strategies for high-risk segments.

📌 How to Use

Clone this repo:

git clone https://github.com/your-username/telco-customer-churn.git


Open project.pbix in Power BI to explore dashboards.

Review EDA findings in Telco_EDA_Summary_Report_EN.docx.

🎥 Demo

👉 Click here to watch the project demo

🏷 Tags

#PowerBI #DataAnalytics #CustomerChurn #EDA #Python #Telco
