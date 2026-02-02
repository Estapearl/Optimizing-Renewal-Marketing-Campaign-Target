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
    <strong>Customer profile data</strong>:age, income band, marital status, household composition, and registration date. This provided demographic and household context that may influence renewal decisions.
  </li>
  <li>
    <strong>Purchase and engagement behavior</strong>:spending patterns across product categories and purchase channels. These variables helped capture customer value, activity level, and interaction with the company.
  </li>
  <li>
    <strong>Campaign response history</strong>:whether customers responded to previous marketing campaigns. This served as a key engagement signal for informing renewal likelihood.
  </li>
</ol>

<p>
To support the analysis, the datasets were cleaned, merged, and transformed into a single customer-level table. Additional fields such as customer tenure, total spend, and aggregated campaign responses were derived to better represent customer behavior over time.
</p>

<h2>How Customers Were Evaluated</h2>

<p>
Customers were evaluated based on how likely they were to respond positively to a policy renewal campaign. The evaluation focused on observable customer behavior and characteristics, rather than assumptions or single metrics.
</p>

<p><strong>Each customer was assessed across four main dimensions:</strong></p>

<ol>
  <li>
    <strong>Engagement history</strong><br>
    Customers who had previously responded to marketing campaigns were treated as more likely to engage again. Past campaign responses were used as a strong signal of renewal interest.
  </li>
  <li>
    <strong>Customer value and activity</strong><br>
    Spending behavior and purchase activity were used to understand how actively customers interacted with the company. Customers with higher and more consistent spending were considered more invested in the relationship.
  </li>
  <li>
    <strong>Recency and relationship strength</strong><br>
    How recently a customer engaged with the company, along with how long they had been a customer, was used to reflect relationship strength and current relevance.
  </li>
  <li>
    <strong>Household and demographic context</strong><br>
    Household composition, age group, and income band were included to capture life-stage and financial factors that influence renewal decisions.
  </li>
</ol>

<p>
These factors were combined to assign each customer a relative renewal likelihood score. Customers were then grouped into <strong>High</strong>, <strong>Medium</strong>, and <strong>Low</strong> renewal potential categories to support clear, actionable targeting decisions.
</p>

<h2>Results &amp; Validation</h2>

<p>
After customers were grouped into High, Medium, and Low renewal potential, actual campaign response data was used to evaluate whether the prioritization approach aligned with real customer behavior.
</p>

<p>
Across the renewal campaign, <strong>667 customers responded</strong>, resulting in an overall response rate of approximately <strong>29.75%</strong>.
</p>

<p>
Customers identified as <strong>High Priority</strong> accounted for <strong>347 of the 667 total responses</strong>, meaning that <strong>more than half of all campaign responses</strong> came from this segment alone. Within the High Priority group, the response rate was <strong>62%</strong>, which is more than double the overall campaign average.
</p>

<p>
These results show that customers identified as High Priority responded far more often than other customers. This indicates that the evaluation approach correctly identified customers who were more likely to engage with the renewal campaign, allowing the business to focus outreach on the right customers and avoid unnecessary marketing spend.
</p>








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



