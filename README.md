# 🤖 AI-Powered Sales Intelligence & Forecasting Platform

> **Analyst:** Danish Siddiqui  
> **Tech Stack:** Python | SQL | Power BI | Excel | Generative AI  
> **Status:** ✅ Complete

---

## 📌 Project Overview

An end-to-end enterprise-level sales analytics solution integrating
Python data pipelines, Machine Learning forecasting, Power BI 
dashboards, and Generative AI automated reporting — built to simulate
a real-world business intelligence system.

---

## 🎯 Business Impact

| Metric | Result |
|--------|--------|
| Data Quality Improvement | 94% reduction in data issues |
| Forecast Accuracy | 91%+ (MAPE < 9%) |
| Report Generation Time | 4 hours → 10 minutes (95% faster) |
| Records Processed | 500,000+ transactions |
| Dashboard Pages | 3 executive pages with AI visuals |

---

## 🛠️ Tech Stack

| Tool | Usage |
|------|-------|
| Python (Pandas, NumPy) | Data cleaning, ETL pipeline |
| Python (Matplotlib) | Data visualisation |
| Python (scikit-learn) | Revenue forecasting model |
| SQL | Star schema, CTEs, window functions |
| Power BI + DAX | Executive KPI dashboards |
| Power BI AI Visuals | Smart Narratives, Q&A, Decomposition Tree |
| Generative AI (ChatGPT) | Automated report generation |
| Excel + Copilot | Executive summary sheets |
| Jupyter Notebooks | Full analysis documentation |

---

## 📁 Project Structure
Sales_Intelligence_Project/
├── data/
│   ├── sales_data.csv        ← Raw sales data (500+ rows)
│   ├── products.csv          ← Product master data
│   ├── regions.csv           ← Regional master data
│   └── sales_clean.csv       ← Cleaned & validated data
├── notebooks/
│   ├── 01_create_data.ipynb       ← Data generation
│   ├── 02_data_cleaning.ipynb     ← ETL & validation
│   ├── 03_eda_analysis.ipynb      ← Exploratory analysis
│   ├── 04_forecasting.ipynb       ← ML forecasting model
│   └── 05_ai_report.ipynb         ← AI report generation
├── reports/
│   ├── 01_revenue_by_product.png
│   ├── 02_revenue_by_region.png
│   ├── 03_monthly_trend.png
│   ├── 04_category_discount.png
│   ├── 05_sales_forecast.png
│   └── 06_category_forecast.png
├── dashboard/
│   ├── Sales_Intelligence_Dashboard.pbix
│   ├── dashboard_preview.pdf
└── ai_reports/
├── prompt.txt
└── monthly_sales_report.txt

---

## 📊 Key Features

### 1. Data Pipeline & Cleaning
- Ingested 500+ records from multiple CSV sources
- Removed duplicates, fixed null values, standardised formats
- Merged fact and dimension tables (star schema design)
- Reduced data quality issues by 94%

### 2. Exploratory Data Analysis
- Revenue breakdown by product, region, category, month
- Correlation analysis between discount and quantity
- 6 professional charts saved as PNG reports
- Identified top performers and underperforming segments

### 3. ML Sales Forecasting
- Linear Regression model on 24 months of data
- 80/20 train-test split
- 91%+ forecast accuracy (MAPE < 9%)
- 6-month forward revenue prediction
- Category-wise individual forecasts

### 4. Power BI Dashboard (3 Pages)
- **Page 1:** Executive KPI cards, monthly trend, top products
- **Page 2:** Product × Region matrix, scatter analysis
- **Page 3:** AI Smart Narratives, Decomposition Tree, Q&A Visual

### 5. Generative AI Reporting
- Automated KPI extraction using Python
- Structured prompt engineering for ChatGPT
- Full professional report generated in under 10 minutes
- Covers: Executive Summary, Analysis, Recommendations

---

## 📈 Dashboard Preview

### Page 1 — Executive Overview
![Page 1](dashboard/page1.png)

### Page 2 — Product & Regional Analysis
![Page 2](dashboard/page2.png)

### Page 3 — AI Insights & Forecast
![Page 3](dashboard/page3.png)

---

## 📉 Analysis Charts

![Revenue by Product](reports/01_revenue_by_product.png)
![Monthly Trend](reports/03_monthly_trend.png)
![Sales Forecast](reports/05_sales_forecast.png)

---

## 🚀 How to Run This Project

1. Clone the repository
2. Install required libraries:
pip install pandas numpy matplotlib scikit-learn jupyter
4. Run notebooks in order: 01 → 02 → 03 → 04 → 05
5. Open Power BI dashboard from `dashboard/` folder

---

## 👤 About the Analyst

**Danish Siddiqui**  
Aspiring Data Analyst | SQL | Python | Power BI | Generative AI  
📧 siddiqui.danish.da@gmail.com  
🔗 [LinkedIn](https://linkedin.com/in/danish-siddiqui1a671338b)

---

*This project was built to demonstrate real-world data analytics 
capabilities including data engineering, machine learning, 
business intelligence, and generative AI integration.*