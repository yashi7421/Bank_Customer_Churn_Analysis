**📉 Bank_Customer_Churn_Analysis**

This project analyzes customer churn behavior using interactive Power BI dashboards built on a structured Excel dataset. The objective is to identify churn patterns, key risk factors, and actionable insights to improve customer retention.

**📊 Project Overview:**

- Customer churn is a critical KPI that directly affects business growth and revenue.
- This project explores churn trends across multiple dimensions such as credit card usage, geography, age, gender, and credit score.

**The dashboards are designed to:**

1] Identify high-risk customer segments.

2] Track churn trends over time.

3] Support data-driven retention strategies.

**🛠️ Tools Used:**

- Power BI – Data modeling, DAX, and dashboard development.
- Microsoft Excel – Data storage and preprocessing.

**📂 Dataset Description:**

The dataset follows a star schema model consisting of one fact table and multiple dimension tables:

| Table Name     | Columns                                                                                                                     |
| -------------- | --------------------------------------------------------------------------------------------------------------------------- |
| CustomerInfo   | CustomerID, Surname                                                                                                         |
| ActiveCustomer | ActiveID, ActiveCategory                                                                                                    |
| ExitCustomer   | ExitID, ExitCategory                                                                                                        |
| CreditCard     | CreditID, Category                                                                                                          |
| Geography      | GeographyID, GeographyLocation                                                                                              |
| Gender         | GenderID, GenderCategory                                                                                                    |
| Date Master    | Date, Month, Month Order, Year                                                                                              |
| Bank_Churn     | CustomerID, Age, Balance, CreditScore, Bank DOJ, Exited, EstimatedSalary, GenderID, CreditID, ExitID, GeographyID, ActiveID |

**🗂️ Data Model (Schema):**

- Fact Table: Bank_Churn
- Dimension Tables: CustomerInfo, Geography, Gender, CreditCard, ActiveCustomer, ExitCustomer, Date
- Designed using a star schema for efficient analysis.

**🔗 = Relationships Between Tables:**

<h3 align="center">Schema Diagram</h3>

<p align="center">
  <img src="images/Schema Diagram.png" width="800"/>
</p>

**❓ Key Business Questions:**

1] What is the overall churn and retention rate?

2] How does churn vary across months and years?

3] Which gender contributes more to churn?

4] Do credit card holders churn more than non-holders?

5] Which credit score categories are high risk?

6] How does churn differ across France, Germany, and Spain?

7] Which age group shows the highest churn behavior?

**📊 Power BI Dashboards:**

**1. Customer Churn Overview Dashboard:**
- KPI cards (Total, Active, Inactive, Exit)
- Monthly churn trends
- Credit score & credit card analysis

<h3 align="center">Customer Churn Overview Dashboard</h3>

<p align="center">
  <img src="images/Dashboard_1.png" width="800"/>
</p>

**2. Customer Retention & Trend Dashboard:**
- Geography-wise churn
- Age-based churn behavior
- Yearly and monthly churn in %

<h3 align="center">Customer Retention & Trend Dashboard</h3>

<p align="center">
  <img src="images/Dashboard_2.png" width="800"/>
</p>

**🔍 Key Insights:**

| Category          | Insight                                                                      |
| ----------------- | ---------------------------------------------------------------------------- |
| Churn Rate        | ~20% (2,037 customers exited)                                                |
| Retention         | 7,963 customers retained                                                     |
| Customer Split    | Active: 51.5% • Inactive: 48.5%                                              |
| Credit Card Usage | ~70% of churn from credit card holders                                       |
| Geography         | France: Highest customers • Germany: Highest churn rate • Spain: Most stable |
| Age Group         | 35–50 years → Highest churn                                                  |
| Gender            | Male customers contribute ~56% of churn                                      |
| Credit Score      | Fair & Poor categories → Highest churn                                       |
| Trend             | Churn stable between 16%–26% across years                                    |

<h3 align="center">Insights of Dashboard - 1</h3>

<p align="center">
  <img src="images/Insights_1.png" width="800"/>
</p>

<h3 align="center">1Insights of Dashboard - 2</h3>

<p align="center">
  <img src="images/Insights_2.png" width="800"/>
</p>

**✅ Conclusion:**

This dashboard helps businesses to:
- Identify high-risk customer segments.
- Understand churn drivers across multiple dimensions.
- Improve customer retention strategies.
- Make data-driven decisions using interactive visual insights.
