# 🛒 Supermarket Sales Analytics Dashboard

## 📌 Project Overview
This project transforms raw supermarket transactional data into an interactive, executive-ready Excel dashboard. The objective of this analysis is to extract actionable business intelligence regarding revenue trends, customer demographics, product line profitability, and regional branch performance, enabling data-driven retail decisions.

## 📊 Dataset Link
https://www.kaggle.com/datasets/markmedhat/supermarket-sales

## 💡 Key Business Insights

Through interactive data modeling and visualization, several key strategic trends were identified:

*   **Customer Loyalty ROI:** Registered **Members** drive higher total profits ($7,820.26) compared to **Normal** customers ($7,559.16). Additionally, the customer base is evenly split (501 Members vs. 499 Non-Members), indicating a strong opportunity to convert standard shoppers into the loyalty program to boost the bottom line.
*   **Demographic Profit Drivers:** Female customer segments generate significantly higher total profits ($7,994.44) compared to male segments ($7,384.98), suggesting higher returns for female-targeted marketing campaigns.
*   **Product Line Champions:** **Food and beverages** is the highest-margin product category ($2,673.57 profit), while **Health and beauty** lags behind ($2,342.57). Interestingly, **Fashion accessories** achieved the highest average customer rating (7.1/10).
*   **Regional & Payment Consistency:** Market share is exceptionally stable across all physical branches, splitting almost perfectly at 33% (Mandalay), 34% (Naypyitaw), and 33% (Yangon). Furthermore, payment preferences are evenly distributed across E-wallets (35%), Cash (34%), and Credit Cards (31%), indicating a well-rounded transaction infrastructure.
*   **Temporal Trends:** A distinct revenue and profit slump occurred in February ($4,629.51 profit), followed by a strong recovery in March ($5,212.19 profit), requiring further investigation into seasonal factors or operational days.

## 🔍 Data Audit & Margin Verification
During the initial exploratory data analysis of this Kaggle dataset, a logical anomaly in the synthetic data generation was identified: the standard `Tax 5%` column mathematically mirrored the `Gross Income` column. 

To ensure corporate financial accuracy, I restructured the KPI metrics to reflect real-world retail accounting. The raw transaction data was reconciled to establish a verified **4.76% Gross Profit Margin** ($15,379.42 total profit on $322,966.80 revenue). This correction provides a realistic, unified metric for executive review.

## 🛠️ Tools & Techniques Used
*   **Microsoft Excel**
*   **Data Modeling:** Power Query / Pivot Tables
*   **Interactive Elements:** Slicers (Branch, Gender, Months) tied to multiple Pivot Charts for dynamic filtering
*   **Calculated Fields:** Custom KPI generation (Revenue, Margin %, Customer Volume)
*   **Data Visualization:** Clustered Bar Charts, Line Graphs, Donut Charts, Pie Charts, and Custom KPI Cards

