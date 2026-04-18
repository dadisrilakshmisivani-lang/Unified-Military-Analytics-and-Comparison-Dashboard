# 📊 Cleaned Data

This folder contains processed and structured datasets used for analysis and dashboard development in the **Unified Military Analytics and Comparison Dashboard** project.

---

## 📌 Files

### 1. military_cleaned.csv

* Description: Cleaned version of the raw scraped data.
* Processing steps:

  * Removed special characters (%, commas, symbols)
  * Converted values to numeric format
  * Standardized column names
  * Handled missing/null values

📌 Purpose:
Used as the base dataset for further analysis and KPI generation.

---

### 2. 📈 military_final.csv

* Description: Fully structured dataset ready for visualization.
* Enhancements:

  * Organized columns for dashboard compatibility
  * Consistent formatting across all metrics
  * Suitable for Power BI / Tableau integration

📌 Purpose:
Directly used for building dashboards and visualizations.

---

### 3. 📊 military_final(KPI).csv

* Description: Dataset enriched with Key Performance Indicators (KPIs).
* Includes:

  * Power Index Rank Gap
  * Assets per Capita
  * Budget-to-GDP Ratio
  * Additional derived metrics

📌 Purpose:
Used for advanced analytics and KPI-based visual dashboards.

---

## 🔄 Data Processing Workflow

1. Raw Data → Collected via web scraping
2. Cleaning → Data formatted and standardized (`military_cleaned.csv`)
3. Structuring → Organized dataset (`military_final.csv`)
4. KPI Engineering → Derived metrics added (`military_final(KPI).csv`)

---

## 📝 Notes

* All datasets are cleaned and validated for accuracy.
* Missing values are minimized and handled appropriately.
* These datasets are optimized for visualization tools like Power BI and Tableau.
