# E-Commerce Sales Intelligence Dashboard | CPG & FMCG

## Overview
This project presents a powerful and interactive E-Commerce Sales Intelligence Dashboard built for sales performance across different regions, categories, and products. The solution integrates multiple data sources including HubSpot CRM, ERP, Google Cloud Storage, and Nielsen to provide end-to-end insights for sales, marketing, and executive teams.

---

## Tools & Technologies
- Power BI – Dynamic and real-time dashboard visualizations
- SQL – Data transformation and integration
- Python – Forecasting, data cleansing, and automation scripts
- Google Cloud Platform (GCP) – Cloud storage and connector support
- HubSpot CRM – Customer and sales pipeline data integration
- ERP System – Product, order, and fulfillment data
- Nielsen – Competitor performance metrics and market intelligence
- JIRA – Project tracking and collaboration

---

## Business Use Case
- Visualize regional and product-wise sales KPIs
- Compare revenue vs. profit margin by category and time
- Integrate CRM and ERP for real-time sales pipeline and fulfillment tracking
- Benchmark against competitors using Nielsen market share data
- Forecast future sales performance based on historical trends

---

## Project Structure
```
ecommerce-sales-intelligence/
├── data/
│   ├── _sales_data.csv
│   ├── erp_data.csv
│   ├── hubspot_export.csv
│   ├── nielsen_market_data.csv
│   └── region_category_mapping.csv
├── scripts/
│   ├── data_cleaning.py
│   ├── forecast_model.ipynb
│   └── join_and_transform.sql
├── dashboards/
│   ├── _Sales performance dashboard.pbix
├── visuals/
│       ├── Sales performance dashboard.png
│       ├── Sales performance.png
├── README.md
```

---

## Key Achievements
- Built real-time Power BI dashboards with regional filters, product breakdowns, and custom KPIs
- Created forecasting models in Python to estimate monthly and quarterly revenue
- Automated data refresh from HubSpot CRM and ERP databases, cutting manual reporting time by 30%
- Integrated Nielsen competitor data for side-by-side market analysis
- Aligned dashboards with business goals by collaborating with sales and marketing teams

---

## Data Sources & Integration
- Connected to Google Cloud Storage and ERP database for product orders and fulfillment data
- Pulled HubSpot CRM exports via API and combined with transaction-level data
- Joined Nielsen data for market comparison metrics
- Used SQL (BigQuery + local) to preprocess and unify datasets for visualization

---

## KPI Metrics Tracked
- Total Revenue, Profit Margin, Units Sold
- Sales Trend (Daily, Weekly, Monthly)
- Region & Category-wise Growth
- Forecasted Revenue vs. Actuals
- Market Share vs. Competitors (via Nielsen)
- Pipeline Performance (via HubSpot)

---

## Outcome
> Empowered leadership and business units with real-time insights, driving smarter decisions, boosting sales strategy effectiveness, and improving operational efficiency across the organization.

---

## Getting Started
1. Clone this repo
2. Load datasets from the `/data` folder or your cloud sources
3. Run SQL scripts to transform data (`scripts/join_and_transform.sql`)
4. Open ` Sales_performance.pbix` in Power BI and refresh data
5. (Optional) Run `forecast_model.ipynb` for predictive modeling

---

## Screenshots
_See `/visuals/Sales performance dashboard/` for images of dashboards and reports. _

---

## Author
Haritha Nair  
Azure Consultant & BI Engineer  
[harithanair2234@gmail.com] (mailto:harithanair2234@gmail.com)

---

## License
This project is open source.
![image](https://github.com/user-attachments/assets/53846432-7ebc-423b-b46e-a8eddf0ae2e2)
