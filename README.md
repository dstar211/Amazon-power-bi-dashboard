# Amazon sales analysis  with Power BI

Amazon Sales Analysis Dashboard (Power BI)
📖 Project Overview
This project analyzes Amazon’s sales performance using Power BI to uncover key business insights and sales trends.
It visualizes KPIs, product performance, and revenue growth through interactive charts and dashboards,
helping track sales progress and decision-making over time.

🎯 Problem Statement
Businesses need to monitor sales trends, product performance, and customer feedback effectively to make data-driven decisions.
This dashboard provides a comprehensive view of Amazon sales data, helping identify growth opportunities and key revenue drivers.

📊 KPI’s Requirement

YTD Sales: Monitor year-to-date sales to gauge overall revenue performance over time.
```
YTD SALES = TOTALYTD(SUM(Amazon_Data[Price(Dollar)]),'Date table'[Date])
```

QTD Sales: Track quarterly sales to identify sales trends and fluctuations.
```
 QTD SALES = TOTALQTD(SUM(Amazon_Data[Price(Dollar)]),'Date table'[Date])
```

YTD Products Sold: Analyze total products sold throughout the year to understand product movement.

YTD Reviews: Measure year-to-date product reviews to assess customer satisfaction.

📈 Charts Requirement

YTD Sales by Month (Line Chart): Visualize monthly sales trends and seasonal patterns.

YTD Sales by Week (Column Chart): Display weekly sales data to spot short-term performance fluctuations.

Sales by Product Category (Heat Map): Show category-wise sales for a clear comparative view.

Top 5 Products by YTD Sales (Bar Chart): Highlight the top-performing products by revenue.  

### 💻 Tech Stack

| Tool / Technology | Purpose |
|--------------------|----------|
| **Power BI** | Data visualization and dashboard creation |
| **Power Query** | Data cleaning and transformation |
| **DAX** | Data modeling and advanced calculations |
| **Excel / CSV** | Data source and preprocessing |
| **Power BI Service** | Report publishing and sharing |
| **Microsoft Fabric / Cloud Storage** | Data integration and scalability |

💡 Insights

Identify high-performing products and categories
Understand seasonal and regional sales patterns
Evaluate customer satisfaction through review trends 
Support data-driven business planning

![Amazone ](https://github.com/dstar211/Amazon-power-bi-dashboard/blob/main/amazon%20.png)



