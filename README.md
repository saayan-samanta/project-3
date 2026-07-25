# E-Commerce Retail Exploratory Data Analysis (EDA)

## 📌 Project Overview

This project performs an in-depth Exploratory Data Analysis (EDA) on an e-commerce retail dataset to uncover patterns, trends, customer behavior, and business insights.

The analysis focuses on understanding sales performance, customer segments, product categories, pricing, discounts, payment methods, delivery performance, and return behavior.

---

## 🎯 Project Objective

The main objectives of this project are to:

- Understand the structure and quality of the dataset.
- Analyze customer and product-level patterns.
- Identify sales and revenue trends.
- Study customer segment behavior.
- Analyze the relationship between pricing, discounts, and order value.
- Examine payment methods and shipping performance.
- Identify important relationships between numerical and categorical features.
- Generate meaningful business insights through data visualization.

---

## 📊 Dataset Overview

The dataset contains e-commerce retail transaction records with information related to:

- Customer demographics
- Customer segments
- Product categories
- Product pricing
- Quantity purchased
- Discounts
- Payment methods
- Shipping types
- Delivery duration
- Return status

### Dataset Size

- **100,000 records**
- **18 features**

---

## 🔍 Analysis Performed

### 1. Data Understanding

- Dataset structure
- Data types
- Statistical summary
- Missing value analysis
- Duplicate value analysis

### 2. Data Cleaning

- Date format conversion
- Data type correction
- Outlier detection
- IQR-based outlier capping

### 3. Univariate Analysis

Analysis of:

- Age
- Gender
- State
- Product Category
- Customer Segment
- Payment Method
- Shipping Type
- Return Status
- Order Date

### 4. Bivariate Analysis

Relationships analyzed between:

- Product Category and Revenue
- Customer Segment and Revenue
- Payment Method and Revenue
- Shipping Type and Delivery Days
- Gender and Purchase Amount
- Return Status and Revenue
- Age and Final Price

### 5. Multivariate Analysis

Explored relationships between multiple variables using:

- Correlation Matrix
- Heatmaps
- Pivot Tables
- Scatter Plots with Hue
- Category-wise comparisons

---

## 📈 Key Insights

- **Product categories generate relatively similar revenue, with Home & Kitchen contributing slightly more.**
- **Regular customers contribute the highest revenue, followed by Premium and New customers.**
- **Both genders contribute relatively equally to the customer base and overall purchases.**
- **Grocery has the highest average discount, while Electronics has the lowest.**
- **Higher product prices and quantities generally lead to higher final order values.**
- **Product price alone does not strongly influence total quantity sold across categories.**
- **Home & Kitchen records the highest total quantity sold.**
- **Credit Card and UPI are among the most preferred payment methods.**
- **Standard and Express shipping show similar average delivery durations.**
- **Most orders are not returned, indicating generally positive customer satisfaction.**

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📂 Project Structure

```text
ecommerce-retail-eda/
│
├── data/
├── notebooks/
├── visualizations/
├── reports/
├── README.md
└── requirements.txt
