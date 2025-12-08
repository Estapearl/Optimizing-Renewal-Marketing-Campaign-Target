<div align="center">

# Optimizing Renewal Campaign Targeting Using Household and Purchase Behavior
## Domain: Marketing Analytics | Customer Retention | Campaign Optimization

</div>

---
## Executive Summary

OptiSecure Insurance Ltd., an insurance firm in the United Kingdom faced stagnant policy renewal rates especially among digitally acquired customers. Despite running repeated email and SMS campaigns, the company lacked clarity on which customers were most likely to renew, leading to inefficient targeting and increased marketing costs.

I developed a customer segmentation and renewal scoring framework that combined household demographics, purchase behavior, digital engagement, and past campaign responses to rank customers by renewal likelihood. This enabled the marketing team to focus outreach on high-potential customers while reducing unnecessary contact with low-response segments.

The final solution delivered a clean, analysis-ready dataset and interactive dashboards in Looker Studio, giving stakeholders clear visibility into customer segments, renewal readiness, and campaign prioritization.

---
## Business Problem & Project Objectives

### Business Problem
OptiSecure Insurance Ltd. was facing challenges with policy renewals. Despite running multiple campaigns, renewal rates were stagnant, especially among digitally acquired customers. The marketing team lacked clear insights into customer behavior, making it difficult to prioritize outreach and allocate budget effectively. This inefficiency not only increased marketing costs but also risked lower customer retention and revenue growth.

### Project Objectives
The project aimed to help the company:  
1. **Identify high-value customer segments** likely to renew their policies.  
2. **Improve targeting efficiency** by focusing marketing efforts where they would have the greatest impact.  
3. **Provide a foundation for data-driven campaigns** that could be scaled and refined over time.

---
## Data Overview

The analysis used a multi-sheet dataset provided by OptiSecure Insurance Ltd. It included three main sheets:

1. **Customer Profile** – demographic information such as age, household composition, income, and registration date.  
2. **Purchase Behavior** – spending across product categories (e.g., wine, meat, fruits) and purchase channels (web, catalog, store).  
3. **Campaign Performance** – customer responses to previous marketing campaigns (AcceptedCmp1–5, Response).  

> For privacy reasons, no real customer data is included.  
> 🔗 [View Sample Dataset](https://docs.google.com/spreadsheets/d/11Lkdclpz9Ci3eJsTVPPX6OgWQSaeYkwPKeizICnoGs0/edit?usp=sharing)

---
## Analytical Approach

To improve campaign targeting, a structured, data-driven approach was followed:

1. **Data Preparation** – Cleaned and merged customer, purchase, and campaign datasets into a single analysis-ready file. Derived key fields like age, tenure, family size, total spend, and cumulative campaign responses.  

2. **Segmentation** – Grouped customers based on household demographics (marital status, children at home) and purchase behavior patterns to identify meaningful segments.  

3. **Feature Normalization & Scoring** – Standardized numeric metrics (spend, recency, web/catalog purchases, campaign responses) to make them comparable. Developed a scoring model that ranks customers by likelihood to renew.  

4. **Prioritization** – Classified customers into High, Medium, and Low priority groups based on their scores, enabling focused outreach for maximum impact.  

5. **Visualization & Insights** – Built interactive dashboards in Looker Studio to provide stakeholders with clear visibility of customer segments, renewal likelihood, and campaign readiness.  

> This approach helped the marketing team focus efforts on high-potential customers, reduce wasted spend, and improve overall campaign efficiency.

---
<table width="100%">
  <tr>
    <td width="50%" align="left">
      <img src="Campaign%20response%20by%20income.png" width="95%">
    </td>

    <td width="50%" align="right">
      <img src="Campaign%20response%20by%20household%20type.png" width="95%">
    </td>
  </tr>
</table>


