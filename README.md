# 🛒 E-Commerce Sales Analysis

## 📌 Project Overview

This project analyzes e-commerce transaction data to understand
sales performance, customer behavior, product performance,
geographic sales, purchasing patterns, and cancellations.

The analysis was performed using Python and popular data analysis
and visualization libraries.

---

## 🎯 Objectives

- Analyze overall sales performance
- Identify top-performing products
- Analyze customer purchasing behavior
- Identify high-value customers
- Compare sales across countries
- Analyze monthly and daily sales trends
- Analyze order values and purchase frequency
- Examine cancellations and returns
- Perform RFM customer analysis
- Generate actionable business recommendations

---

## 🛠️ Tools & Technologies

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📊 Dataset

The project uses the Online Retail dataset containing transactional
data from a UK-based online retailer.

The dataset includes information such as:

- Invoice Number
- Product Code
- Product Description
- Quantity
- Invoice Date
- Unit Price
- Customer ID
- Country

---

## 🔍 Analysis Performed

### Data Cleaning
- Removed duplicate records
- Identified cancelled transactions
- Checked invalid quantities
- Checked invalid prices
- Converted columns to appropriate data types
- Handled missing customer information

### Feature Engineering
- Calculated sales revenue
- Extracted year, month, day, and hour
- Created day-of-week information

### Exploratory Data Analysis
- Total sales
- Total quantity sold
- Total orders
- Top products
- Top countries
- Monthly sales
- Customer purchase frequency
- Average Order Value

### Customer Analysis
- One-time vs repeat customers
- Customer revenue
- RFM analysis

### Visualization
- Monthly sales trend
- Top products by sales
- Top countries by sales
- Sales by day
- Sales by hour
- Top customers
- Order value distribution
- Quantity vs sales
- Cancellation analysis

---

## 💡 Key Insights

- November 2011 recorded the highest monthly sales.
- The United Kingdom generated the highest sales.
- A relatively small number of products generated a large share
  of revenue.
- Customer revenue was concentrated among high-value customers.
- Repeat customers represent an important source of recurring revenue.
- RFM analysis helps identify valuable and engaged customers.
- Cancellation patterns should be monitored to identify potential
  business issues.

---

## 📈 Business Recommendations

1. Focus on high-value customers through loyalty programs and
   personalized offers.
2. Encourage one-time customers to make repeat purchases.
3. Promote high-performing products.
4. Investigate cancellation and return patterns.
5. Explore opportunities in promising international markets.
6. Prepare inventory and marketing strategies for high-sales periods.

---

## 🏁 Conclusion

This project demonstrates how Python-based data analysis can be
used to transform raw e-commerce transaction data into meaningful
business insights.

The analysis covers data cleaning, feature engineering,
exploratory data analysis, visualization, customer analysis,
RFM analysis, and business recommendations.

---

## 👨‍💻 Author

**Aziz Ahmad Khan**

BS Computer Science | Aspiring Data Analyst

---
## 📁 Project Structure

```text
Ecommerce_Sales_Analysis/
│
├── data/
│   └── Online Retail.xlsx
│
├── notebooks/
│   └── Ecommerce_Sales_Analysis.ipynb
│
├── visualizations/
│   ├── monthly_sales_trend.png
│   ├── top_products_by_sales.png
│   ├── top_countries_by_sales.png
│   └── ...
│
├── reports/
│
├── README.md
└── requirements.txt