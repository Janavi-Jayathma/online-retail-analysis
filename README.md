# 🛒 Online Retail Data Analysis

An end-to-end **Exploratory Data Analysis (EDA)** project using the [UCI Online Retail Dataset](https://archive.ics.uci.edu/ml/datasets/online+retail) to uncover patterns in customer behavior, product performance, and sales trends.  
This analysis uses **Python, Pandas, and Matplotlib** to clean, explore, and visualize the dataset.

---

## 📘 Table of Contents
- [Project Overview](#project-overview)
- [Dataset Information](#dataset-information)
- [Objectives](#objectives)
- [Tools and Libraries](#tools-and-libraries)
- [Steps in the Analysis](#steps-in-the-analysis)
- [Key Insights](#key-insights)
- [How to Run](#how-to-run)
- [Visualizations](#visualizations)
- [RFM Analysis](#rfm-analysis)
- [Customer Churn Analysis](#customer-churn-analysis)
- [Future Improvements](#future-improvements)
- [Author](#author)
- [License](#license)

---

## 📂 Project Overview
The **Online Retail Dataset** contains all the transactions occurring between **01/12/2010 and 09/12/2011** for a UK-based online store.  
It includes product details, quantities, prices, and customer information.  

In this project, we:
- Perform **data cleaning and preprocessing**
- Engineer new features (e.g., `TotalPrice`)
- Analyze **sales trends**, **top countries**, and **top products**
- Perform **RFM (Recency, Frequency, Monetary)** segmentation
- Analyze **customer churn** patterns

---

## 📊 Dataset Information

**Source:** [UCI Machine Learning Repository – Online Retail Dataset](https://archive.ics.uci.edu/ml/datasets/online+retail)  
**File:** `Online Retail.xlsx`

| Column | Description |
|--------|--------------|
| InvoiceNo | Invoice number (unique ID) |
| StockCode | Product (item) code |
| Description | Product description |
| Quantity | Number of items per transaction |
| InvoiceDate | Date and time of the transaction |
| UnitPrice | Price per unit |
| CustomerID | Unique customer identifier |
| Country | Country of the customer |

---

## 🎯 Objectives

1. Clean and preprocess the dataset.  
2. Identify top-selling countries and products.  
3. Visualize monthly sales patterns.  
4. Segment customers using **RFM Analysis**.  
5. Analyze **customer churn** behavior.  

---

## 🧰 Tools and Libraries

- **Python 3.10+**
- **Pandas** – Data manipulation  
- **Matplotlib / Seaborn** – Visualization  
- **NumPy** – Numerical calculations  
- **OpenPyXL** – Reading Excel files  
- **Jupyter Notebook / Google Colab**

Install dependencies:
```bash
pip install pandas numpy matplotlib openpyxl
