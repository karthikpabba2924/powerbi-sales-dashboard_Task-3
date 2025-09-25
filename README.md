# powerbi-sales-dashboard_Task-3
An interactive Power BI dashboard that helps business stakeholders analyze sales, profit, and customer performance, supporting better decision-making
# Task 3 – Sales Dashboard in Power BI

## 📌 Objective
Design an interactive dashboard for business stakeholders to analyze sales and profit performance using Power BI.

---

## 🗂 Dataset
- Source: [Superstore Dataset (Kaggle)](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)
- File Used: `Superstore.csv`
- Key Columns: Order Date, Sales, Profit, Quantity, Category, Segment, Region, Customer Name, Ship Mode

---

## 🛠 Tools Used
- Power BI Desktop
- GitHub (for submission)
- Microsoft PowerPoint (for summary)

---

## 🔑 Steps Followed

### 1. Data Import
- Downloaded `Superstore.csv` from Kaggle.
- Loaded into Power BI via **Home → Get Data → Text/CSV**.

### 2. Data Preparation
- Verified data types:
  - Order Date → Date
  - Sales, Profit, Quantity → Numeric
  - Category, Region, Segment → Text
- Created additional columns:
  ```DAX
  Year = YEAR('Superstore'[Order Date])
  Month = FORMAT('Superstore'[Order Date], "MMMM")
  Quarter = "Q" & FORMAT('Superstore'[Order Date], "Q")

3. Dashboard Visuals

KPIs (Cards):

Total Sales (SUM of Sales)

Total Profit (SUM of Profit)

Total Orders (COUNT of Order ID)

Total Quantity (SUM of Quantity)

![t2](https://github.com/user-attachments/assets/c10735b9-a6e3-4e90-9133-2ab81dc7ebc9)
Charts:

Sales Over Time → Line Chart (Order Date vs Sales)

Profit by Category → Column Chart

Sales by Region → Map / Bar Chart

Top 10 Customers by Sales → Bar Chart (filtered Top N = 10)

Filters (Slicers):

Year

Region

Category

Segment

4. Formatting

Applied consistent theme.

Added titles to all visuals.

Organized layout:

Top → KPI Cards

Middle → Sales Trend + Profit by Category

Bottom → Region Sales + Top 10 Customers

Right → Slicers

📂 Repository Contents

Superstore.csv → Dataset

Task4_Dashboard.pbix → Power BI dashboard file

Screenshots/ → PNG images of dashboard

Summary_PPT.pptx → Short presentation with screenshots

README.md → This file[2.pdf](https://github.com/user-attachments/files/22535145/2.pdf)




















[Sample - Superstore.csv](https://github.com/user-attachments/files/22535063/Sample.-.Superstore.csv)
