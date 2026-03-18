# 🛍️ Retail Sales Analytics Dashboard

## 📊 Project Overview
This project focuses on analyzing retail sales data to uncover insights related to sales performance and customer behavior.

The analysis combines **Python (EDA & feature engineering)** and **Power BI (interactive dashboard)** to support data-driven business decisions.

---

## 🎯 Objectives
- Analyze overall sales performance
- Identify top-performing products and regions
- Understand revenue contribution by sales channel
- Segment customers using RFM analysis
- Build an interactive dashboard for business monitoring

---

## 📁 Dataset
- Source: Kaggle – Retail Sales Dataset  
- Total Transactions: ~20,000  
- Total Customers: ~1,000  

### Features:
**Customer Data**
- customer_id
- age
- gender
- city

**Transaction Data**
- sale_id
- product_name
- category
- quantity
- unit_price
- sale_date

**Business Dimensions**
- region
- sales_channel

---

## ⚙️ Data Preparation
- Checked missing values → No missing values found  
- Removed duplicates → No duplicate data  
- Converted date format  
- Feature engineering:
  - Revenue = quantity × unit_price  
  - Profit & Profit Margin  
- Created RFM metrics:
  - Recency
  - Frequency
  - Monetary

---

## 📈 Exploratory Data Analysis

### Sales Performance
- Revenue trend over time
- Revenue by region
- Revenue by sales channel
- Top products by revenue

### Customer Behavior
- Age distribution
- Revenue by gender
- Top customers by revenue
- Customer segmentation (RFM)

---

## 📊 Dashboard (Power BI)

### Retail Sales Dashboard
- KPI: Revenue, Profit, Profit Margin, Transactions
- Revenue trend (monthly)
- Revenue by region
- Revenue by channel
- Top products

### Customer Insight Dashboard
- Customer segmentation (RFM)
- Top customers
- Demographic insights
- Revenue by gender

---

## 🔍 Key Insights
- Centro region contributes the highest revenue  
- Online and offline sales channels perform similarly  
- A small number of products generate most revenue  
- Many customers fall into "At Risk" segment  

---

## 💡 Business Recommendations
- Focus marketing on high-performing regions  
- Improve retention strategy for at-risk customers  
- Promote top-performing products  
- Strengthen online sales channel  

---

## 🛠️ Tools & Technologies
- Python (Pandas, NumPy, Matplotlib)
- Power BI
- Google Colab

---

## 🚀 How to Run
1. Open the notebook in Google Colab / Jupyter
2. Run EDA and data preparation
3. Load dataset into Power BI
4. Open `.pbix` file to explore dashboard

---

## 👤 Author
**Mafud Satrio Setiono**  
Data Analyst / Data Science  

- 📧 Email: riostetiono23@gmail.com  
- 🔗 LinkedIn: (isi nanti)  
- 💻 GitHub: (ini repo kamu)

---

## ⭐ Notes
This project is part of my data analyst portfolio showcasing end-to-end data analysis from raw data to dashboard visualization.
