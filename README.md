<h1>Optimizing Insurance Renewal Campaigns with Customer Insights</h1>
<p><strong>A marketing analytics project focused on customer targeting, retention, and campaign effectiveness.</strong></p>

<p><em>
This project focuses on improving insurance policy renewal campaigns by helping marketing and retention teams identify which customers are most likely to respond.  
Using customer demographics, household composition, purchase behavior, and past campaign activity, I built a data-driven prioritization system that groups customers into High, Medium, and Low renewal potential.  
The solution allows the business to focus outreach on customers who are most likely to renew, reducing wasted communication and improving campaign effectiveness.  
Results were validated using actual campaign response data and presented through interactive dashboards for the marketing team.
</em></p>

<h2>Business Problem</h2>

<p>
OptiSecure Insurance operates in a highly competitive market where policy renewals are critical to long-term revenue and customer lifetime value. Retaining existing customers is significantly more cost-effective than acquiring new ones, making renewal campaigns a key focus for the business.
</p>

<p>
Despite running regular renewal campaigns across digital channels, the company experienced stagnant renewal response rates, particularly among digitally acquired customers. Campaigns were largely broad-based, with similar messages sent to all customers regardless of their likelihood to renew.
</p>

<p>
As a result, a substantial portion of marketing spend was directed toward customers who were unlikely to respond, leading to inefficient use of advertising budgets, increased campaign costs, and avoidable marketing waste.
</p>

<p>
The marketing and retention teams lacked a clear, data-driven way to identify which customers were most likely to renew. Without customer-level prioritization, the business struggled to focus outreach effectively, optimize marketing spend, and improve overall renewal campaign performance.
</p>

<h2>Analysis Objectives</h2>

<p>
The objective of this analysis was to support more effective insurance renewal campaigns by introducing structure and clarity into how customers are targeted. Specifically, the project aimed to:
</p>

<ol>
  <li>
    Identify customers with a higher likelihood of renewing their policies by analyzing customer demographics, household characteristics, purchase behavior, and past campaign engagement.
  </li>
  <li>
    Enable targeted campaign prioritization by grouping customers into High, Medium, and Low renewal potential segments, allowing marketing and retention teams to focus outreach where it is most likely to be effective.
  </li>
  <li>
    Reduce inefficient marketing spend by limiting outreach to customers with low renewal likelihood and reallocating effort toward higher-impact segments.
  </li>
  <li>
    Provide clear visibility into customer segments and campaign performance to support informed decision-making by marketing and retention stakeholders.
  </li>
</ol>

<h2>Data Overview</h2>

<p>
The analysis was based on customer-level data provided by OptiSecure Insurance, covering demographic attributes, purchase behavior, and historical campaign engagement. The data represents customers acquired through digital and non-digital channels and was structured across multiple related tables.
</p>

<p><strong>Key data components included:</strong></p>

<ol>
  <li>
    <strong>Customer profile data</strong> — age, income band, marital status, household composition, and registration date. This provided demographic and household context that may influence renewal decisions.
  </li>
  <li>
    <strong>Purchase and engagement behavior</strong> — spending patterns across product categories and purchase channels. These variables helped capture customer value, activity level, and interaction with the company.
  </li>
  <li>
    <strong>Campaign response history</strong> — whether customers responded to previous marketing campaigns. This served as a key engagement signal for informing renewal likelihood.
  </li>
</ol>

<p>
To support the analysis, the datasets were cleaned, merged, and transformed into a single customer-level table. Additional fields such as customer tenure, total spend, and aggregated campaign responses were derived to better represent customer behavior over time.
</p>





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
## How Renewal Performance Was Measured

Renewal performance was measured using a small set of indicators designed to support clear targeting decisions and campaign evaluation.

A customer was counted as having **responded** if they accepted a renewal offer. This definition was applied consistently and used as the primary signal of renewal engagement.

Three measures were used to assess performance:

- **Response Rate:** Used to understand how effectively different customer groups engaged with renewal campaigns, based on the proportion of customers within each segment
   who responded.

- **Customer Score:** Used to rank individual customers based on observed behavior, including purchase activity, digital engagement, and past campaign participation. Higher
   scores indicated customers with stronger likelihood to respond to renewal communications.

- **Segment-Level Performance:** Used to compare response behavior across income bands and household types, enabling identification of segments that consistently showed
  higher or lower renewal engagement.

Together, these measures provided a clear and consistent basis for interpreting results and prioritizing renewal campaign targeting.

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



