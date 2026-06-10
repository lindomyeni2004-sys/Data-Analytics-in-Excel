# Corporate Financial & Sales Analysis Dashboard (Excel)

## Project Overview
This project demonstrates the end-to-end process of transforming a raw, unorganized corporate financial dataset into a fully interactive **Sales Analysis Dashboard** built entirely in Microsoft Excel. The final deliverable enables stakeholders to filter, visualize, and track key performance metrics across multiple dimensions, including products, global regions, and market segments.

---

## What I Had (The Raw Data)
The initial dataset consisted of a flat table (`Original Data`) containing 700+ rows of raw financial transactions with the following parameters:
* **Dimensions:** Market Segments, Countries (Canada, France, Germany, Mexico, USA), and Products (Amarilla, Carretera, Montana, Paseo, Velo, VTT).
* **Financial Metrics:** Units Sold, Manufacturing Price, Sale Price, Gross Sales, Discounts, Cost of Goods Sold (COGS), and Net Profit.
* **Time Parameters:** Transaction Dates, Month Names, Month Numbers, and Fiscal Years.

The fundamental relationship governing the financial columns in the source data is represented as:
$$\text{Net Profit} = \text{Sales} - \text{COGS}$$
$$\text{Sales} = \text{Gross Sales} - \text{Discounts}$$

---

## What I Made of It (The Transformation)

I transformed the raw transactional records into a structured, relational analytics system categorized across three main layers:

### 1. Multi-Dimensional Pivot Tables
To isolate key business metrics and aggregate performance trends, I generated dedicated pivot tables summarizing:
* **Volume Metrics:** Total `Units Sold` grouped individually by market segment and by country.
* **Product Performance:** Aggregated summaries of `Total Sales`, `Profit Per Product`, and `COGS Per Product` to evaluate individual item profitability.
* **Cost Analysis:** Evaluation of product-specific manufacturing costs against total revenue.

### 2. Analytical Data Visualizations (Graphs)
Using the summarized pivot data, I designed clean, expressive visual charts to make the numbers immediately interpretable:
* **Bar/Column Charts** comparing the volume of units sold across international borders and market tiers.
* **Performance Plots** visualizing top-performing products by total revenue generation vs. net profitability margins.

### 3. Dynamic & Interactive Sales Dashboard
The final culmination of this project is a single-screen **Sales Analysis Dashboard** that synthesizes all individual graphs and KPIs into a clean business intelligence interface. 
* **Interactive Controls:** Integrated interactive slicers (such as filters for Year, Country, and Product Segment).
* **Dynamic Response:** When a user toggles a slicer, all underlying pivot tables and connected graphs dynamically update in real-time, allowing executives to seamlessly deep-dive into regional or segment-specific trends.

---

## Key Skills & Core Excel Features Demonstrated
* **Data Summarization:** Advanced Pivot Tables & Pivot Charts.
* **Dashboard Architecture:** Layout design, conditional formatting, dynamic charting, and cross-filtering using Slicers.
* **Financial Data Modeling:** Transforming flat transactional schemas into aggregated business dimensions.
