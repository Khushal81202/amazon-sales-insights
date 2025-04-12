# 📊 Amazon Sales Report Analysis

This project presents an **exploratory data analysis (EDA)** of an Amazon sales dataset. It cleans the data, extracts key insights, and visualizes patterns in customer behavior, product sales, and logistics.

## 📁 Dataset

The dataset contains sales transaction details such as:
- Order Date
- Product Category
- Size
- Quantity
- Amount
- Courier and Fulfilment Details
- Shipping Location Info
- Buyer Type (Retail/B2B)

## 📌 Objective

To derive meaningful insights from the sales data and understand:
- Popular product categories and sizes
- Distribution of sales across states
- Courier and fulfilment preferences
- Retail vs. B2B buyer split

## 🧼 Data Cleaning

The following steps were performed:
- Removed blank/unnecessary columns
- Dropped rows with null values
- Converted data types (e.g., postal codes, date fields)
- Renamed columns for clarity

## 📊 Exploratory Data Analysis

### 📦 Product Insights
- **M-size** is the most sold product size.
- **T-shirts** are the highest selling category.

### 🚚 Courier & Fulfilment
- Majority of the orders are **shipped** through courier.
- Most orders are fulfilled by **Amazon**.

### 🛍️ Buyer Type
- **99.3%** of customers are **Retail buyers**.
- Only **0.7%** are B2B clients.

### 🌍 Regional Analysis
- Highest number of orders come from **Maharashtra**.

## 📈 Visualizations

Visual tools used:
- **Seaborn & Matplotlib**
- Countplots, Pie Charts, Histograms, Bar Charts, Scatter Plots

## 🛠️ Libraries Used

# python
pandas
numpy
matplotlib
seaborn

📌 Conclusion
This analysis shows that the business predominantly serves retail customers in Maharashtra, with T-shirts and M-size products being top sellers. Amazon fulfillment is the preferred delivery method.
