# Data-Driven Retention Strategy to Secure Revenue
### An End-to-End Customer Churn Analysis in the Telecommunications Industry

![dashboard_preview](https://github.com/user-attachments/assets/d809e521-608d-477a-abd4-4f9c57e0b9b9)


**➡️ [Access the Interactive Looker Studio Dashboard Here](https://lookerstudio.google.com/reporting/43f8a232-614e-4e95-ad52-7538605c28de)**

---

## 📝 Project Overview

This repository contains an end-to-end data analysis project focused on identifying the key drivers of customer churn for a fictional telecommunications company. The project translates raw customer data into actionable business insights, culminating in a strategic retention plan and an interactive dashboard designed to help stakeholders make data-informed decisions, reduce revenue loss, and improve customer loyalty.

---

## 🎯 Business Problem & Objectives

In a saturated telecommunications market, customer retention is more cost-effective than acquisition. This project addresses the critical business challenge of customer churn by answering four key questions:

1.  **Scale of the Problem:** What is the overall churn rate and what is its financial impact on Monthly Recurring Revenue (MRR)?
2.  **Root Cause Analysis:** What are the primary factors and customer behaviors that correlate with a high probability of churn?
3.  **Financial Opportunity:** What is the potential revenue that can be saved with a targeted retention program?
4.  **Actionable Priority:** Which customer segments should be prioritized to maximize the Return on Investment (ROI) of retention efforts?

---

## 🛠️ Methodology & Tools

This project follows the **CRISP-DM (Cross-Industry Standard Process for Data Mining)** framework to ensure a structured and systematic approach from business understanding to deployment.

-   **Data Preparation & Analysis:** `Python` (`Pandas`, `NumPy`, `Matplotlib`, `Seaborn`)
-   **Interactive Dashboard:** `Google Looker Studio`
-   **Version Control:** `Git` & `GitHub`

---

## 🚀 Key Insights & Strategic Recommendations

The analysis uncovered several critical insights that form the basis of our strategic recommendations:

#### **Insight 1: Month-to-Month Contracts are the Primary Churn Driver**
Customers on flexible **Month-to-Month (M2M) contracts** have a churn rate of **42.7%**, which is over four times higher than customers on annual contracts. This segment alone accounts for **88.6% of all churned customers**.

-   **Recommendation:** Launch a proactive marketing campaign to migrate high-risk M2M customers to one or two-year contracts by offering financial incentives (e.g., 10-15% discount) and value-added services (e.g., 3 months of free Online Security).

#### **Insight 2: Service Ecosystem Integration Drives Loyalty**
Customers without key support services like `TechSupport` and `OnlineSecurity` are nearly **three times more likely to churn**. The churn rate consistently decreases as the number of additional services a customer adopts increases.

-   **Recommendation:** Strengthen cross-selling and bundling strategies. Introduce a "Welcome Package" for new M2M customers that includes these crucial support services at an attractive price point and offer free trials to encourage adoption.

#### **Insight 3: High-Value, High-Risk Segment Represents the Biggest Opportunity**
A specific segment of customers—defined as active, M2M subscribers with low tenure (≤12 months) and above-average monthly charges—poses a disproportionate risk to revenue.

-   **Recommendation:** Form a dedicated **VIP Retention Team** to personally engage with the customers identified in this segment. Empower this team with exclusive, "off-script" offers (e.g., personalized discounts, free service upgrades) to maximize retention success and achieve the highest ROI. The dashboard provides a dynamic, prioritized list for this team to action daily.

---

## 📂 Repository Structure

The repository is organized as follows:

```
.
├── data/              # Contains the raw and cleaned datasets (.csv)
├── deliverables/      # Contains the final project outputs (report, presentation, images)
├── notebooks/         # Contains the Python notebook for the entire analysis (.ipynb)
├── .gitignore         # Specifies files for Git to ignore
└── README.md          # Project overview and documentation (You are here)
```
```

---
