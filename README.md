# Myntra Return Rate Root Cause Analysis Dashboard

## Project Overview

During Myntra's Big Fashion Festival (BFF) sale, overall sales performance appeared strong. However, management identified a significant increase in product returns, impacting revenue and profitability.

The objective of this project was to analyze return patterns, identify root causes behind high return volumes, and provide actionable business insights using Databricks SQL and Dashboarding.

---

## Business Problem

Although the sale generated substantial order volume, the CFO observed that customer return rates had increased significantly.

The analysis focused on answering the following business questions:

1. How much revenue was retained versus lost due to returns?
2. Which product categories generated the highest returns?
3. Which customer segments (City Tiers) contributed most to returns?
4. Which Brand-Category combinations were driving the return problem?
5. Were returns concentrated on specific days or consistent throughout the sale period?

---

## Dataset Information

The analysis was performed using three datasets:

### Orders Fact Table

* Order information
* Order status (Delivered / Returned / Cancelled)
* Final sale price

### Products Master Table

* Product category
* Brand details

### Users Master Table

* Customer demographics
* City Tier information

---

## Tools & Technologies

* Databricks SQL
* Databricks Dashboards
* SQL Warehouses
* Data Visualization
* Aggregations & Joins
* Business Analytics

---

# Dashboard Overview

<img width="1437" height="567" alt="image" src="https://github.com/user-attachments/assets/fe0e5870-5480-4230-8f0e-d8be2b045865" />


---

# Key Findings & Business Insights

## 1. Revenue Impact Analysis

### Findings

* Approximately 79.6% of revenue came from successfully delivered orders.
* Around 20.4% of revenue was associated with returned orders.

### Business Implications

A return-related revenue loss of over 20% is substantial for any large-scale sales event. While demand generation was successful, profitability was negatively affected by returns. Reducing return rates would directly improve realized revenue without requiring additional customer acquisition spending.

---

## 2. Returns by Product Category

### Findings

* Ethnic Wear recorded the highest number of returns.
* Accessories ranked second.
* Footwear and Western Wear showed comparatively lower return volumes.

### Business Implications

The return problem is not evenly distributed across product categories. Ethnic Wear appears to be the primary contributor to return volume and should be prioritized for investigation. Potential causes include sizing inconsistencies, quality concerns, inaccurate product descriptions, or customer expectation mismatches.

---

## 3. Orders & Returns by City Tier

### Findings

* Tier 2 cities generated the highest order volume.
* Tier 2 cities also recorded the highest number of returns.
* Tier 3 cities contributed the lowest order and return counts.

### Business Implications

The concentration of returns in Tier 2 markets suggests that customer behavior, product suitability, logistics performance, or fulfillment quality may differ across regions. Targeted operational improvements in Tier 2 cities could significantly reduce overall return volume.

---

## 4. Root Cause Analysis: Brand-Category Return Drivers

### Findings

* Puma recorded the highest overall return volume.
* Roadster and H&M also contributed significantly to returns.
* Returns were concentrated within specific brand-category combinations rather than being evenly distributed.

### Business Implications

The return issue appears to be driven by a limited number of high-return brand-category combinations. These products should be prioritized for quality reviews, sizing audits, product description validation, and customer feedback analysis. Addressing these specific combinations would likely produce a larger impact than broad platform-wide interventions.

---

## 5. Daily Return Trend Analysis

### Findings

* Daily return counts remained relatively stable throughout the 15-day sale period.
* No extreme single-day spike was observed.
* Return volume fluctuated within a narrow range.

### Business Implications

The return problem was not caused by a one-time operational incident. Instead, returns occurred consistently throughout the campaign, suggesting a systemic issue related to products, customer expectations, or purchasing behavior. Long-term corrective measures would therefore be more effective than investigating isolated events.

---

# Overall Conclusion

The analysis indicates that the return challenge was primarily driven by:

* High return concentration within the Ethnic Wear category.
* Specific high-return brands such as Puma, Roadster, and H&M.
* Elevated return activity from Tier 2 cities.
* A sustained return pattern throughout the sales campaign.

Rather than a single operational failure, the findings suggest a broader issue involving product fit, category-specific customer expectations, and selected brand-category combinations.

Addressing these areas could significantly reduce return rates, improve customer satisfaction, and increase realized revenue during future sales events.

---

## Skills Demonstrated

* SQL Data Analysis
* Data Aggregation & Filtering
* Multi-Table Joins
* Business Intelligence
* Dashboard Development
* Data Visualization
* Root Cause Analysis
* Databricks Lakehouse Analytics
