# Coffee Shop Sales & Performance Analysis (Excel-Driven)

## 📌 Business Context & Executive Summary
This project provides an end-to-end data analysis solution for a Coffee Shop using **Microsoft Excel** to evaluate its sales performance, optimize operations, and drive revenue growth. By analyzing transaction history, this interactive Excel dashboard uncovers critical insights regarding peak business hours, customer purchasing behavior, and payment preferences.

---

## 🛠️ Data Methodology & Advanced Excel Techniques
* **Power Query (ETL):** Used for Data Extraction, Cleaning, and Transformation. This included handling missing values, standardizing dates, and extracting time components (Hours and Days) to enable time-series analysis.
* **Data Modeling (Power Pivot):** Structured the dataset into a **Star Schema** within Excel's Data Model. Connected the centralized sales Fact Table to Dimension Tables (`Dim_Products`, `Dim_Date`, `Dim_Time`) to enable optimized performance and seamless filtering.
* **Advanced Pivot Tables & DAX/Measures:** Developed customized Key Performance Indicators (KPIs) and interactive summaries using Excel Pivot Tables. Key DAX measures calculated include:
  * `Total Sales = SUM(Sales[Revenue])`
  * `Total Orders = DISTINCTCOUNT(Sales[Order_ID])`
  * `Average Order Value = [Total Sales] / [Total Orders]`
* **Dynamic Dashboard Design:** Built utilizing Excel Slicers, advanced formatting, and dynamic charting to create a clean, modern user interface.

---

## 📊 Deep-Dive Analytical Insights
Based on the Excel dashboard visualizations, here are the core findings:

1. **The Peak Sales Hours & Days:**
   * **Hourly Peak:** There is a massive spike in orders at **10:00 AM** (morning rush), followed by a secondary surge between **4:00 PM and 6:00 PM**.
   * **Daily Performance:** Sales revenue remains strong throughout the week, achieving its maximum velocity on **Tuesdays and Fridays**.
2. **Customer Payment Behavior:**
   * An overwhelming **96% of total transactions ($118.5K+) are paid via Card**, while only 4% use cash. 
3. **Product & Pricing Dynamics (Menu Engineering):**
   * High-revenue drivers like Latte and Americano dominate sales volume. The correlation scatter plot assists in identifying the ideal price elasticity for various menu tiers.

---

## 💡 Actionable Business Recommendations
Based on the extracted insights, I recommend the business owner to implement the following strategies:
1. **Labor & Shift Optimization:** Increase staff scheduling and pre-prepare inventory during the high-demand windows (9 AM – 11 AM and 4 PM – 6 PM) to reduce wait times and capture maximum revenue.
2. **Targeted Micro-Marketing:** Introduce happy hour bundles or loyalty discounts during slow hours (e.g., 1 PM – 3 PM) to smooth out demand and utilize idle capacity.
3. **Digital-First Operations:** Ensure that card payment terminals (POS machines) and network infrastructure are highly stable, as credit/debit cards represent 96% of the customer base.

---

## 📷 Dashboard Preview
![Coffee Shop Dashboard](coffee_dashboard.png)
