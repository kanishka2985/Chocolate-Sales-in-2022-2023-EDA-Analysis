# 🍫 Chocolate Sales Analysis (2022–2023)

> Exploratory Data Analysis (EDA) project to analyze chocolate sales performance and generate business insights using Python.

---

## 📖 Table of Contents
- [Project Overview](#-project-overview)
- [Business Objective](#-business-objective)
- [Dataset Information](#-dataset-information)
- [Data Wrangling](#-data-wrangling)
- [Exploratory Data Analysis](#-exploratory-data-analysis)
- [Key Insights](#-key-insights)
- [Business Recommendations](#-business-recommendations)
- [Tech Stack](#-tech-stack)
- [Project Outcome](#-project-outcome)

---

# 📌 Project Overview

This project analyzes **Chocolate Sales Data (2022–2023)** to evaluate business performance and identify factors influencing revenue growth.

The analysis includes:

✔ Country-wise sales performance  
✔ Sales channel analysis  
✔ Salesperson performance  
✔ Pricing and discount behavior  
✔ Marketing spend analysis  
✔ Seasonal and time-based trends  
✔ Correlation and relationship analysis  

The project converts raw sales records into meaningful business insights for better decision-making.

---

# 🎯 Business Objective

The objective of this project is to:

- Increase overall sales revenue
- Identify top and low-performing markets
- Optimize pricing and discount strategies
- Improve marketing effectiveness
- Analyze seasonal demand patterns
- Support data-driven business decisions
- Achieve long-term business growth

---

# 📂 Dataset Information

Dataset contains sales transaction records including:

| Feature |
|----------|
| Order Date |
| Country |
| Salesperson |
| Sales Channel |
| Amount |
| Discount Percentage |
| Price per Box |
| Marketing Spend |
| Boxes Shipped |

### Dataset After Cleaning

Rows: **198,397**  
Columns: **11**

---

# 🧹 Data Wrangling & Preprocessing

Data preprocessing was performed to ensure the dataset was clean, structured, and ready for analysis. This process improved data quality, ensured consistency, and enabled accurate business insights.

---

## 1. Missing Value Handling
Missing or incomplete records were removed from the dataset to maintain data accuracy and eliminate inconsistencies that could affect analysis results.

---

## 2. Date Conversion
The order date field was standardized into a proper date format to support time-based analysis. This enabled extraction of yearly, monthly, daily, and weekly sales trends.

---

## 3. Sales Amount Cleaning
Sales values were cleaned by removing currency formatting and converting them into numerical values. This allowed accurate calculations, aggregations, and visualizations.

---

## 4. Feature Engineering
Additional time-related features were created from the order date to enhance analysis and identify trends.

Generated features included:

- **Order Year** → Analyze yearly sales performance  
- **Order Month** → Identify monthly trends and seasonality  
- **Order Day** → Observe day-level purchasing behavior  
- **Day of Week** → Compare weekday and weekend sales patterns  

---

## 5. Sales Category Segmentation
Sales values were segmented into three categories:

- **Low**
- **Medium**
- **High**

This categorization helped understand sales distribution and compare business performance across different sales levels.

---

### ✅ Outcome of Data Wrangling

After preprocessing:

- Improved overall dataset quality  
- Standardized date and numerical formats  
- Enabled advanced exploratory data analysis (EDA)  
- Enhanced trend detection and business insight generation  
- Prepared data for visualization and decision-making  

---

# 📊 Exploratory Data Analysis

The following visualizations were created:

| Visualization | Purpose |
|--------------|---------|
| 📈 Total Sales by Country | Compare sales performance across countries |
| 🥧 Distribution of Sales Channels | Understand contribution of Retail, Wholesale, and Online |
| 📊 Top Salespersons Analysis | Identify highest-performing salespersons |
| 📉 Total Sales by Year | Analyze yearly business growth |
| 📈 Monthly Sales Trend | Detect seasonal sales patterns |
| 🥧 Sales Category Distribution | Segment sales into Low, Medium, and High |
| 📉 Sales by Day of Week | Understand weekday sales behavior |
| 📊 Discount Distribution | Analyze discount frequency and spread |
| 📦 Price per Box Analysis | Detect pricing distribution and outliers |
| 📈 Marketing Spend Distribution | Evaluate spending patterns |
| 🔥 Correlation Heatmap | Identify relationships among variables |
| 🔍 Pair Plot Analysis | Explore multi-variable interactions |

---

# 🔍 Key Insights

## 🌍 Country Performance
- Australia generated the highest total sales.
- Brazil ranked second in overall sales performance.
- Lower-performing markets present expansion opportunities.

---

## 🛒 Sales Channels
- Retail contributed the largest share of revenue.
- Wholesale remained a significant contributor.
- Online sales showed strong growth opportunities.

---

## 📅 Time Trends
- Overall sales increased from **2022 → 2023**.
- Higher sales were observed in later months of the year.
- Weekend sales outperformed weekdays.

---

## 💰 Pricing & Discounts
- Moderate discounts were most frequently used.
- Pricing showed an impact on shipment volume.
- Extreme pricing variations may affect demand.

---

## 📣 Marketing
- Marketing spend showed a positive relationship with sales.
- Controlled spending can improve return on investment (ROI).

---

## 🚚 Operations
- Boxes shipped had a strong influence on total revenue.
- Efficient logistics can directly improve business performance.

---

# 💡 Business Recommendations

### 🌍 Market Expansion
- Expand investment in high-performing countries.
- Develop strategies for low-performing regions.

### 🛒 Sales Channel Optimization
- Strengthen online sales presence.
- Reduce dependency on retail sales.

### 💰 Pricing Strategy
- Maintain competitive pricing.
- Use discounts strategically.

### 📣 Marketing Improvements
- Increase marketing ROI through targeted campaigns.
- Focus budget allocation on high-performing channels.

### 📦 Operational Efficiency
- Improve inventory planning.
- Prepare for seasonal demand spikes.

### 📊 Data Strategy
- Continue using data-driven business decisions.

---

# 🛠 Tech Stack

| Technology | Purpose |
|-----------|---------|
| Python | Data Analysis |
| Pandas | Data Cleaning & Wrangling |
| NumPy | Numerical Computation |
| Matplotlib | Data Visualization |
| Seaborn | Statistical Visualization |
| Jupyter Notebook | Development Environment |

---

# 📈 Project Outcome

This project successfully transformed raw chocolate sales data into actionable business insights and business recommendations.

## Expected Benefits

✅ Better Revenue Planning  

✅ Improved Market Decisions  

✅ Efficient Marketing Spend  

✅ Pricing Optimization  

✅ Stronger Sales Performance  

✅ Improved Operational Efficiency  

✅ Sustainable Business Growth  

---

⭐ If you found this project useful, consider giving it a star on GitHub.
