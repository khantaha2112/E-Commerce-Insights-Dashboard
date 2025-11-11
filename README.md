# 🛒 Vishal E-commerce Sales Dashboard — Data Analysis Project

_Developed an interactive Power BI dashboard to analyze the sales, profit, quantity, and customer behavior data for Vishal E-commerce Store, uncovering insights into state-wise performance, product categories, and payment preferences to support strategic decision-making._

  ![Image](https://github.com/user-attachments/assets/f771dec2-aa66-48b4-be37-b8de32ec71c8) <img width="1796" height="724" alt="Image" src="https://github.com/user-attachments/assets/461b8b77-3a3f-49bd-aac1-2b419480566e" />

---

## 📌 Table of Contents
- <a href="#overview">Overview</a>
- <a href="#business-problem">Business Problem</a>
- <a href="#dataset">Dataset</a>
- <a href="#tKey Analytical Areas">Tools & Technologies</a>
- <a href="#Dataset">Project Structure</a>
- <a href="#Tools & Technologies">Data Cleaning & Preparation</a>
- <a href="#Project Structure">Key Analytical Areas</a>
- <a href="#Core Metrics & Status">Research Questions & Key Findings</a>
- <a href="#dashboard">Dashboard</a>
- <a href="#Final Recommendations">Data Flow & Linkage</a>
- <a href="#final-recommendations">Final Recommendations</a>

<h2><a class="anchor" id="overview"></a>Overview</h2>

This project focuses on analyzing **Vishal E-commerce Store’s** transactional data to understand sales performance, profitability, and customer purchasing behavior across different states, categories, and payment modes. The Power BI dashboard presents a consolidated view of all **key performance indicators (KPIs) and enables drill-down analysis to identify trends, profitable segments, and improvement areas**.

---
<h2><a class="anchor" id="🛑 The Core Business Problem"></a>Business Problem</h2>

The store faced challenges in understanding which states, products, and customer segments contribute most to revenue and profit. Without clear visibility into these patterns, it was difficult to:
- Identify high-performing regions and categories.
- Understand the profitability across sub-categories.
- Optimize inventory and marketing strategies.
- Evaluate the effectiveness of different payment modes.
---

<h2><a class="anchor" id="dataset"></a>Dataset Used</h2>

- <a href="https://drive.google.com/file/d/1NYLYydSPw8ALOWH9B6mWkpXb57dQtV_O/view?usp=sharing">Ola Booking Sep25 Data</a>
---
<h2><a class="anchor" id="🔎Key Analytical Areas Addressed by the OLA Project"></a>Key Analytical Areas </h2>

- Sales & Profit Analysis: Identify total revenue, profit, and quantity trends.
- State-wise Performance: Evaluate which states contribute the most to sales and profit.
- Category & Sub-Category Insights: Assess product category contributions and profitability.
- Customer Insights: Highlight top customers driving sales volume.
- Payment Mode Analysis: Understand the preferred payment modes among customers.
- Seasonal Trends: Monthly profit trends to spot seasonal spikes and dips.
---

<h2><a class="anchor" id="tools--technologies"></a>Tools & Technologies</h2>

- **Google Sheet** -  for data cleaning and preprocessing
- **Power BI** -  ( Creation of the final interactive dashboard and Key Performance Indicator (KPI) tracking )
- **GitHub** -  ( Repository for storing all project files, including SQL scripts and the Power BI file )

---
<h2><a class="anchor" id="project-structure"></a>Project Structure</h2>

```
OLA-Rider-Retention-Strategy/
├── README.md                                 (The main project documentation file)
├── Ola_Analytics_Dashboard.pbix              (The final, interactive Power BI file)
├── Ola_Data_Queries.sql                      (Contains all SQL transformation, aggregation, and View creation scripts)
├── Source_Data/
│   └── OLA_Booking_Data.csv                  (The raw 100,000 row dataset)
└── Visualizations/                           (Snapshots of key dashboard sections)
    ├── Ola_Dashboards_Full_View.jpg          
    ├── Ola_Performance_Summary.png           (Visual for Step 1: Overall Performance)
    ├── Ola_Vehicle_Metrics.png               (Visual for Step 2: Vehicle Type Breakdown)
    ├── Ola_Revenue_Trends.png                (Visual for Step 3: Revenue Insights)
    ├── Ola_Cancellations_Analysis.png        (Visual for Step 4: Cancellation Analysis)
    └── Ola_Ratings_Overview.png              (Visual for Step 5: Ratings Overview)
```
<h2><a class="anchor" id="exploratory-data-analysis-eda"></a>📈 Core Metrics & Findings</h2>

**🎯 Core Volume & Value :**
- Total Sales Amount: 438K
- Total Profit: 37K
- Total Quantity Sold: 5615

**❌ Cancellation Breakdown :**
- **Total Cancellations:** $\text{73,076}$ (Total count of rides canceled, both driver and customer).
- **Driver-Cancelled Rides:** $\text{45,416}$ (Represents $\text{62.15\%}$ of all cancellations, making it the primary cause of lost revenue).
- **Customer-Cancelled Rides:** $\text{22,530}$ (The count of rides canceled by the customer).

**⭐ Top Insights:**
- Maharashtra contributed the highest sales, followed by Madhya Pradesh.
- Clothing dominates with 63% of total quantity sold, while Furniture and Electronics contribute 17% and 21% respectively.
- Cash on Delivery (44%) is the most preferred payment method.
- Highest profit months were January and December, indicating strong seasonal demand.

- **Overall Customer Rating:** $\text{4.01}$
---
<h2><a class="anchor" id="dashboard"></a>Dashboard</h2>

**📊Power BI Dashboard shows:**
- KPIs for Total Sales, Profit, Quantity, and AOV.
- Bar charts for State-wise and Customer-wise performance.
- Donut charts for Category and Payment Mode breakdowns.
- Line/Bar visual for Monthly Profit Trends.
- Comparative chart of Profit by Sub-Category.

- **Incentivize Drivers** in high-cancellation zones to improve availability and reduce $\text{Driver-Cancelled}$ rides.
- **Implement Dynamic Pricing** strategies during peak demand periods (weekends, rush hours) to maximize revenue and match supply.
- **Enhance App Communication** to provide customers with clear and immediate driver status updates to reduce $\text{Customer-Cancelled}$ rides.
- **Develop a Driver Quality Program** to address low $\text{Customer Ratings}$ and target specific feedback (e.g., professionalism, vehicle cleanliness).
- **Target Top-Spending Customers** with loyalty rewards and exclusive offers to improve overall rider retention.

---


