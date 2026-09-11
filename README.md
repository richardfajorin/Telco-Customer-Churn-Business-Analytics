# Telco Customer Churn Business Analytics Case Study

## Overview

This project analyzes customer churn in a telecommunications company using Python and data analytics techniques.

The goal is to understand **why customers are leaving, which customer segments have higher churn rates, and what the business can do to improve customer retention.**

The analysis was completed as part of the **AnalystLab Africa Data Analytics Internship Week 5 Business Analytics Case Study**.

---

## Business Problem

Customer churn can significantly affect revenue and long-term customer relationships.

The key questions investigated in this project are:

* What percentage of customers are leaving?
* Which customer characteristics are associated with higher churn?
* Does contract type influence churn patterns?
* How do monthly charges relate to churn?
* Does customer tenure affect churn?
* Which internet service and payment methods have higher churn rates?
* Which customer segments should receive greater retention attention?

---

## Dataset

The dataset contains **7,043 customer records** and information about:

* Customer demographics
* Contract type
* Tenure
* Monthly charges
* Total charges
* Internet service
* Payment method
* Online services
* Customer support services
* Churn status

### Target Variable

**Churn**

* `Yes` — customer left
* `No` — customer remained

---

## Tools & Technologies

* Python
* Pandas
* Matplotlib
* Seaborn
* Jupyter Notebook
* Data Cleaning
* Exploratory Data Analysis (EDA)
* Business Analytics

---

## Analysis Process

The project followed these major steps:

1. **Data Understanding**

   * Examined dataset structure
   * Checked rows, columns and data types
   * Reviewed summary statistics

2. **Data Preparation**

   * Checked for missing values
   * Converted variables where necessary
   * Prepared data for analysis

3. **Exploratory Data Analysis**

   * Analyzed overall churn
   * Compared churn across customer segments
   * Examined numerical variables
   * Created visualizations

4. **Driver Analysis**

   * Contract type
   * Tenure
   * Monthly charges
   * Internet service
   * Payment method
   * Customer support and security services

5. **Business Interpretation**

   * Identified high-risk customer segments
   * Translated analytical findings into business insights
   * Developed retention recommendations

---

## Key Findings

### Overall Churn

Out of **7,043 customers**:

* **1,869 customers churned**
* **5,174 customers remained**
* Overall churn rate: **26.54%**

Approximately one-quarter of the customer base had churned.

### Contract Type

| Contract       | Churn Rate |
| -------------- | ---------: |
| Month-to-month |     42.71% |
| One year       |     11.27% |
| Two year       |      2.83% |

Month-to-month customers had substantially higher churn rates than customers on longer contracts.

### Customer Tenure

| Tenure Group | Churn Rate |
| ------------ | ---------: |
| 0–12 months  |     47.44% |
| 13–24 months |     28.71% |
| 25–48 months |     20.39% |
| 49–72 months |      9.51% |

Customers in their first year showed the highest churn rate, indicating that the early customer relationship is an important retention period.

### Monthly Charges

Average monthly charges:

* Retained customers: **61.27**
* Churned customers: **74.44**

Churned customers had higher average monthly charges than retained customers.

### Internet Service

| Internet Service    | Churn Rate |
| ------------------- | ---------: |
| Fiber optic         |     41.89% |
| DSL                 |     18.96% |
| No internet service |      7.40% |

Fiber-optic customers showed the highest churn rate among the three groups.

### Payment Method

| Payment Method            | Churn Rate |
| ------------------------- | ---------: |
| Electronic check          |     45.29% |
| Mailed check              |     19.11% |
| Bank transfer (automatic) |     16.71% |
| Credit card (automatic)   |     15.24% |

Electronic-check users showed substantially higher churn than customers using automatic payment methods.

---

## Correlation Analysis

Correlation analysis showed the following relationships with churn:

| Variable        | Correlation |
| --------------- | ----------: |
| Tenure          |      -0.352 |
| Total Charges   |      -0.199 |
| Monthly Charges |       0.193 |
| Senior Citizen  |       0.151 |

Tenure had the strongest relationship with churn among the numerical variables analyzed.

> **Note:** Correlation indicates association, not causation.

---

## Business Insights

The analysis suggests that churn is not evenly distributed across the customer base.

The strongest patterns were observed among:

* Newer customers
* Month-to-month customers
* Customers with higher monthly charges
* Fiber-optic customers
* Electronic-check users
* Customers without online security or technical support services

These segments provide useful starting points for targeted customer-retention strategies.

---

## Recommendations

### 1. Strengthen Early-Customer Retention

Develop a structured onboarding and retention program for customers during their first 12 months.

### 2. Target Month-to-Month Customers

Identify month-to-month customers at higher risk and provide appropriate incentives or longer-term plan options.

### 3. Investigate Fiber-Optic Churn

Examine pricing, service quality, customer experience and support issues among fiber-optic customers.

### 4. Investigate Electronic-Check Customers

Understand why electronic-check users have higher churn and encourage convenient automatic payment options where appropriate.

### 5. Build a Churn-Risk Monitoring System

Develop a future predictive model that can identify customers with a high probability of churn before they leave.

---

## Project Structure

```text
Telco-Customer-Churn-Business-Analytics/
│
├── README.md
├── telco_churn_analysis.ipynb
├── telco_churn_analysis.py
│
├── data/
│   └── telco_customer_churn.csv
│
├── report/
│   └── Telco_Customer_Churn_Business_Analytics_Case_Study.docx
│
└── visuals/
    ├── churn_distribution.png
    ├── churn_by_contract.png
    ├── churn_by_tenure.png
    ├── churn_by_internet_service.png
    └── churn_by_payment_method.png
```

---

## Deliverables

* Business Analytics Case Study Report
* Python analysis notebook
* Data visualizations
* Business recommendations
* Presentation

---

## Future Improvements

Future versions of this project could include:

* Customer churn prediction using Machine Learning
* Feature engineering
* Customer segmentation
* Churn probability scoring
* Interactive Power BI dashboard
* Automated churn-risk monitoring

---

## Author

**Richard Fajorin**

Biomedical Engineering · Data · Software · AI

GitHub: [richardfajorin](https://github.com/richardfajorin)

---


This project is an educational business analytics case study. The findings describe patterns and associations within the dataset and should not be interpreted as proof of causal relationships.
