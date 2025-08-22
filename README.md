# E-commerce Dashboard — Google Looker Studio

## Project Overview
This project is an interactive **Google Looker Studio dashboard** built on an e-commerce dataset.  
The dashboard is designed to help business stakeholders track **sales performance, product insights, and inventory health** in one place.

## Objectives
- Provide an overview of key performance metrics (Revenue, Sales, Pricing, Ratings).
- Enable product-level drilldowns with filters and search controls.
- Monitor inventory with stock value analysis and low-stock alerts.

## 🗂Dashboard Structure
### Page 1 — Overview
- KPIs: **Revenue, Sales, Avg Price, Avg Rating** (with period comparison).
- Time series: **Revenue trend by Date**.
- Bar chart: **Category vs Revenue**.
- Donut chart: **Price Band vs Revenue**.
- Filters: **Date range (report-level)**, **Category (page-level)**.
- Highlight: **Top 3 Products by Revenue**.

### Page 2 — Products
- Table with product-level details:  
  *Product Name, Category, Sales, Revenue, Price, Effective Price, Rating, Reviews, Low Stock Flag*.  
- Added **Inventory Value** column.  
- Conditional formatting: Low stock flagged in red.  
- Interactive filters: Product Search, Category dropdown, Price Band dropdown, Rating slider.  
- Default sorting by **Revenue (descending)**.

### Page 3 — Inventory
- KPIs: **Total Stock Units, Total Inventory Value**.  
- Bar chart: **Category vs Inventory Value**.  
- Product-level table: *Product Name, Stock Quantity, Inventory Value, Low Stock Flag*.  

## Features Implemented
- **Calculated fields**: Discount normalization, Effective Price after discount, Revenue, Inventory Value, Price Bands.  
- **Parameters**: Low Stock Alert threshold (user-controlled).  
- **Conditional formatting** for quick identification of at-risk SKUs.  
- **Interactive filters & search** for flexible exploration.  
- **Multi-page navigation** to separate executive summary, product insights, and inventory analysis.

## Key Insights
- Identified top revenue-generating products and categories.  
- Revealed sales distribution by pricing tiers.  
- Flagged products at risk of stockouts via low-stock alerts.  
- Showed capital tied up in inventory across categories.

## Tools & Skills
- Google Looker Studio  
- Data visualization & storytelling  
- Business KPIs (Revenue, Sales, Inventory Value, Pricing)  
- Dashboard design (multi-page, filters, parameters)

## Live Report
https://lookerstudio.google.com/reporting/8b06275f-5271-4766-b804-076e2c12ab8f
