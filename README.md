# Customer Segmentation using RFM Model

## Author

**Mahek Shaikh**

---

# Customer Segmentation using RFM Model

## Project Overview

Customer segmentation is one of the most important techniques used by businesses to understand customer behavior and improve marketing effectiveness. This project applies the **RFM (Recency, Frequency, Monetary)** model to classify customers into meaningful segments based on their purchasing patterns.

The objective of this project is to identify high-value customers, loyal customers, potential loyalists, at-risk customers, and lost customers. By leveraging customer transaction data, the project helps organizations improve customer retention, increase revenue, and design targeted marketing campaigns.

This project demonstrates practical applications of **Business Analytics, CRM Analytics, Customer Intelligence, Marketing Analytics, and Business Intelligence** using Python and Power BI.

---

## Business Problem

Businesses often struggle to identify:

* Which customers generate the highest revenue
* Which customers are most loyal
* Which customers are likely to stop purchasing
* Which customers should receive personalized offers
* Which customer groups contribute most to overall business performance

Without proper customer segmentation, marketing budgets are often wasted on generic campaigns that fail to maximize customer engagement and retention.

This project solves these challenges using the RFM customer segmentation framework.

---

## Project Objectives

* Analyze customer purchasing behavior
* Calculate Recency, Frequency, and Monetary metrics
* Create customer segments based on RFM scores
* Identify valuable and at-risk customers
* Measure revenue contribution by segment
* Support customer retention strategies
* Provide actionable business recommendations
* Build an interactive Power BI dashboard

---

## RFM Framework

### Recency (R)

Measures how recently a customer made a purchase.

Higher recency scores indicate customers who purchased recently and are more likely to engage again.

### Frequency (F)

Measures how often a customer makes purchases.

Higher frequency scores indicate loyal and active customers.

### Monetary (M)

Measures total customer spending.

Higher monetary scores indicate customers contributing significant revenue.

---

## Dataset Description

The dataset contains customer-level information including:

* Customer ID
* Customer Name
* Region
* Gender
* Total Orders
* Total Purchase Amount
* Average Order Value
* Last Purchase Date
* Product Category
* Recency
* Frequency
* Monetary
* RFM Score
* Customer Segment

---

## Technologies Used

### Python

* Pandas
* NumPy
* Matplotlib
* Seaborn

### Power BI

* Data Modeling
* DAX Measures
* KPI Cards
* Interactive Visualizations
* Dashboard Design

### Tools

* Google Colab
* Microsoft Power BI
* GitHub

---

## Analysis Performed

### Data Preparation

* Generated customer transaction dataset
* Cleaned and validated records
* Prepared customer-level analytics table

### RFM Calculation

* Calculated Recency
* Calculated Frequency
* Calculated Monetary Value

### Customer Scoring

Assigned scores from 1–5 for:

* Recency
* Frequency
* Monetary

Created a combined RFM Score for customer ranking.

### Customer Segmentation

Customers were categorized into:

* Champions
* Loyal Customers
* Potential Loyalists
* At-Risk Customers
* Lost Customers

---

## Power BI Dashboard Features

### KPI Cards

* Total Customers
* Total Revenue
* Average Order Value
* Champion Customers
* Loyalty Percentage

### Visualizations

* Customer Segment Distribution
* Revenue by Customer Segment
* Revenue by Region
* Revenue by Product Category
* Region-wise Customer Segmentation
* Top 10 High-Value Customers

### Interactive Filters

* Region
* Gender
* Customer Segment
* Product Category

---

## Key Business Insights

### Revenue Drivers

Champion and Loyal Customers contribute the largest share of overall revenue.

### Customer Retention

At-Risk customers represent opportunities for retention campaigns and personalized engagement strategies.

### Marketing Opportunities

Potential Loyalists can be converted into long-term loyal customers through targeted promotions.

### Customer Value Analysis

A small percentage of customers generate a disproportionately large share of total revenue.

### Regional Performance

Customer revenue distribution varies across regions, enabling region-specific marketing strategies.

---

## Business Recommendations

### For Champion Customers

* Offer VIP rewards
* Provide exclusive discounts
* Introduce premium loyalty programs

### For Loyal Customers

* Increase engagement through loyalty benefits
* Offer early access to promotions

### For Potential Loyalists

* Use personalized marketing campaigns
* Encourage repeat purchases

### For At-Risk Customers

* Launch re-engagement campaigns
* Provide special retention offers

### For Lost Customers

* Run win-back campaigns
* Promote new products and services

---

## Dashboard Outcome

The dashboard provides a complete view of customer behavior, revenue contribution, customer loyalty, and retention opportunities.

It enables businesses to make data-driven decisions that improve customer engagement, increase retention rates, and maximize customer lifetime value.

---

## Project Skills Demonstrated

* Business Analysis
* Customer Analytics
* CRM Analytics
* Marketing Analytics
* Data Analysis
* Customer Segmentation
* KPI Development
* Dashboard Design
* Data Visualization
* Power BI
* DAX
* Python Programming
* Business Intelligence
* Insight Generation


---

## Conclusion

The Customer Segmentation using RFM Model project demonstrates how businesses can transform customer transaction data into actionable insights. By identifying customer value and engagement levels, organizations can improve retention, increase profitability, and design highly targeted marketing strategies.

This project showcases practical skills used by Business Analysts, CRM Analysts, Marketing Analysts, Customer Insight Analysts, and Business Intelligence professionals in real-world business environments.

---

## Repository Structure

```text
Customer-Segmentation-RFM-Model/
│
├── Dataset/
│   ├── Raw_Customer_Dataset.csv
│   └── Final_RFM_Dataset.csv
│
├── Notebook/
│   └── Customer_Segmentation_RFM_Analysis.ipynb
│
├── Dashboard/
│   ├── PowerBI_Dashboard.pbix
│   └── Dashboard_Screenshot.png
│
├── Visualizations/
│   ├── Customer_Segment_Distribution.png
│   ├── Revenue_By_Segment.png
│   ├── Region_Revenue.png
│   ├── Category_Analysis.png
│   ├── RFM_Heatmap.png
│   └── High_Value_Customers.png
│
├── Reports/
│   └── KPI_Report.csv
│
└── README.md
```
