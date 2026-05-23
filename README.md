# Discount Mart Sales Analytics Dashboard

## Project Overview
In retail management, tracking high-level performance metrics while maintaining the ability to drill down into monthly trends and category drivers is critical for sustained profitability. 

The goal of this project was to design an interactive sales analytics dashboard for **Discount Mart**, a fictional supermarket. The dashboard translates raw sales records into actionable business insights, helping stakeholders quickly evaluate revenue trends, monitor profit levels, and pinpoint top-performing product categories across different fiscal years.

## Tools Used
* **Tableau Public** (Interactive Dashboard Creation & Data Visualization)
* **Excel / SQL** (Data Cleaning, Filtering, and Structured Transformation)

## Dataset
The dataset consists of supermarket transaction records for Discount Mart. It includes granular, row-level details on order dates, transaction values, localized sales regions, product category classifications (Technology, Office Supplies, and Furniture), and financial outcomes (Total Sales and Net Profit). 

## Key Questions Answered
* **What are the overall financial health metrics of the business?** (Evaluating total baseline revenue and absolute profit margins).
* **How do sales fluctuate throughout the year?** (Identifying peak operational months and low-performing periods against a calculated yearly baseline).
* **Which product lines are driving the highest revenue?** (Breaking down performance across primary product categories to support inventory and marketing focus).

## Process

### 1. Data Cleaning
* Imported raw transaction data into Excel/SQL to check for structural anomalies, duplicate entries, and missing values.
* Standardized date fields to ensure accurate formatting for chronological time-series analysis.
* Verified that financial columns (Sales, Profit) were formatted as numeric values with consistent currencies.

### 2. Data Exploration
* Profiled the dataset to understand the distribution of sales across different product lines.
* Ran preliminary aggregations to identify extreme statistical outliers, such as the minimum and maximum monthly revenue marks.

### 3. Data Analysis
* Segmented the cleaned data by calendar years to support dynamic filtering capabilities.
* Calculated overall business benchmarks, including aggregate profit margins and the baseline monthly average sales line used for performance comparison.

### 4. Visualization
* Designed an intuitive, interactive layout in Tableau Public optimized for non-technical business stakeholders.
* Built a monthly line chart enhanced with a static average line to clearly distinguish above-average performance months from trailing ones.
* Implemented a clean horizontal bar chart for categorical data to prevent visual clutter and enable instant performance ranking.

## Dataset
The dataset utilized for this analysis consists of supermarket transaction records for **Discount Mart**. 

* **Source Data:** The raw and cleaned data files can be found in the [`/data`](./data/) directory of this repository.
* **Attributes:** It includes row-level details on order dates, product categories (Technology, Office Supplies, Furniture), and financial variables (Sales, Profit).

## Insights & Recommendations

### Key Insights
* **Overall Performance:** The supermarket achieved a total revenue of **$733,215** with an overall profit of **$219,965**.
* **Seasonal Sales Fluctuation:** Sales performance varies drastically by month. Business activity peaks aggressively in **November ($118.4K)**, while hitting its lowest operational trough in **February ($20.3K)**.
* **Category Drivers:** Volume and revenue generation are heavily concentrated within three core product sectors: **Technology**, **Office Supplies**, and **Furniture**, with clear tier distinctions visible between them.

### Recommendations
* **Capitalize on Peak Seasons:** Allocate the majority of the marketing and promotional budget toward the Q4 ramp-up leading into November to maximize high-conversion seasonal shopping trends.
* **Mitigate Q1 Slumps:** Introduce targeted customer loyalty incentives, clear-out promotions, or bundled discounts during February to stimulate demand during the historical low-volume period.
* **Optimize Category Mix:** Evaluate inventory levels and supplier relationships within the top-performing categories to prevent stockouts during peak months and maximize high-margin returns.

## Dashboard Preview

![Discount Mart Dashboard Preview](dashboard_preview.png)

## Files Included
* **`data/`**: Cleaned dataset files utilized for the Tableau workbook.
* **`scripts/`**: SQL queries used during the initial data preparation and exploration phases.
* **`dashboard/`**: Link to the interactive workbook on Tableau Public or the local `.twbx` file.
