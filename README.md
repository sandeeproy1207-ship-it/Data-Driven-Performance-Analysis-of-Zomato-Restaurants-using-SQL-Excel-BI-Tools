# 📊 Data-Driven Performance Analysis of Zomato Restaurants using SQL, Excel & Power BI

---

## 🏁 Executive Summary
This project presents an end-to-end data analysis of the **Zomato restaurant dataset** to extract key insights about restaurant performance, pricing strategy, customer preferences, and operational trends.  
Using **SQL**, **Excel**, and **Power BI**, the analysis translates raw restaurant data into meaningful business intelligence that can guide data-driven decisions for restaurant aggregators and food delivery businesses.

---

## 🎯 Project Overview & Objectives

This project is a comprehensive analysis of the Zomato restaurant dataset, covering 995 restaurants across 39 cities. The primary goal is to identify key drivers of restaurant performance, customer satisfaction, and market trends.

The key objectives were:
* To analyze the distribution and count of restaurants by city and country.  
* To identify the most popular and competitive cuisines.  
* To understand the impact of services like **Online Delivery** and **Table Booking** on the market.  
* To determine the relationship between restaurant type (e.g., Cafe, Pub) and customer ratings.  
* To provide actionable, data-driven recommendations for a new restaurant venture.

---

## ⚙️ Methodology

1. **Data Preparation & Cleaning (Excel & SQL)**
  - Used Excel to perform data validation, handle missing entries, and remove duplicates.  
  - Applied SQL queries (`SELECT`, `GROUP BY`, `HAVING`, `WINDOW FUNCTIONS`) for data extraction and aggregation.  
  - Built country and calendar reference tables for temporal and geographic analysis.

2. **Data Modeling (SQL & Power BI)**
  - Created relationships between fact and dimension tables (Country, City, Calendar).  
  - Calculated new attributes: `financial_month`, `financial_quarter`, `year_month`, and `weekday_name`.

3. **Visualization (Power BI)**
  - Designed interactive dashboards with KPIs such as total restaurants, average ratings, and delivery availability.  
  - Used slicers and filters for dynamic insights across regions and cuisines.  
  - Created drill-through functionality for granular city-wise and cuisine-wise performance.

4. **Analytical Insights (Excel & Power BI)**
  - Implemented advanced Excel formulas (`SUMIFS`, `COUNTIFS`, `INDEX-MATCH`, `DATEPART`).  
  - Used DAX in Power BI for calculating measures and trend analysis.  
  - Combined visual storytelling and analytical metrics to highlight performance gaps.

---

## 🧠 Skills Demonstrated

| Category | Tools / Skills Used |
|-----------|--------------------|
| **Data Cleaning & Preparation** | Excel (Advanced), SQL |
| **Analysis & Querying** | Window Functions, Aggregations, Joins |
| **Visualization** | Power BI |
| **Dashboarding & Insights** | DAX, Filters, Drill-through, KPIs |
| **Business Intelligence** | Trend Analysis, Correlation Mapping, Market Segmentation |

---

## 📈 Results & Insights

My analysis of the **995 restaurants** in the dataset revealed several key trends:

1. **Online Delivery is the Market Standard:** A significant majority of restaurants (**74%**) offer online delivery. This suggests it is a critical feature for customer accessibility and market competition.  
2. **Table Booking is a Niche Service:** In contrast, **87% of restaurants do not offer table booking**, indicating it is a specialized service for a small segment of the market (e.g., fine dining) and not a standard customer expectation.  
3. **Customer Satisfaction Varies by Restaurant Type:** When analyzing average ratings, **Pubs (3.7 avg)** and **Cafes (3.5 avg)** show higher customer satisfaction compared to **Quick Bites (3.3 avg)**.  
4. **Cuisine Market is Highly Saturated:** The **North Indian (448)** and **Chinese (295)** cuisines dominate the market, indicating intense competition.  
5. **Restaurant Openings:** The highest number of openings occurred during **Q1 (April–June)**, aligning with the fiscal planning cycle and seasonal market readiness.s  

### 🖼️ Dashboard Preview:
![Zomato Power BI Dashboard](b7fa84f0-1f2a-4a69-b45f-abfbf98c1919.png)

---

## 💡 Business Recommendations

Based *directly* on the insights above:

1.  **Strategic Cuisine & Niche Focus:** The "North Indian" and "Chinese" markets are critically oversaturated. **Therefore, I recommend** incentivizing new and existing partners to diversify their menus. Promotional efforts should focus on high-satisfaction, less-competitive niches like **"Cafes"** (3.5 avg rating) to fill a clear gap in the market.
2.  **Align Campaigns with Market Trends:** Restaurant openings peak in Q1 (April-June). **Therefore, I recommend** launching major marketing and partner-acquisition campaigns (e.g., "New Opening Spotlight," "Welcome Discounts") during Q1 to capitalize on this wave of new partners and capture early customer interest.
3.  **Prioritize What Customers Actually Use:** My insight shows 87% of the market ignores table booking, while 74% relies on online delivery. **Therefore, I recommend** all partnership and marketing efforts de-prioritize "table booking" and focus exclusively on what moves the needle: **optimizing the online delivery experience.**

---

## 🚀 Next Steps

- Integrate **real-time APIs** from Zomato or Swiggy for dynamic dashboard updates.  
- Automate **data refresh pipelines** in Power BI.  
- Extend analysis using **Python (Pandas, Seaborn, Plotly)** for predictive modeling.  
- Develop a **forecasting model** to predict restaurant ratings and customer churn.  
- Deploy the dashboard publicly using **Power BI Service**.

---

## 👨‍💻 Author
**Sandeep Roy**  
B.Tech, IIT Roorkee s 
📧 [sandeep_r@ce.iitr.ac.in](mailto:sandeep_r@ce.iitr.ac.in)  
🔗 [GitHub Portfolio](https://github.com/sandeeproy1207-ship-it)  
🔗 [LinkedIn](https://www.linkedin.com/in/sandeep--roy)
