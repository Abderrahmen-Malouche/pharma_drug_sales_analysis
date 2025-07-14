# 💊 Pharma Drug Sales Analysis (Power BI Dashboard)

This repository presents a comprehensive **Pharma Drug Sales Analysis** project conducted using **Power BI**. The project demonstrates data cleaning, transformation, and visualization of pharmaceutical sales data to uncover key business insights.

![Dashboard](https://github.com/user-attachments/assets/9a720e71-4266-4390-bc5f-ecfa0260e3cf)


---

## 📂 Project Overview

- **Objective**: To analyze drug sales data across different time frames (daily, weekly, monthly, quarterly, yearly) and categories to support business decisions.
- **Tools Used**: Power BI (Data Cleaning, DAX Measures, Visualization)
- **Dataset**: Raw CSV data consisting of drug categories, sales volumes, quantities, and timestamps.

---

## 🧹 Data Cleaning & Preparation

Performed in Power BI using Power Query:
- Removed duplicates and null values
- Formatted date and time fields
- Standardized drug category names
- Converted numeric values to proper formats
- Filtered out erroneous entries

---

## 🧮 DAX Measures & Calculations

Custom measures were created for deeper analysis:
- `Weekly Sales`
- `Total Monthly Sales`
- `Average Monthly Sales`
- `Daily Sales`
- `Yearly Sales`
- Percentage contributions by drug category

---

## 📊 Dashboard Highlights

- **KPIs**: Weekly sales, total monthly sales, average monthly sales, category counts
- **Time-Based Insights**:
  - **Weekly Sales by Category**
  - **Monthly vs Average Monthly Sales**
  - **Quarterly Sales Trend**
  - **Yearly Sales Overview**
- **Category-Based Analysis**:
  - **Daily Sales by Drug Category (Pie Chart)**
  - **Hourly Quantity Sold by Category**
- **Interactive Filters**:
  - Slicer for year selection

---

## 📁 Files Included

- `raw_data.csv` – Raw dataset (anonymized)
- `dashboard.png` – Screenshot of the final Power BI dashboard
- `README.md` – Project overview

---

## 🚀 How to Use

1. Clone or download the repository.
2. Open Power BI Desktop.
3. Load the CSV file and apply the data transformations and DAX measures as described.
4. Recreate the visuals or use the dashboard image as reference.

---

## 📌 Key Takeaways

- Highest daily sales came from category **N05B** with **~49.44%** of daily revenue.
- Sales peaked during **Q1 and Q4** and dropped in **Q2**.
- Consistent patterns in **morning sales hours** were observed across categories.
- **2015** and **2018** showed the strongest yearly sales growth.
