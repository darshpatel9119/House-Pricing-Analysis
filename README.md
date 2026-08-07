# House Pricing Analysis – Power BI

## 📌 Project Overview

An interactive **Power BI dashboard** developed to analyze house sales performance, pricing trends, regional differences, property age, and offer-price metrics.

The project demonstrates data preparation, data modeling, DAX calculations, time intelligence, and interactive data visualization.

## 🗂️ Data Source & Preparation

* Imported the raw CSV dataset into **SQL Server (SSMS)**.
* Connected SQL Server to **Power BI**.
* Performed data transformation and preparation using **Power Query**.
* Created a dedicated Date table and established relationships for time-based analysis.

## 📊 Key DAX Analysis

* **YoY Sales Growth** – Compared current-year and previous-year sales.
* **Offer Price** – Created a calculated column based on purchase price and price change.
* **Median Sale Price Change** – Analyzed median price changes by region.
* **Units Sold – Last Year & Last Quarter** – Calculated distinct units sold for historical periods.
* **Last 12 Months Sales** – Performed rolling twelve-month sales analysis.
* **Average Purchase Price** – Used `ALLEXCEPT()` for regional analysis.
* **Total YTD** – Performed Year-to-Date sales analysis using `TOTALYTD()`.
* **Average Price per Sqm** – Analyzed average property price per square meter.
* **Property Age** – Created an Age calculated column based on construction and sale year.
* **Offer Price to SQM Ratio** – Compared offer price relative to property area.

## 📈 Dashboard Pages & Visualizations

### Page 1 – House Market Overview

* **Line Chart** – YoY Sales Growth by Sales Type
* **Scatter Plot** – Purchase Price vs Offer Price
* **Bar Chart** – Median Sale Price Change
* **Card Visuals** – Units Sold Last Year, Units Sold Last Quarter, and Total Sales Last Year

### Page 2 – Sales Performance

* **Bar Charts** – Average Purchase Price by Region and Offer Price/SQM Ratio by Sales Type
* **Table** – Total Purchase Price and YTD Sales
* **Donut Chart** – Average Price per Sqm by Region
* **Key Influencers** – Purchase Price Analysis by Property Age

## 🛠️ Tools & Technologies

**Power BI | DAX | Power Query | SQL Server | SQL | CSV**

## 🎯 Key Skills Demonstrated

* Data Cleaning & Transformation
* Data Modeling & Relationships
* DAX & Time Intelligence
* Calculated Columns & Measures
* Interactive Data Visualization
* Business-Oriented Data Analysis
