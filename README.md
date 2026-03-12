# 📊 E-commerce SQL & Python Analysis (Olist Dataset)

## Project Overview

This project analyses the **Olist e-commerce dataset** using Python and SQL to evaluate business performance, customer behaviour, and delivery efficiency.

The data was cleaned, transformed into fact and dimension tables, analysed using SQL, and visualised in a dashboard.

### Business Questions

- How is overall business performance?
- How has revenue changed over time?
- What percentage of customers make repeat purchases?
- How long does delivery take on average?

### Tools

- Python (pandas, plotly)
- SQL (SQLite)
- Google Colab


---

## Dataset

Olist Brazilian e-commerce dataset containing:

- orders  
- customers  
- order_items  
- products  
- payments  

Relationships between tables were used to build a clean analytical model.


---

## Data Model

Fact table:

- `fact_orders` (one row per order)

Dimension table:

- `dim_customers`

Fields used:

- revenue
- order_month
- delivery_time_days
- customer_unique_id


---

## KPIs

- Total Revenue (~13.2M)
- Total Orders (~96k)
- Average Order Value (~137)
- Unique Customers (~96k)
- Repeat Purchase Rate (~3%)
- Average Delivery Time (~12 days)
- Monthly Revenue Trend


---

## Dashboard

Built using **Python + Plotly** in Google Colab.

Visualisations included:

- KPI summary
- Monthly revenue trend
- Orders per month
- Repeat vs one-time customers
- Delivery time distribution


---

## Key Insights

- Revenue ≈ 13.2M from ~96k orders  
- Unique customers ≈ total orders → low retention  
- Repeat purchase rate ≈ 3%  
- Average order value ≈ 137  
- Average delivery time ≈ 12 days  
- Growth mainly driven by new customers  


---

## Next Steps

- Product-level analysis  
- Regional performance analysis  
- Delivery time vs repeat purchase analysis  
- Customer segmentation  
- Interactive dashboard (Power BI / Tableau)  


---

## Project Purpose

This project demonstrates skills in:

- Data cleaning
- Data modelling
- SQL analysis
- KPI design
- Data visualisation
- Business insight generation
