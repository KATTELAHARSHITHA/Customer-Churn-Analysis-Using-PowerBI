# 📊 Customer Churn Analysis – Power BI Project

## 📌 Project Overview

This project presents an interactive **Power BI dashboard** built on the **Telco Customer Churn dataset**. The objective is to analyze customer demographics, service subscriptions, billing details, and contract types to uncover the drivers of customer churn. The dashboard provides actionable insights that can help businesses improve customer retention and revenue.

## 🎯 Objectives

* Calculate and monitor **churn rate** across the customer base.
* Analyze **customer demographics** (gender, age group, tenure) and their impact on churn.
* Evaluate **service subscriptions** (phone, internet, add-ons) and churn correlation.
* Compare **billing & contract types** to identify high-risk segments.
* Highlight **cross-selling opportunities** and customer lifetime value.
* Provide interactive filters and drill-through capabilities for deeper exploration.

## 📂 Dataset Description

The dataset includes **7,043 customer records** with the following attributes:

* `customerID`: Unique customer identifier
* `gender`, `SeniorCitizen`, `Partner`, `Dependents`
* `tenure`: Number of months with the company
* `PhoneService`, `MultipleLines`, `InternetService` (DSL, Fiber optic, None)
* `OnlineSecurity`, `OnlineBackup`, `DeviceProtection`, `TechSupport`
* `StreamingTV`, `StreamingMovies`
* `Contract`: Month-to-month, One year, Two year
* `PaperlessBilling`, `PaymentMethod`
* `MonthlyCharges`, `TotalCharges`
* `Churn`: Customer status (Yes/No)

## 📊 Dashboard Features

* **KPI Cards**: Total Customers, Churned Customers, Churn Rate, Average Monthly Charges, Average Tenure
* **Demographics Analysis**: Gender vs. Churn, Senior Citizen impact, Tenure distribution
* **Service Insights**: Internet type vs. Churn, Add-on services, Most common churn combinations
* **Billing & Contracts**: Churn by contract type, payment method, paperless billing impact
* **Churn Drivers**: Factors influencing churn, revenue impact of lost vs. retained customers
* **Interactive Features**: Slicers for gender, contract type, internet service, and payment method; drill-through pages for detailed analysis

 ## 🛠️ Tools Used

* **Power BI Desktop** – Dashboard creation and DAX modeling
* **DAX Expressions** – Calculated measures (churn rate, average charges, retention KPIs)
* **Telco Customer Churn Dataset** – CSV file

## 🚀 Key Insights

* Customers with **month-to-month contracts** have the highest churn.
* **Fiber optic internet** users show higher churn compared to DSL.
* **Senior citizens** and customers with **higher monthly charges** are more likely to churn.
* Customers with **multiple bundled services** are less likely to churn, indicating strong cross-selling opportunities.


