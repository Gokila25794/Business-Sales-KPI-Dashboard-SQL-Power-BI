# Business-Sales-KPI-Dashboard-SQL-Power-BI
SQL + Power BI dashboard analyzing 50K+ sales &amp; order records to track revenue, top performers, regional KPIs, and business performance insights.
Problem Statement

Food delivery platforms generate large volumes of order and restaurant data, but business teams need KPI dashboards to understand revenue distribution, city performance, top restaurants, and operational efficiency.
This project analyzes order and restaurant datasets using SQL and Power BI to build an interactive KPI dashboard for sales, revenue, and performance insights.

📁 Dataset Overview

Zomato Orders & Restaurants datasets

Two-table model: Orders + Restaurant details

Data loaded into MySQL and transformed using SQL

~50K+ order records analyzed

Cleaned and aggregated data exported for BI modeling

🛠 Tools Used

MySQL — Data upload, joins, aggregations, transformations

SQL — Exploration, grouping, top-N analysis

Power BI — Dashboard visualization

Excel — Intermediate transformed data export

DAX — KPI measures

🔗 Data Preparation (SQL Work)

Uploaded raw datasets into MySQL

Joined Orders and Restaurants tables using Restaurant_ID

Performed aggregation queries for sales and order metrics

Extracted Top 5 restaurants by total sales using SQL

Generated city-wise and area-wise summaries

Exported transformed dataset for Power BI dashboarding

📈 Key KPIs Analyzed

Total Revenue

Average Order Value

Orders % by City

Restaurant Count by City & Area

Revenue by Area

Top 5 Restaurants by Sales

Monthly & Quarterly Sales Trend

Delivery Time vs Rating correlation

📊 Dashboard Features

City-wise order percentage distribution

Restaurant count by city and area

Revenue treemap by area

Top 5 restaurants by total sales ranking

Monthly and quarterly sales trend charts

Correlation visual: delivery time vs ratings vs order volume

KPI cards for Total Revenue & Average Order Value

Restaurant-wise sales summary table

🔎 Key Insights

Mumbai (22.56%) and Bangalore (22%) lead in total order share

Revenue across cities is balanced, with tight competition among top 5 cities

Area A (~3.39M) and Area B (~3.16M–3.9M) are highest revenue zones

Top restaurants each generated 3M+ total sales, with Bangalore Area B peaking (~0.98M)

April showed highest monthly sales (~1.376M), June lowest (~1.261M) — seasonal fluctuation observed

Average Order Value KPI (~367.69K aggregated) significantly exceeded initial benchmark target

Delivery time mostly clustered between 50–54 minutes regardless of order volume — indicates operational consistency

✅ Business Recommendations

Focus expansion and promotions in Area A and Area B high-revenue zones

Replicate Bangalore & Mumbai area performance strategies in other cities

Use seasonal peaks (Q2 spike) for targeted campaigns and offers

Promote top-performing restaurants for marketplace visibility

Monitor low-revenue areas (Area E) for operational or demand improvement
