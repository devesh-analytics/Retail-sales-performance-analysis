# 🛒 Retail Sales & Business Performance Analytics | Power BI

## 📌 Project Overview
This project transforms a messy retail transaction dataset into a validated analytical dataset and an interactive Power BI dashboard. It provides management with a consolidated view of retail sales performance, eliminating the need for manual consolidation across multiple sources. 

## 🎯 Project Objectives
- Create a reliable cleaned dataset for reporting.
- Monitor monthly sales and order performance.
- Analyze product, category, salesperson, region, city, and channel performance.
- Monitor completed, returned, and cancelled orders.
- Present key findings through an interactive Power BI dashboard.

## 🛠️ Tools & Technologies
- **Microsoft Power BI** – Data modeling, DAX, visualization, and interactive reporting.
- **Microsoft Excel** – Raw data cleaning, validation, calculations, and analysis.
- **MySQL** – Data validation, querying, and business analysis.
- **ChatGPT** – Analytical assistance and DAX documentation.

## 📊 Dataset & Quality Management
The original dataset contained duplicates, missing values (Customer ID, City, Payment Method), negative quantities, and invalid dates. After profiling and cleaning via SQL and Excel, the finalized dataset contains:
- **1,505 cleaned records**.
- **25 total columns** (including cleaning and helper fields).
- **3 Sales Channels:** Online, Store, Marketplace.

---

## 📈 Key KPIs

| Metric | Value |
|---|---:|
| Total Sales | 29.59M |
| Total Orders | 2K |
| Total Quantity | 5K |
| Average Order Value | 19.73K |

---

## 🔍 Key Insights
- **Sales Trends:** The monthly trend highlights distinct high- and low-performing periods across the year.
- **Category & Product Performance:** Product analysis clearly identifies the major items contributing to overall revenue, categorized seamlessly into Accessories, Electronics, Furniture, and Stationery.
- **Geographic Breakdown:** Regional analysis allows for direct comparisons between East, West, South, and North performance.
- **Order Status:** Order-status filtering isolates completed transactions from returned and cancelled transactions, providing visibility into fulfillment success.

---

## 💡 Business Value
- **Centralized View:** Provides a single, consolidated view of sales performance for Senior Management.
- **Interactive Comparisons:** Multiple slicers allow focused analysis by date, region, category, channel, and status.
- **Actionable Workflows:** Establishes a repeatable workflow from raw data ingestion to final dashboard visualization.
- **Efficiency:** Faster identification of products, categories, regions, and periods requiring immediate business attention.

---

## 📷 Dashboard Preview

### Main Dashboard Overview
This view displays the overall performance metrics, including 29.59M in total sales.
![Main Dashboard Overview](./Screenshot%202026-09-24%20141451.png)

### Filtered View: East Region & Electronics
This view highlights sales specific to the East region and Electronics category.
![Filtered View 1](./Screenshot%202026-09-24%20141523.png)

### Filtered View: North Region & Electronics
This view demonstrates the performance of Electronics within the North region.
![Filtered View 2](./Screenshot%202026-09-24%20141713.png)

### Filtered View: South Region & Stationery
This view filters the data to show performance for Stationery in the South region.
![Filtered View 3](./Screenshot%202026-09-24%20141637.png)

---

## 📁 Project Files

| File | Description |
|---|---|
| [📊 Power BI Dashboard](./Retail%20Sales%20%26%20Business%20Performance%20Analytics.pbix) | Download and open the interactive Power BI dashboard |
| [📁 Cleaned Dataset](./Retail_Sales_Cleaned.xlsx) | Excel dataset used for the final analysis |
| [📄 Case Study (BRD/FRD)](./Retail_Sales_Case_Study.pdf) | Business Requirements, Functional Requirements, and methodology |

---

## 👨‍💻 Author

**Devesh Singh**

Recent BBA Graduate | Business Analyst / Data Analyst

🔗 **Portfolio:** https://deveshwork.lovable.app/

🔗 **GitHub:** https://github.com/devesh-analytics
