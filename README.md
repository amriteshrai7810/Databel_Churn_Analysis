# Databel Telecom Customer Churn Analysis

This project focuses on analyzing customer churn for **Databel**, a leading telecommunications provider. Using **Advanced Excel** and data analytics techniques, the study aims to uncover the drivers of churn and provide actionable insights to improve customer retention.

Dashboard Link: [Telecom Churn Analysis Live Dashboard](https://1drv.ms/x/c/f7b6f4461d511de9/IQCU2yI9eMzEQKKJoyQoeAA_ATyPZmEddHA_6OAXutyK7PQ?e=j0eGxl)

---

## Objective
- **Understand Churn Rates**:
  - Calculate the overall churn rate and identify high-churn customer groups.
- **Identify Key Drivers**:
  - Determine factors contributing to churn, such as account length, subscription type, charges, and customer service interactions.
- **Analyze Customer Segments**:
  - Examine patterns in churn based on demographics, contract types, and payment methods.
- **Provide Recommendations**:
  - Devise strategies to reduce churn and improve customer loyalty.


 ![image](https://github.com/user-attachments/assets/6e0a335e-09fe-49b0-8770-419019f80f35)



---

## Key Insights
- **Churn Rates**:
  - Customers in **California (CA)** have the highest churn rate at **63%**.
  - There is no gender-based disparity in churn rates.
- **Drivers of Churn**:
  - **Customer Service Calls**:
    - A negative correlation (0.64) between churn and customer service call frequency.
    - Churn rate increases significantly (from 36% to 87%) when customers make more than 2 service calls.
  - **Account Length**:
    - Weak correlation (-0.35) with churn, showing longer account tenure slightly reduces churn probability.
  - **Data Usage**:
    - Customers with lower data usage (<3GB) churn at a higher rate, with a **13% difference** compared to higher data users.
  - **Average Monthly Charges**:
    - Churned customers pay an average of **$8 more** than retained customers.
- **Demographics**:
  - No significant churn differences based on gender.
  - Contract types and payment methods show strong categorical relationships with churn, analyzed using contingency tables.
- **Segmentation**:
  - Researched churner types: **Conditional loyal subscribers**, **conditional churners**, **lifestyle migrators**, and **unsatisfied customers**.

---

## Steps in Analysis
1. **Data Preparation**:
   - Used Power Query to handle null values and clean data.
   - Verified data types and column quality for analysis.
2. **Exploratory Data Analysis**:
   - Created pivot tables and charts for churn by demographics, customer service calls, and data usage.
   - Used bar-of-pie charts to explore churn categories.
3. **Advanced Statistical Analysis**:
   - Calculated correlations (e.g., Point Biserial Correlation) between churn and variables like account length and customer service calls.
4. **Visualization**:
   - Built interactive charts, including churn by demographics, top churn reasons, and churn distribution comparisons.

---

## Tools Used
- **Microsoft Excel**:
  - PivotTables
  - Power Query and Power Pivot
  - DAX calculations
  - Bar and pie charts
- Statistical Analysis (Point Biserial Correlation)

---

## Conclusion
This analysis provides critical insights into customer churn patterns for Databel. By addressing high-churn customer segments and improving customer service quality, Databel can reduce churn rates and enhance customer satisfaction.
