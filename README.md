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
## Key Metrics & Evaluation Framework

Renewal campaign performance was assessed using a consistent set of metrics designed to support practical targeting and decision-making.

A **campaign response** was defined as a customer accepting a renewal offer. This definition was applied consistently across the analysis and used as the primary measure of renewal engagement.

Customer performance was evaluated at both the individual and segment level:

- **Response Rate**  
  Used to measure how effectively different customer groups engaged with renewal campaigns.

- **Customer Score**  
  Used to rank customers based on observed engagement signals, including purchase behavior, digital interaction, and past campaign participation. Customers with higher scores were prioritized for renewal outreach.

- **Segment-Level Performance**  
  Used to compare performance across income bands and household types, identifying segments that consistently showed stronger renewal behavior.

These metrics provided a practical framework for identifying high-value customer segments and informing renewal targeting decisions used throughout this engagement.

---
<table width="100%">
  <tr>
    <td width="50%" align="center">
      <img src="./campaign_response_income.png" width="95%">
      <br><strong>Campaign Response by Income Band in %</strong>
    </td>
    <td width="50%" align="center">
      <img src="./campaign_response_household.png" width="95%">
      <br><strong>Campaign Response by Household Type in %</strong>
    </td>
  </tr>
</table>



