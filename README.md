#  End-to-End Data Engineering & BI Pipeline for Olist E-Commerce

![DEPI Banner](https://img.shields.io/badge/DEPI-Digital%20Egypt%20Pioneers%20Initiative-1e3a8a?style=for-the-badge)
![Track](https://img.shields.io/badge/Track-Data%20Analysis-06b6d4?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-10b981?style=for-the-badge)

An end-to-end data engineering and business intelligence project designed to analyze **Olist** (Brazil's largest e-commerce marketplace)
This project processes raw e-commerce transaction data, builds a normalized relational database, performs advanced **RFM Customer Segmentation**, and delivers prescriptive dashboards in **Power BI** to solve retention and logistical bottlenecks

---

##  Executive Summary & Key Discoveries

By analyzing 96k+ unique customers and millions of transactional records, we uncovered three major strategic business issues:
1. **Customer Retention Crisis:** A dangerously low **3.12% repeat purchase rate**, indicating high Customer Acquisition Costs (CAC) with minimal customer lifetime value
2. **Logistical Bottlenecks:** Average delivery times exceed **15 days** to remote states (e.g., Rio de Janeiro), with freight costs exceeding $40+ per item in Northern regions
3. **Quality Control Gaps:** The top-selling category (`bed_bath_table`) suffers from a low average review score (**3.97/5**), threatening overall customer trust
---

##  Technical Architecture & Pipeline

The project was executed through a 3-tier pipeline architecture
1. **Data Ingestion & Cleaning (Python/Pandas):** Handled missing values, standardized formats, and calculated Recency, Frequency, and Monetary (RFM) metrics
2. **Database Engineering (SQL Server):** Designed a 3rd Normal Form (3NF) relational database, enforcing strict Primary/Foreign Key constraints to ensure data integrity
3. **Data Modeling & BI (Power BI):** Constructed a clean **Star Schema**, wrote complex DAX measures, and eliminated bi-directional relationship ambiguity to power 4 executive dashboards

---

##  Tech Stack & Tools

* **Languages:** Python 3.x, SQL (T-SQL), DAX
* **Libraries:** Pandas, NumPy
* **Database:** Microsoft SQL Server / SSMS
* **Visualization:** Power BI Desktop
* **Version Control:** Git & GitHub

---

##  Key Dashboards & Visuals

The project delivers 4 comprehensive dashboards covering
*  **Executive Overview:** High-level KPIs, total revenue, and order volume metrics
*  **Customer Insights & RFM Segmentation:** Segmenting users into *Loyal Customers*, *Potential Loyalists*, and *At-Risk* buckets
*  **Logistics & Delivery Operations:** Freight cost distribution and delivery time variance across Brazilian states
*  **Product & Category Performance:** Analysis of best-selling items vs. customer review scores

---
## 📊 Dashboards Overview

<img width="1593" height="975" alt="Screenshot 2026-06-19 010606" src="https://github.com/user-attachments/assets/207ab311-927e-4f7a-a815-bca9dabf6487" />

<img width="1584" height="958" alt="Screenshot 2026-06-19 010657" src="https://github.com/user-attachments/assets/55d7cf5b-54cf-4ca2-96c8-cbf1eb349829" />
<img width="1595" height="965" alt="Screenshot 2026-06-19 010719" src="https://github.com/user-attachments/assets/734c20f5-3c30-4949-9886-6ad54059f89d" />

<img width="1591" height="973" alt="Screenshot 2026-06-19 010737" src="https://github.com/user-attachments/assets/4a3c0928-32cc-47b4-b94b-2050fec29d72" />


##  Prescriptive Recommendations

* **Launch "Olist Points" Loyalty Program:** Re-engage the 96.88% of one-time buyers by incentivizing repeat purchases
* **Regional Freight Optimization:** Partner with localized fulfillment centers in high-friction states to drop delivery times below 7 days
* **Seller Quality Audits:** Set up automated rating alerts for high-volume vendors with review scores under 3.8
---

##  Project Team (Group D)

* **Ahmed Abdelfattah** - Data Analyst / BI Engineer
* **Supervisor:** Eng. Abdelrahman Ashour
* Special thanks to the **Digital Egypt Pioneers Initiative (DEPI)** team.
