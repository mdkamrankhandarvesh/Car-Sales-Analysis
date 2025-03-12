# Car Sales Analysis 🚗💰

## 📌 Project Overview
This project analyzes car sales data to uncover insights on **top-selling models, dealer performance, and profit trends over time**. The dataset includes car models, dealers, sales quantity, and profits. This analysis was done as part of my **IBM Data Analyst Certification (Coursera)**.

## 📂 Dataset Information
- **File Name:** `CarSalesByModelEnd.xlsx`
- **Sheets Overview:**
  1. **`data`** – Contains raw sales data with columns:
     - `Year`, `Month`, `Date`, `Model`, `Dealer ID`, `Quantity Sold`, `Profit`
  2. **`Task-1`** – Total **Quantity Sold** by dealer
  3. **`Task-2`** – Total **Profit** by car model
  4. **`Task-3`** – Total **Profit** by dealer
  5. **`Task-4`** – Best-selling models & their profits
  6. **`TOP MODELS`** – Highlights the most profitable models
  7. **`PROFIT OVER TIME`** – Shows profit trends from **2021 to 2023**

## 🔍 Key Insights
### 🚀 Top-Selling Models
- **Beaufort** is the most profitable model with **₹13.2M** in sales.
- **Hudson** follows closely with **₹11.5M** in sales.
- **Champlain** ranks third with **₹6.6M** in total profit.

### 📈 Yearly Profit Trends
- **2021:** ₹15.2M
- **2022:** ₹16.1M
- **2023:** ₹16.9M (**highest recorded profit**)
- The trend indicates a **steady increase in profit each year**.

### 🏆 Dealer Performance
- Dealer **1215** generated the highest profit (**₹8.1M**).
- Dealer **1217** follows closely with **₹7.7M**.
- The **bottom 10% of dealers** contributed less than **5%** of total sales, indicating room for improvement.

## 📊 Visualizations & Analysis
You can use **Excel, Python (Pandas, Matplotlib, Seaborn), or Tableau** to create visualizations such as:
- **Bar Chart** 📊 – Top 5 best-selling models
- **Line Graph** 📈 – Profit trends over time
- **Pie Chart** 🥧 – Sales share by dealer

## 🛠 How to Use This Dataset
1. **Load it into Python:**
   ```python
   import pandas as pd
   df = pd.read_excel('CarSalesByModelEnd.xlsx', sheet_name='data')
   print(df.head())
   ```
2. **Perform Exploratory Data Analysis (EDA)**
3. **Create visualizations** to highlight trends and key insights

## 🚀 How to Contribute
- **Fork this repository** and add more insights
- **Submit a pull request** with new visualizations or analysis

## 🔗 Links
- **LinkedIn Post:** [Insert Link]
- **GitHub Repository:** [Insert Link]

---

📢 **Follow me for more data analytics projects!**

#DataAnalytics #Excel #IBMDataAnalyst #CSV #CarSalesAnalysis

