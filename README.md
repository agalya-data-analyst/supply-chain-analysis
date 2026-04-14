# DataCo Smart Supply Chain Analysis 🚛📊

## 📌 Project Overview
This project provides a comprehensive data analysis of a global supply chain network using **Excel** and **Power BI**. The primary focus is on identifying logistical bottlenecks, quantifying late delivery risks, and uncovering financial leakage points to optimize overall supply chain health.

## 🎯 Project Objectives
* **Analyze Supply Chain Health:** Monitor Gross Sales ($36.78M) and Net Profit ($3.97M).
* **Quantify Late Delivery Risk:** Diagnose the factors behind the 55% failure rate.
* **Identify Financial Leakage:** Isolate "Loss Zones" where high discounts erode profit margins.
* **Evaluate Shipping Mode Efficiency:** Investigate why 'First Class' shipping has a 1.8x higher risk of delay.
* **AI-Driven Root Cause Analysis:** Utilize Key Influencers and Decomposition Trees to find hidden drivers of delays.

## 🛠️ Tech Stack & Tools
* **Microsoft Excel:** Data auditing, missing value imputation, and reference table creation.
* **Power BI & Power Query:** Data transformation, ETL processes, and Star Schema modeling.
* **DAX (Data Analysis Expressions):** Advanced measures for time intelligence and KPI tracking.

## 📂 Data Transformation (ETL)
* **Standardization:** Translated geographic names from Spanish to English for global reporting.
* **Feature Engineering:** Calculated "Delivery Delay" and "Arrival Logic" using DATEDIFF and Date functions.
* **Data Modeling:** Implemented a **Star Schema** connecting a central Fact Table (`Order_Transactions`) to several Dimension Tables (`Product`, `Customer`, `Location`, `Department`, and `Calendar`).

## 💡 Key Insights
1. **Operational Lag:** The actual average delivery time is **7 days**, exceeding the target of **4 days** by 75%.
2. **The Shipping Paradox:** AI insights revealed that **'First Class'** shipping, meant for speed, actually increases late delivery probability by **1.8x**.
3. **Regional Hotspots:** **Western Europe and Central America** were identified as "High-Risk" zones where high sales volume coincides with peak delay rates.
4. **Profit Protection:** The **Consumer segment** drives 50% of revenue, but high-value Technology orders are suffering from profit erosion due to shipping variances.
![Overview](Supplychain%20Overview.png)
![Strategic](Strategic%20AI%20Insights.png)
![Operational](Operational%20dashboard.png)
## 🚀 Conclusion & Recommendations
* **Logistics Optimization:** Re-evaluate carrier contracts for 'First Class' routes in high-risk regions.
* **Real-Time Monitoring:** Transition from manual reporting to this automated dashboard to close the "Visibility Gap."
* **Proactive Alerts:** Implement an alert system for orders falling into "High-Risk" categories identified by the AI influencers.

---
**Author:** [Agalya J]  
**Tools Used:** Excel, Power BI, DAX, Power Query
