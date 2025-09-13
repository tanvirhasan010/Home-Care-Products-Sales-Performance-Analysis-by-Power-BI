# 🧼 Home Care Products Sales Performance Analysis - Power BI Dashboard

## 📊 Project Overview

This repository contains a **Power BI** dashboard project focused on analyzing the sales performance of home care products. The project provides actionable insights into sales trends, product performance, regional distribution, and customer behavior within the home care industry. This analysis is designed to support strategic decision-making for sales, marketing, and inventory management.

## 🎯 Business Objectives

- **Sales Performance Monitoring**: Track overall sales revenue, units sold, and profitability.
- **Product Portfolio Analysis**: Identify best-selling and underperforming home care product categories.
- **Regional Performance**: Analyze sales distribution across different regions and territories.
- **Temporal Trends**: Understand seasonal patterns and sales performance over time.
- **Customer Insights**: Analyze purchasing behavior and preferences in the home care market.
- **Inventory Management**: Identify stock levels, turnover rates, and potential stockout risks.

## 📁 Project Contents

- **Power BI Desktop File** (`.pbix`): The main file containing data transformations, data model, reports, and visualizations.
- **Data Source** (Sample/Processed): The dataset used for analysis.
- **README.md**: This documentation file.
- **Screenshots/**: Folder containing images of the final dashboard.

## 🔧 Tools & Technologies Used

- **Microsoft Power BI Desktop**: For ETL, data modeling, and visualization
- **Power Query**: For data extraction, transformation, and loading
- **DAX (Data Analysis Expressions)**: For creating calculated measures and KPIs
- **Data Source**: Likely Excel, CSV, or database containing home care products sales data

## 📈 Key Features of the Dashboard

### 1. Executive Summary View
- High-level KPIs: Total Sales Revenue, Total Units Sold, YTD Growth, Profit Margin %
- Key performance indicators with period comparisons (YoY, QoQ, MoM)
- Quick overview of overall business health

### 2. Sales Performance Analysis
- **Revenue Trend Analysis**: Monthly/quarterly sales performance visualization
- **Product Category Performance**: Sales breakdown by product categories (e.g., cleaning supplies, laundry care, air fresheners)
- **Top Products Ranking**: Best-performing products by revenue and units sold
- **Price Point Analysis**: Relationship between pricing and sales volume

### 3. Geographical Analysis
- **Regional Sales Distribution**: Choropleth map or bar charts showing sales by region/territory
- **Top Performing Stores/Regions**: Identification of high-performing sales locations
- **Market Penetration Analysis**: Sales density across different geographical areas

### 4. Time Intelligence
- **Seasonal Patterns**: Identification of peak sales seasons (e.g., spring cleaning periods)
- **Sales Growth Trends**: Month-over-month and year-over-year growth analysis
- **Holiday Impact Analysis**: Sales performance during special events and holidays

### 5. Interactive Filtering
- Time period slicers (year, quarter, month, week)
- Product category filters
- Regional/territory selectors
- Cross-filtering capabilities between all visualizations

## 📋 Sample Insights (Examples)

Based on the analysis, the dashboard might reveal:
- **Top Performing Category**: Cleaning supplies account for 45% of total revenue.
- **Seasonal Peak**: Q2 sales are 30% higher than average due to spring cleaning demand.
- **Regional Champion**: The Northeast region generates 28% of total sales revenue.
- **Product Performance**: "Eco-Friendly All-Purpose Cleaner" shows the highest profit margin at 42%.
- **Growth Opportunity**: The South region shows untapped potential with 15% YoY growth.

## 🛠️ Data Modeling & DAX

The project features sophisticated data modeling:

- **Star Schema Design**: Optimized data model with fact and dimension tables
- **Calculated Measures** using DAX:
  - `Total Sales = SUM(Sales[Revenue])`
  - `YTD Sales = TOTALYTD(SUM(Sales[Revenue]), 'Date'[Date])`
  - `YoY Growth % = DIVIDE([Total Sales] - [Sales PY], [Sales PY])`
  - `Profit Margin = DIVIDE([Total Profit], [Total Revenue])`
  - `Sales per Unit = DIVIDE([Total Sales], [Total Units])`
- **Time Intelligence Functions**: For comparative period analysis
- **Dynamic Segmentation**: Classifying products based on performance tiers

## 🚀 How to Use This Project

### Prerequisites
- **Power BI Desktop** (free download from [Microsoft](https://powerbi.microsoft.com/desktop/))

### Steps to Explore:
1. **Clone or download** this repository
   ```bash
   git clone https://github.com/tanvirhasan010/Home-Care-Products-Sales-Performance-Analysis-by-Power-BI.git
   ```
2. Open the `.pbix` file in Power BI Desktop
3. Interact with the dashboard by:
   - Using slicers to filter by time period, product category, or region
   - Hovering over visualizations for detailed tooltips
   - Clicking on chart elements to cross-filter the entire report
4. Explore the Data Model (View → Model View) to understand table relationships
5. Review DAX formulas (View → Model View → click on measures)


## 📝 Project Learning Outcomes

This project demonstrates:
- End-to-end Power BI development from data ingestion to visualization
- Advanced data cleaning and transformation using Power Query
- Efficient data modeling for business intelligence
- Complex DAX formula implementation for business calculations
- Dashboard design principles for optimal user experience
- Business storytelling with data for the consumer goods industry

## 🤝 Contributing

This is a portfolio project, but feedback and suggestions are welcome! If you have ideas for improvement or find issues, please feel free to open an issue or submit a pull request.

## 📄 License

This project is intended for educational and portfolio purposes. The data used is likely a sample or synthetic dataset.

## 👨‍💻 Author

** Md Tanvir Hasan**
- GitHub: [@tanvirhasan010](https://github.com/tanvirhasan010)
- LinkedIn: https://www.linkedin.com/in/md-tanvir-hasan-scm010/


## 🙏 Acknowledgments

- Thanks to Microsoft for providing Power BI as a powerful business intelligence tool
- Inspired by real-world consumer goods and retail analytics challenges
- Data source acknowledgment (if applicable)
