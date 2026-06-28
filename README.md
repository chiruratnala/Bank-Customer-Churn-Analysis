# Bank Customer Churn Analysis: Predictive Insights & Retention Strategies

## 📌 Executive Summary
This repository contains a comprehensive data analytics project focused on diagnosing and mitigating customer attrition within a commercial banking institution. By leveraging historical demographic and financial data, this analysis identifies pivotal variables driving customer churn and provides actionable, data-driven strategies to optimize customer retention and maximize lifetime value (CLV).

## 🎯 Business Objective
The primary objective of this analysis is to:
1. Determine the baseline churn rate across the institution.
2. Identify high-risk customer segments based on demographic and behavioral indicators.
3. Formulate strategic recommendations to enhance customer satisfaction, engagement, and retention.

## 🛠️ Technology Stack
* **Data Storage & Extraction:** SQL
* **Data Cleaning & Exploration:** Python (Pandas, NumPy), Microsoft Excel
* **Data Visualization & Dashboarding:** Power BI
* **Version Control:** Git & GitHub

## 📂 Dataset Overview
The primary dataset utilized for this analysis is encapsulated in **Customer-Churn-Records.xlsx**. It contains structured records detailing customer demographics, account information, and interaction history.

**Data Dictionary (Key Features):**
* `CreditScore`: The numerical representation of the customer's creditworthiness.
* `Geography`: The customer's country of residence (e.g., France, Spain, Germany).
* `Gender`: The customer's biological sex.
* `Age`: The customer's age in years.
* `Balance`: The current available balance in the customer's primary account.
* `NumOfProducts`: The aggregate number of bank products the customer is utilizing.
* `HasCrCard`: Binary indicator of credit card possession (1 = Yes, 0 = No).
* `IsActiveMember`: Binary indicator of recent account activity and engagement (1 = Active, 0 = Inactive).
* `Complain`: Binary indicator of whether the customer has formally lodged a complaint (1 = Yes, 0 = No).
* `Churn` (Target Variable): Binary indicator of whether the customer has exited the bank (1 = Churned, 0 = Retained).

## 📊 Interactive Dashboard & Key Performance Indicators

<img width="975" height="722" alt="image" src="https://github.com/user-attachments/assets/0f9c97c1-3558-4806-8772-a62d51565e17" />


### Granular Insights & Findings
An extensive exploratory data analysis (EDA) yielded the following critical observations:

1. **Systemic Churn Baseline:** The overarching churn rate stands at **20.38%**, indicating a substantial volume of exiting capital.
2. **The Complaint-to-Churn Pipeline:** There is a catastrophic **99.51% conversion rate** from registered complaints to eventual churn. This highlights a severe systemic failure in dispute resolution and customer recovery protocols.
3. **Demographic Vulnerability:** The **46–60 age demographic** represents the highest-risk cohort, demonstrating an attrition rate of **51.12%**. 
4. **Credit-Tier Attrition:** Customers occupying the lowest credit score bracket (**350–449**) churn at an accelerated rate of **33%**, whereas rates stabilize near 20% for prime and super-prime credit tiers.
5. **Engagement Deficits:** Customers classified as "Inactive Members" exhibit a significantly elevated churn rate (**26.87%**) compared to their highly engaged counterparts.

## 💡 Strategic Business Recommendations
Based on the analytical findings, the following interventions are recommended:

* **Overhaul Customer Service Protocols:** Given the 99.51% complaint-to-churn metric, immediate restructuring of the grievance redressal department is imperative. Implement a proactive "service recovery paradox" strategy to immediately follow up on logged complaints with specialized retention officers.
* **Targeted Wealth Management for Ages 46-60:** Design and deploy tailored financial products (e.g., retirement planning, premium deposit accounts) specifically marketed to the 46-60 demographic to increase product dependency and reduce the 51.12% churn rate.
* **Incentivize Engagement:** Develop automated, behavior-triggered campaigns to re-engage "Inactive Members." This could include promotional APY rates, waived fees for utilizing multiple products, or gamified credit card rewards.

## 🚀 Repository Structure & Execution
1. Clone this repository to your local environment.
2. Ensure you have the requisite visualization software (Power BI/Excel) installed to interact with the raw dashboard files.
3. The raw data can be inspected within the `Customer-Churn-Records.xlsx` file.
👨‍💻 Author
------------

**Chiru Ratnala**

Aspiring **Data Analyst**

If you found this project helpful, feel free to ⭐ **star the repository!**
