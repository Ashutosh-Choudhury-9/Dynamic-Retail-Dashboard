# Dynamic-Retail-Dashboard
# Overview
This project involves the creation of a dynamic retail dashboard using Microsoft Excel, designed to visualize and analyze retail sales data across various dimensions. The dashboard connects to three main data tables-Orders, Returns, and People-and helps businesses gain insights into key sales performance metrics. This project is ideal for businesses looking to enhance their decision-making processes by analyzing data through dynamic visualizations and KPIs.

The dashboard includes key performance indicators (KPls) that track important metrics such as Total Sales, Total Profit, Quantity Sold, Number of Orders, and Profit Margin. These KPis are calculated and displayed on a centralized chart to ensure easy comparison and visualization. The project covers multiple problem statements that help break down the data into actionable insights.
# Sample Data Tables
# 📑 ORDERS Table
| Order ID        | Order Date | Ship Date  | Ship Mode     | Customer Name      | Segment     | City         | State           | Country        | Product Name                   | Sales    | Quantity | Profit   |
|:----------------|:-----------|:-----------|:--------------|:-------------------|:------------|:-------------|:----------------|:---------------|:-------------------------------|---------:|---------:|---------:|
| CA-2012-124891  | 31-07-2020 | 31-07-2020 | Same Day      | Rick Hansen        | Consumer    | New York City| New York        | United States  | Plantronics CS510 Headset       | 2309.65  | 7        | 762.18   |
| IN-2013-77878   | 05-02-2021 | 07-02-2021 | Second Class  | Justin Ritter      | Corporate   | Wollongong   | New South Wales | Australia      | Novimex Leather Armchair        | 3709.39  | 9        | -288.76  |
| IN-2013-71249   | 17-10-2021 | 18-10-2021 | First Class   | Craig Reiter       | Consumer    | Brisbane     | Queensland      | Australia      | Nokia Smart Phone              | 5175.17  | 9        | 919.97   |
| ES-2013-1579342 | 28-01-2021 | 30-01-2021 | First Class   | Katherine Murray   | Home Office | Berlin       | Berlin          | Germany        | Motorola Cordless Phone        | 2892.51  | 5        | -96.54   |
| SG-2013-4320    | 05-11-2021 | 06-11-2021 | Same Day      | Rick Hansen        | Consumer    | Dakar        | Dakar           | Senegal        | Sharp Wireless Fax             | 2832.96  | 8        | 311.52   |

# 👥 PEOPLE Table
| Person              | Region  |
|:--------------------|:--------|
| Anna Andreadi        | Central |
| Chuck Magee          | South   |
| Kelly Williams       | East    |
| Matt Collister       | West    |
| Deborah Brumfield    | Africa  |

# ↩️ RETURNS Table
| Returned | Order ID        | Market         |
|:---------|:----------------|:---------------|
| Yes      | MX-2013-168137   | LATAM          |
| Yes      | US-2011-165316   | LATAM          |
| Yes      | ES-2013-1525878  | EU             |
| Yes      | CA-2013-118311   | United States  |
| Yes      | ES-2011-1276768  | EU             |

# 📌 KPI Table
The KPI table consolidates the most essential performance metrics for the retail analysis. These KPIs allow the dashboard to provide actionable insights by comparing important aspects of sales performance.

| KPI                  | Name           | Symbol |
|:---------------------|:---------------|:-------|
| Sum of Sales          | Total Sales    | 📈     |
| Sum of Profit         | Total Profit   | 💰     |
| Sum of Quantity       | Total Quantity | 📦     |
| Count of Order ID     | No. Of Orders  | 🛒     |
| Sum of Profit Margin  | Profit Margin  | 🔍     |

# 🎯 Problem Statements Solved
The dynamic retial dashboard answers several business questions, providing in-depth insights into key performance areas:

1. **KPIs** : Total Sales, Total Profit, Quantity, Number of Orders, Profit Margin.

   ![KPIs](https://github.com/user-attachments/assets/586630b0-a11d-4782-b4a5-374bc0127335)
   
2. **Sales and Profit Analysis** : Understanding overall sales and profitability.

   ![Sales vs Profit](https://github.com/user-attachments/assets/8df46dd9-d6b2-46f2-bd9a-98c3004252a7)

3. **Category-Wise Profit** : Breakdown of profit by product category.

   ![Category-wise Total Profit](https://github.com/user-attachments/assets/d31538b8-add7-44e3-ac7b-b6b10d966702)

4. **Segment-Wise Sales Share %** : Sales distribution across segments.

   ![Segment-wise Total Sales %](https://github.com/user-attachments/assets/9620efc0-3984-4fb8-88d4-83e953fdf3fa)

5. **Sales by Country** : Geographic analysis of sales performance by different countries.

   ![Total Sales by Country](https://github.com/user-attachments/assets/9408b436-9b56-4a1d-8395-c404b559f912)

6. **Top 5 Sub-categories** : The best performing sub-categories based on quantity.

   ![Top 5 Sub-category by Total Quantity](https://github.com/user-attachments/assets/34cafa6c-3cf8-41ab-aa9b-7e37ec51855b)

7. **Bottom 5 Sub-categories** : The least performing sub-categories based on quantity.

   ![Bottom 5 Sub-category by Total Quantity](https://github.com/user-attachments/assets/4277eeaf-29b8-4ffc-b480-44a9f731386d)

8. **Yearly Sales Trend** : Understanding sales trend over the years.

    ![Yealy Sales Trend](https://github.com/user-attachments/assets/49eceaf7-03e6-4edb-b15d-e5d3453ee3ea)

# 📊 Dashboard
Snapshot of the dashboard:

![Dashboard Snapshot](https://github.com/user-attachments/assets/b3fd71cf-de91-4e78-a1e4-e72b05c8678f)

# 🛠️ Tools Used
- Microsoft Excel
- Power Query
- Pivot Tables
- Slicers & Filters
- Data Visualization (Bar, Line, Pie Charts)
- Dynamic KPI Cards

# 🏁 Conclusion















