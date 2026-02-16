# 🛒 Mahadev Ecommerce Sales Dashboard

An interactive **Power BI dashboard** built to analyze and visualize ecommerce sales performance across multiple dimensions: revenue, profit, customer insights, product categories, geography, and payment behavior.

![Mahadev Ecommerce Sales Dashboard](https://github.com/okroshan4u/ecommerce-sales-analysis-powerbi/raw/main/Mahadev%20Ecommerce%20sales%20dashboard%20screenshot.jpg)

*Screenshot of the Mahadev Ecommerce Sales Dashboard in Power BI (dark theme)*

## 📌 Overview

The **Mahadev Ecommerce Sales Dashboard** provides a comprehensive 360° view of ecommerce business performance. It helps stakeholders monitor key metrics, spot trends, identify problem areas, and make data-driven decisions.

Features modern **dark theme UI** + dynamic filtering + cross-highlighting.

## 🎯 Business Objectives

- Track overall profit and revenue performance
- Identify profitable vs loss-making months
- Analyze sales distribution by state
- Evaluate product category & sub-category performance
- Understand top customers' contribution to revenue
- Monitor payment method preferences
- Enable quick quarterly performance comparison

## 📊 Key Performance Indicators (KPIs)

| Metric                | Description                          |
|-----------------------|--------------------------------------|
| Total Profit          | Net profit after all costs           |
| Total Sales Amount    | Gross revenue from all orders        |
| Total Orders          | Count of completed orders            |
| Average Order Value   | AOV = Total Sales ÷ Total Orders     |

## 📈 Dashboard Visualizations

1. **Profit Analysis**  
   - Average Profit by Month (bar chart)  
   - Conditional formatting: **Blue = Profit** | **Orange = Loss**  
   - Quickly spot seasonal profitability trends

2. **Sales by Geography**  
   - Sum of Amount by State (map or bar chart)  
   - Identify top-performing and underperforming regions

3. **Category Analysis**  
   - Sum of Quantity by Category (pie/donut/bar)  
   - Main categories: **Furniture** | **Electronics** | **Clothing**

4. **Sub-Category Profitability**  
   - Sum of Profit by Sub-Category (bar chart)  
   - Highlights most profitable and loss-making product lines

5. **Customer Contribution**  
   - Sum of Amount by Customer Name (bar or treemap)  
   - Reveals top revenue-generating customers (Pareto analysis ready)

6. **Payment Mode Distribution**  
   - Breakdown of orders by:  
     - Credit Card  
     - Debit Card  
     - UPI  
     - COD

## 🛠 Tools & Technologies Used

- **Power BI** (Desktop / Service)
- **DAX** (Data Analysis Expressions)
- Data Modeling (star schema)
- Conditional Formatting Rules
- Slicers & Cross-filtering
- Custom dark theme / JSON theme file
- Card visuals, KPI cards, dynamic titles

## 📂 Data Model

**Fact Table**
- Orders / Sales transactions

**Dimension Tables**
- Customers
- Products (with Category & Sub-category)
- Dates / Calendar
- Payment Modes
- Geography (States)

Relationships are properly defined with single-direction filtering for optimal performance.

## 🎨 Design Features

- Modern dark gradient background
- Card-style KPI visuals with conditional icons/colors
- Quarter slicer for time intelligence
- Consistent conditional formatting logic  
  → **Blue** = Positive  
  → **Orange** = Negative
- Clean layout, good spacing, professional typography

## 📌 Key Insights Delivered

- Several months show consistent negative profitability (seasonal dips)
- A few sub-categories generate outsized profit
- Small % of customers drive large % of revenue (80/20 rule likely applies)
- Sales heavily concentrated in select states
- Digital payments (UPI + Cards) significantly outperform COD

## 🚀 How to Use

1. Open the `.pbix` file in Power BI Desktop
2. Use the **Quarter slicer** to focus on specific periods
3. Click on any bar/segment to cross-filter the entire dashboard
4. Hover over visuals for exact values & tooltips
5. Analyze profit trends using the color coding

## 📈 Planned Future Enhancements

- Year-over-Year (YoY) & Month-over-Month (MoM) comparison
- Built-in forecasting lines
- Drill-through pages (Customer, Product, Region detail)
- Customer segmentation (RFM analysis)
- Profit Margin % KPI & trend
- What-if parameters for margin simulation

## 👨‍💻 Author

**Your Name**  
Business Intelligence Developer | Data Analyst

Feel free to connect: [LinkedIn](#) | [Email](#) | [Portfolio](#)

⭐ If you find this dashboard helpful, give it a star!
