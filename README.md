# AI-Powered E-Commerce Business Analytics Platform

## 1. Project Overview

The **AI-Powered E-Commerce Business Analytics Platform** is a data analytics project designed to analyze e-commerce business data and convert raw data into meaningful business insights.

E-commerce businesses generate large amounts of data through customer purchases, product sales, marketing campaigns, payments, returns, and shipments. Analyzing this data helps businesses understand their performance, identify problems, and make better decisions.

In this project, Python is used for data loading, cleaning, validation, exploratory data analysis, and business analysis. Power BI is used to present important business metrics and findings through an interactive dashboard.

The project focuses on understanding customer behavior, sales performance, product profitability, and marketing effectiveness.

## 2. Project Objectives

The main objectives of this project are:

- **Sales Analysis:** Understand monthly sales and revenue trends and identify periods of high and low business performance.
- **Customer Analysis:** Analyze customer segments, spending patterns, loyalty tiers, and customer status.
- **Product Analysis:** Identify products generating the highest revenue and the highest profit.
- **Marketing Analysis:** Evaluate marketing channels and campaigns to understand which ones contribute most to revenue and return on investment.
- **Business Reporting:** Create an interactive Power BI dashboard that makes business performance easier to understand.
- **Data Quality:** Validate datasets and check for missing values, duplicate records, and data consistency before performing analysis.

## 3. Business Problem

An e-commerce company may have thousands of customers, products, orders, and marketing campaigns. However, raw data alone does not clearly explain:

- Which customer groups contribute the most revenue?
- Which products generate the highest profit?
- Which marketing channels bring in the most sales?
- How does revenue change over time?
- How many orders are delivered, cancelled, returned, or failed?
- Which customer groups may need additional engagement?

This project addresses these questions by analyzing different datasets and presenting the results in a structured and understandable format.

## 4. Technologies and Tools Used

| Technology | Purpose |
|---|---|
| Python | Main programming language for data analysis |
| Pandas | Loading, cleaning, transforming, and analyzing datasets |
| NumPy | Numerical calculations and data processing |
| Matplotlib | Creating charts and visualizations |
| Seaborn | Statistical and exploratory visualizations |
| Google Colab | Developing and executing the Python notebook |
| Power BI | Creating interactive dashboards and business reports |

## 5. Datasets Used

The project uses multiple datasets representing different parts of an e-commerce business.

| Dataset | Description |
|---|---|
| `customers.csv` | Customer information, segments, loyalty tiers, and customer status |
| `orders.csv` | Order details, dates, order status, and associated business information |
| `order_items.csv` | Products purchased in each order, quantities, revenue, costs, and profit |
| `products.csv` | Product information and product categories |
| `payments.csv` | Payment-related information |
| `returns.csv` | Information about returned products and orders |
| `shipments.csv` | Shipment and delivery-related information |
| `marketing_campaigns.csv` | Marketing campaign details, channels, and performance metrics |
| `customer_reviews.csv` | Customer feedback and review information |
| `data_dictionary.csv` | Descriptions of dataset columns and their meanings |
| `dataset_validation_report.csv` | Dataset validation results and data quality checks |

These datasets are analyzed individually and combined where appropriate to understand relationships between customers, orders, products, and marketing activities.

## 6. Project Workflow

### Step 1: Data Loading

The datasets are imported into Python using Pandas.

Each CSV file is loaded into a DataFrame so that the data can be inspected, cleaned, and analyzed.

### Step 2: Data Validation and Cleaning

Before conducting business analysis, the datasets are checked for data quality.

The validation process includes:

- Checking the number of rows and columns.
- Identifying missing values.
- Checking duplicate records.
- Verifying unique identifiers.
- Reviewing data types.
- Checking consistency in important business fields.

Data quality is important because incorrect or inconsistent records can lead to misleading business conclusions.

### Step 3: Exploratory Data Analysis (EDA)

Exploratory Data Analysis is performed to understand the structure and characteristics of the datasets.

The analysis includes:

- Descriptive statistics.
- Frequency distributions.
- Customer and order counts.
- Revenue and profit calculations.
- Trend analysis.
- Visual exploration using charts.

EDA helps identify patterns, unusual values, and important relationships before deeper business analysis.

### Step 4: Customer Analysis

Customer data is analyzed to understand customer spending behavior and purchasing patterns.

The analysis includes:

- Customer segmentation.
- Average spending by customer segment.
- Total spending by customer segment.
- Customer status distribution.
- Loyalty tier analysis.
- Average number of orders per customer.

This helps identify valuable customer groups and understand how different segments contribute to business performance.

### Step 5: Sales and Order Analysis

Order data is analyzed to understand sales performance over time.

The analysis includes:

- Monthly revenue trends.
- Delivered order analysis.
- Order status distribution.
- Comparison of sales performance across different periods.

The project distinguishes delivered revenue from other order statuses to make sales reporting more meaningful.

### Step 6: Product Performance Analysis

Product and order-item data is analyzed to understand product-level business performance.

The analysis includes:

- Total revenue by product.
- Total profit by product.
- Product sales quantities.
- Profit margin analysis.
- Identification of high-revenue and high-profit products.

Revenue and profit are evaluated separately because a product generating high sales does not necessarily generate the highest profit.

### Step 7: Marketing Performance Analysis

Marketing campaign data is analyzed to understand the performance of different marketing channels and campaign types.

The analysis includes:

- Revenue generated by marketing channels.
- Average return on investment (ROI).
- Campaign performance comparisons.
- Identification of channels and campaigns with strong business results.

This analysis can help businesses understand where marketing efforts are performing well and where further investigation may be useful.

### Step 8: Power BI Dashboard Development

The analyzed data and business metrics are presented through a Power BI dashboard.

The dashboard includes:

- Monthly delivered revenue trends.
- Customer status distribution.
- Top products by profit.
- Marketing revenue by channel.

The dashboard helps users explore business performance visually without having to examine the raw datasets directly.

## 7. Key Business Insights

The following findings were observed during the project analysis.

### Customer Insights

- Regular customers contributed the highest total spending among the analyzed customer segments.
- Premium customers had higher average spending and a higher average number of orders than Regular customers.
- The customer status analysis showed that Churned customers represented a substantial portion of the customer base.

These findings highlight the importance of understanding both customer value and customer retention.

### Sales Insights

- Organic Search generated the highest total revenue among the analyzed marketing channels.
- Delivered revenue increased during the final quarter of 2025, with December showing the highest monthly delivered revenue in the analyzed period.

These findings help demonstrate how sales performance can be evaluated across channels and time periods.

### Product Insights

- The product generating the highest revenue was not necessarily the product generating the highest total profit.
- Product profitability analysis provided a different perspective from revenue-based product ranking.

This shows why businesses should evaluate both revenue and profit when making product-related decisions.

### Marketing Insights

- Direct/App had the highest average ROI among the analyzed marketing channels.
- Retargeting campaigns had the highest average ROI among the analyzed campaign types.

These results provide useful starting points for evaluating marketing performance. They do not, by themselves, establish that increasing spending on a particular channel will improve future results.

## 8. Power BI Dashboard

The Power BI dashboard summarizes the main business findings through visualizations.

It is designed to help users:

- Monitor monthly delivered revenue.
- Understand customer status distribution.
- Compare product profitability.
- Evaluate revenue generated by marketing channels.

The dashboard provides a visual overview of the business and supports data-driven decision-making.

## 9. Business Value

This project demonstrates how data analytics can support e-commerce business operations.

The analysis can help businesses:

- Understand customer purchasing behavior.
- Identify products with strong revenue and profit performance.
- Evaluate marketing channel effectiveness.
- Monitor sales trends and order outcomes.
- Identify areas that may require further investigation.
- Communicate business performance through dashboards.

The insights can support business decisions, but additional analysis and experimentation would be required before making major changes to marketing budgets, pricing, or customer retention strategies.

## 10. Project Files

The repository contains the following main project files:

- `AI_Powered_Data_Analytics.ipynb` — Python notebook containing data loading, cleaning, validation, analysis, and visualizations.
- `customers.csv` — Customer dataset.
- `orders.csv` — Order dataset.
- `order_items.csv` — Order-item dataset.
- `products.csv` — Product dataset.
- `payments.csv` — Payment dataset.
- `returns.csv` — Returns dataset.
- `shipments.csv` — Shipment dataset.
- `marketing_campaigns.csv` — Marketing campaign dataset.
- `customer_reviews.csv` — Customer reviews dataset.
- `data_dictionary.csv` — Dataset column descriptions.
- `dataset_validation_report.csv` — Data validation report.

## 11. How to Run the Project

You can run this project using Google Colab.

1. Download or clone this GitHub repository.
2. Open [Google Colab](https://colab.research.google.com/).
3. Upload `AI_Powered_Data_Analytics.ipynb` to Colab.
4. Upload the required CSV datasets when prompted by the notebook.
5. Run the notebook cells in sequence.
6. Review the analysis results, visualizations, and business insights.

The notebook uses Python libraries such as Pandas, NumPy, Matplotlib, and Seaborn.

## 12. Future Improvements

Possible future enhancements include:

- Developing customer churn prediction models.
- Building a customer segmentation model using machine learning.
- Creating an AI-powered interface for asking questions about business data in natural language.
- Automating data refresh and dashboard updates.
- Adding predictive sales forecasting.
- Improving marketing campaign analysis with more detailed attribution methods.

These improvements could extend the project from descriptive analytics toward predictive and AI-assisted business analytics.

## 13. Author

**Utkarsha Mushre**

Master of Computer Applications (MCA)

Interested in Data Analytics, Business Intelligence, Python, Machine Learning, and AI-powered analytics.

---

*This project was developed for learning and portfolio purposes to demonstrate data analysis, business intelligence, and data-driven problem-solving skills.*

