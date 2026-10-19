# Bank-CRM-Analysis
Bank Customer Relationship Management (CRM) & Churn Analysis
Project Overview
This project analyzes banking customer data to understand customer churn, identify the customer groups most likely to leave, and recommend practical strategies to improve customer retention and satisfaction. The analysis combines SQL-based data exploration with an interactive Power BI dashboard to turn customer and account information into actionable business insights.

The dataset contains 10,000 customers across seven related tables and covers customers in France, Germany, and Spain. The project examines customer demographics, account balances, credit scores, product holdings, credit-card ownership, activity status, tenure, and exit status.
Business Problem
The bank wants to reduce customer churn, improve service delivery, and increase customer satisfaction. The goal of this project is to uncover patterns in customer behavior and identify regional, demographic, and account-related factors associated with customers leaving the bank.
Project Objectives
- Measure the overall customer churn rate and compare churn across years and months.
- Analyze churn by geography, gender, age group, credit-score segment, active status, and credit-card ownership.
- Explore relationships between churn, account balance, tenure, estimated salary, and number of banking products.
- Identify customer segments that may need targeted retention efforts.
- Build an interactive Power BI dashboard to monitor key metrics and explore trends.
- Translate findings into recommendations for customer engagement and retention.
Dataset
The project uses seven tables:
Table	Description
Bank_Churn	Customer account attributes and churn-related fields, including balance, credit score, tenure, product count, active status, and exit status.
CustomerInfo	Customer details such as customer ID, surname, estimated salary, date of joining, age, gender ID, and geography ID.
CreditCard	Credit-card ownership categories.
ActiveCustomer	Active-customer category information.
ExitCustomer	Customer exit-status categories.
Gender	Gender category lookup.
Geography	Geography/region lookup.


The presentation describes the dataset as containing 10,000 customers and reports no missing or null values in the supplied analysis.
Tools & Technologies
- MySQL – relational data analysis and querying
- SQL – joins, CTEs, subqueries, aggregations, conditional logic, window functions, date functions, and statistical calculations
- Microsoft Power BI – interactive dashboard and data visualization
- Microsoft PowerPoint – presentation of findings and recommendations
Analysis Performed
The SQL analysis addresses questions such as:
- Regional distribution of customer account balances
- Highest estimated-salary customers joining in the final quarter of the latest year in the data
- Average product usage among credit-card holders
- Churn rate by gender and geography
- Credit-score segments and their exit rates
- Active customers with tenure greater than five years
- Churn comparison between credit-card holders and non-holders
- Most common number of products held by exited customers
- Yearly and monthly customer-joining trends
- Account-balance patterns among exited customers
- Potential account-balance outliers among customers who remained
- Customer segmentation by age, gender, geography, and credit-card status
Power BI Dashboard
The Power BI report contains four pages:
1. Overview – headline metrics such as total customers, churn rate, active customers, average balance, and average credit score.
2. Churn Analysis – churn comparisons by gender, geography, credit segment, active status, age group, and number of products.
3. Customer Segmentation – customer distribution by age group, geography, active status, and credit segment, alongside balance and tenure views.
4. Trends & Insights – customer-joining trends over time, average balance by product count, and customer distribution by geography.
The report includes slicers for dimensions such as gender, geography, credit segment, and age group to support interactive exploration.
Key Findings
The project presentation highlights the following findings:
- The overall customer churn rate is approximately 20.37%.
- Germany has the highest regional churn rate, at approximately 32%.
- Female customers show a churn rate of approximately 25% in the presented analysis.
- Customers aged 50 and above have the highest churn among the age groups compared.
- Inactive customers have a higher churn rate than active customers (27% vs. 14%).
- Churn increases notably among customers holding three or four products.
- The year 2017 is identified as the peak churn year in the 2016–2019 trend shown.
- Credit-card holders have a comparatively lower churn rate than customers without credit cards.
These are findings reported in the project's presentation and should be interpreted in the context of the dataset and analysis performed.
Business Recommendations
Based on the analysis, the project proposes the following actions:
- Re-engage inactive customers through personalized SMS, email, and app communication, along with suitable engagement incentives.
- Prioritize retention outreach for customer groups showing higher churn, using relevant demographic and account characteristics.
- Review product-bundling and cross-selling practices, particularly for customers holding more than two products.
- Consider suitable credit-card and rewards offers for eligible customers, while monitoring their effect on retention.
- Strengthen the early customer experience and monitor customers for signs of disengagement.
- Collect feedback from exited customers to identify service issues and opportunities for improvement.
Repository Structure
Bank_CRM_Analysis/
├── Bank_CRM_Final.sql
├── BANK_CRM_ANALYSIS.docx
├── BANK_CRM_ANALYSIS.pptx
└── Bank_CRM.pbix
- Bank_CRM_Final.sql – SQL queries used for the analysis.
- BANK_CRM_ANALYSIS.docx – project documentation, questions, SQL queries, explanations, and recommendations.
- BANK_CRM_ANALYSIS.pptx – presentation of the analysis and its findings.
- Bank_CRM.pbix – Power BI dashboard report.
How to Use
1. Set up a MySQL environment.
2. Obtain and import the source dataset tables using the table names and column structures referenced in Bank_CRM_Final.sql. The ZIP archive contains the SQL script and project deliverables; it does not include separate source-data files.
3. Open Bank_CRM_Final.sql in MySQL Workbench or another compatible SQL client and execute the queries after the required tables have been imported.
4. Open Bank_CRM.pbix in Power BI Desktop to explore the dashboard. If prompted, configure the data source connection to the location of your imported dataset.
5. Use the report slicers to filter the dashboard and investigate customer segments and churn patterns.
Project Outcome
The project demonstrates how SQL analysis and Power BI reporting can be combined to investigate customer churn, understand differences across customer segments, monitor retention-related metrics, and communicate data-informed recommendations to banking stakeholders.
