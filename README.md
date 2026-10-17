# 📊 Retail Sales & Executive Performance Dashboard (Excel)

## 🎯 Executive Summary
An interactive single-page executive Excel dashboard built using retail sales data (5,000+ orders) to analyze revenue, profitability, and categorical performance.

![Dashboard Preview](dashboard_preview.png)

## 💡 Key Business Insights
 **Total Revenue:** **$2,297,200.86** across **5,010** unique orders.
 **Top Performing Category:** **Technology** generated the highest revenue (**$836.1K**) and highest profit (**$145.5K**).
**Critical Business Issue:** **Furniture** category generated high sales (**$742K**) but extremely squeezed profit margins (**$18.4K ~ 2.5%**), indicating excessive discounting or high shipping costs.


## 🛠️ Key Technical Features
**Data Normalization:** Created helper time-series columns (`=TEXT(Date, "MMM-YYYY")`) to handle pivot grouping smoothly.
**Dynamic Aggregation:** Constructed modular Pivot Tables for core KPI metrics and regional performance.
**Visual Design & UX:** Removed gridlines, formatted currency metrics, and eliminated field buttons for a clean presentation canvas.
**User Interactivity:** Integrated dynamic cross-filtering Slicers for **Region** and **Segment** analysis.
