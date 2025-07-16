# E-commerce Sales Dashboard

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Dataset](#dataset)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Installation & Setup](#installation--setup)
- [Insights](#insights)

---

## Project Overview

This project presents a comprehensive **E-commerce Sales Dashboard** developed using Python and Jupyter Notebook. The goal is to perform **exploratory data analysis (EDA)** and generate **insights** from e-commerce transaction data to help businesses understand:

- Sales performance across time, regions, and product categories
- Customer segmentation and purchasing patterns
- Key business metrics and KPIs

The dashboard provides clear and insightful **data visualizations** that enable decision-makers to identify trends, outliers, and business opportunities.

---

##  Features

-  Data Cleaning and Preprocessing
-  Sales Trend Analysis (Monthly, Category-wise, Region-wise)
-  Regional and Country-wise Performance Evaluation
-  Customer Demographics & Segmentation
-  Visual Representation using Matplotlib, Seaborn, and Plotly
-  Key Metrics: Total Sales, Avg. Order Value, Repeat Customers
-  Heatmaps, Bar Charts, Line Graphs, Pie Charts
-  Actionable Business Insights

---

## Dataset

The dataset used for this project contains real e-commerce transaction data and includes the following fields:

- `Order ID`
- `Product Name`, `Category`, `Sub-Category`
- `Order Date`, `Ship Date`
- `Region`, `Country`, `City`
- `Customer Segment`
- `Sales`, `Profit`, `Quantity`, `Discount`

 **Download the dataset from Google Drive**:  
[E-commerce Dataset (Google Drive)](https://drive.google.com/file/d/172vPzfW_O00aU92OW08_OxhTwu3nQbQD/view?usp=sharing)

> Once downloaded, place the file inside the `data/` directory of this project and rename if needed (e.g., `ecommerce_sales_data.xlsx`).


---

##  Technologies Used

- **Programming Language:** Python
- **Data Manipulation:** `pandas`, `numpy`
- **Data Visualization:** `matplotlib`, `seaborn`, `plotly`
- **IDE:** Jupyter Notebook
- **Optional:** `openpyxl` for Excel file handling

---

## Project Structure
.
├── Data_Analytics_Project_E_commerce_Sales_Dashboard.ipynb
├── README.md
├── requirements.txt
└── data/
    └── ecommerce_sales_data.xlsx   <-- (From Google Drive)
##  Installation & Setup

Follow these steps to set up the project on your local machine:

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/ecommerce-sales-dashboard.git
   cd ecommerce-sales-dashboard
2. Install Required Libraries
    pip install -r requirements.txt
3. Launch Jupyter Notebook
     jupyter notebook
   
##  Insights 

Some of the key insights derived from the dataset include:

-  **Sales peaked during November and December**, suggesting strong seasonal demand.
-  **Western and Central US regions** outperformed other regions in terms of both sales and profit.
-  **Corporate and Consumer segments** generated the most revenue.
-  High discount levels negatively impacted overall profit margins.
-  Certain sub-categories, despite high sales volume, had negative profit trends.
