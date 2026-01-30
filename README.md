# Sales & Profit Analysis Dashboard (Power BI)

## Project Overview
This academic dashboard project was developed using the dataset provided by our professor as part of a learning exercise in **data visualization and interactive reporting using Power BI**.  
The primary objective of the project is to analyze **Sales and Profit performance** across multiple business dimensions while demonstrating the effective use of **Bookmarks and Action Buttons**.

The dashboard is designed to switch dynamically between **Sales** and **Profit** views, enabling users to explore different business perspectives within the same report layout.

![Preview](https://github.com/ommkunn/Sales-Profit-Analysis-Dashboard-Power-BI-/blob/main/0130.gif)

---

## Learning Objectives
- Understand the use of **Power BI bookmarks** for view switching
- Implement **action buttons** for interactive navigation
- Apply data modeling concepts on a given academic dataset
- Design clean and intuitive dashboards for analytical storytelling
- Analyze sales and profitability across time, region, category, and products

---

## Dataset
- **Source:** Provided by professor (academic dataset)
- **Nature:** Sample retail business data
- **Key Fields Used:**
  - Order Date (Year-wise analysis)
  - Sales
  - Profit
  - Quantity
  - Discount
  - Category & Sub-Category
  - Product Name
  - Region
  - Segment
  - Ship Mode

---

## Dashboard Structure

### 1. Sales Dashboard (Bookmark: `Sales`)
**Key KPIs**
- Total Sales
- Average Discount
- Total Orders
- Total Quantity
- Count of Ship Modes

**Visualizations**
- Sum of Sales by Year (Line Chart)
- Sum of Sales by Region (Bar Chart)
- Sales by Category and Sub-Category (Treemap)
- Sales by Product Name (Column Chart)

**Filters / Slicers**
- Customer Name
- Product Name
- Segment
- Region
- Year Range (2016–2019)

![Sales Preview](https://github.com/ommkunn/Sales-Profit-Analysis-Dashboard-Power-BI-/blob/main/Sales.png)

---

### 2. Profit Dashboard (Bookmark: `Profit`)
**Key KPIs**
- Total Profit
- Profit Margin %
- Profit per Unit
- Loss Orders
- Total Sales (Reference KPI)

**Visualizations**
- Profit by Region (Donut Chart)
- Profit by Sub-Category (Bar Chart)
- Sales vs Profit vs Quantity by Category & Sub-Category (Bubble Chart)

**Filters / Slicers**
- Product Name
- Segment
- Region
- Year Range (2016–2019)

![Profit](https://github.com/ommkunn/Sales-Profit-Analysis-Dashboard-Power-BI-/blob/main/Profit.png)

---

## Interactivity & Navigation
- **Bookmarks Used:**  
  - `Sales` – Displays all sales-related visuals  
  - `Profit` – Displays all profit-related visuals  

- **Action Buttons:**  
  - Sales Button → Navigates to Sales bookmark  
  - Profit Button → Navigates to Profit bookmark  

This approach ensures a **single-page interactive dashboard** with clean navigation and reduced clutter.

---

## Tools & Technologies
- **Power BI Desktop**
- DAX (for calculated measures)
- Bookmarks & Selection Pane
- Action Buttons
- Academic sample dataset

---

## Academic Purpose
This project is created **strictly for educational and learning purposes**.  
It demonstrates practical implementation of Power BI concepts taught in class, focusing on:
- Business analytics
- Dashboard design principles
- Interactive reporting techniques

---

## Key Takeaways
- Bookmarks enhance user experience without duplicating report pages
- Action buttons make dashboards intuitive and presentation-ready
- Separating Sales and Profit views improves analytical clarity
- Consistent design improves readability and academic evaluation

---

## Author
**Bishwarup**  
Business Analytics Student  
Academic Power BI Project
