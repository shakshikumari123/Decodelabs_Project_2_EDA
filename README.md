# E-Commerce Sales and Customer Analysis

## 📌 Project Overview

This project focuses on performing Exploratory Data Analysis (EDA) on an e-commerce dataset containing 1,200 orders.

The objective is to understand sales patterns, product performance, customer purchasing behavior, payment preferences, order statuses, referral sources, coupon usage, temporal trends, outliers, and relationships between numerical variables.

The analysis was performed using Python in Google Colab with Pandas, NumPy, Matplotlib, and Seaborn.

---

## 🎯 Objectives

- Understand the structure and quality of the dataset.
- Perform data cleaning and validation.
- Analyze numerical and categorical variables.
- Identify sales and order trends over time.
- Compare product performance.
- Analyze payment method preferences.
- Study order status distribution.
- Analyze customer purchasing behavior.
- Detect outliers.
- Study correlations between numerical variables.
- Extract meaningful business insights.

---

## 📊 Dataset

The dataset contains:

- **1,200 rows**
- **14 columns**
- Date range: **January 1, 2023 – June 30, 2025**

### Columns

| Column | Description |
|---|---|
| OrderID | Unique identifier for each order |
| Date | Order date |
| CustomerID | Customer identifier |
| Product | Product purchased |
| Quantity | Number of units purchased |
| UnitPrice | Price per unit |
| ShippingAddress | Shipping address |
| PaymentMethod | Payment method used |
| OrderStatus | Current order status |
| TrackingNumber | Shipment tracking identifier |
| ItemsInCart | Number of items in cart |
| CouponCode | Coupon applied |
| ReferralSource | Customer referral source |
| TotalPrice | Total value of the order |

---

## 🛠️ Tools & Technologies

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 🔍 Analysis Performed

### 1. Data Understanding

- Dataset shape
- Column names
- Data types
- Date range
- Numerical and categorical variables

### 2. Data Quality Analysis

- Missing value detection
- Duplicate row detection
- Duplicate OrderID detection
- Duplicate TrackingNumber detection
- Unique value checks
- Text formatting checks

### 3. Descriptive Statistics

Calculated:

- Count
- Mean
- Median
- Standard deviation
- Minimum
- Maximum
- Quartiles

### 4. Outlier Detection

The Interquartile Range (IQR) method was used to identify potential outliers.

- Quantity: 0
- UnitPrice: 0
- ItemsInCart: 0
- TotalPrice: 8

The detected TotalPrice outliers were investigated and retained because they represented legitimate high-value orders.

### 5. Categorical Analysis

Analyzed:

- Product
- Payment Method
- Order Status
- Coupon Code
- Referral Source

### 6. Time-Based Analysis

Analyzed:

- Monthly order trends
- Year-wise order counts
- Year-wise total order value
- Year-wise average order value

### 7. Product Analysis

Compared products using:

- Order count
- Total sales
- Average order value
- Total quantity sold

### 8. Payment Analysis

Compared payment methods using:

- Order count
- Total order value
- Average order value

### 9. Customer Analysis

Analyzed:

- Number of orders per customer
- Total order value per customer
- Average order value per customer

### 10. Correlation Analysis

Examined relationships between:

- Quantity
- UnitPrice
- ItemsInCart
- TotalPrice

---

## 📈 Key Findings

### Overall

- Total Orders: **1,200**
- Total Order Value: **₹1,264,761.96**
- Average Order Value: **₹1,053.97**
- Highest Order Value: **₹3,456.40**
- Lowest Order Value: **₹11.39**

### Product

- Most ordered product: **Printer — 181 orders**
- Highest total sales: **Chair — ₹195,620.11**
- Highest quantity sold: **Chair — 562 units**
- Highest average order value: **Laptop — ₹1,110.56**

### Payment

- Most commonly used payment method: **Online — 258 orders**
- Highest total order value: **Credit Card — ₹263,847.63**
- Highest average order value: **Credit Card — ₹1,127.55**

### Order Status

- Most common order status: **Cancelled — 250 orders**

### Marketing

- Most common referral source: **Instagram — 259 orders**
- Most common coupon code: **FREESHIP — 313 orders**

### Correlation

The strongest relationship with TotalPrice was:

- UnitPrice → TotalPrice: **0.717**
- Quantity → TotalPrice: **0.615**
- ItemsInCart → TotalPrice: **0.393**

---

## 💡 Business Insights

1. Product performance varies depending on the metric used. Printer had the highest order count, while Chair generated the highest total sales.
2. Credit Card payments were associated with the highest total order value and average order value.
3. Online payments were the most frequently used payment method.
4. Cancelled orders were the most common order status and represented a substantial order value.
5. UnitPrice and Quantity were the strongest numerical factors associated with TotalPrice.
6. Customer activity was dominated by single-order customers.
7. Instagram was the most common referral source.
8. FREESHIP was the most frequently occurring coupon code.

> Note: TotalPrice associated with cancelled or returned orders should not automatically be interpreted as realized revenue because the dataset does not provide sufficient information to calculate actual realized revenue.

---

## 📁 Project Structure
E-Commerce-Sales-and-Customer-Analysis/
│
├── README.md
├── Problem_Statement.pdf
├── Original_Dataset.csv
├── E-Commerce_Sales_and_Customer_Analysis.ipynb
└── Project_Documentation.pdf
🚀 How to Run the Project
Clone or download this repository.
Open the Jupyter Notebook in Google Colab or Jupyter Notebook.
Upload the dataset if required.
Run the notebook cells sequentially.
Review the generated statistics, visualizations, and insights.

📌 Conclusion:- 
This project demonstrates how Exploratory Data Analysis can be used to transform raw e-commerce data into meaningful insights.

The analysis provides an understanding of product performance, sales behavior, payment preferences, order statuses, customer activity, marketing sources, and numerical relationships.

Python-based EDA techniques were used throughout the project to validate the dataset, discover patterns, visualize trends, identify outliers, and generate business-oriented conclusions.


👩‍💻 Author
Shakshi Kumari
