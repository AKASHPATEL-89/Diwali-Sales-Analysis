# 📊 Diwali Sales Analysis

An end-to-end data analytics project that explores customer purchasing behavior during Diwali. The project includes **data cleaning and exploratory data analysis using Python** and a **Power BI dashboard** for interactive business insights.

## 📌 Project Overview

The objective of this project is to analyze Diwali sales data and identify important customer segments, purchasing patterns, product performance, geographical trends, and occupation-wise spending.

The dataset contains **11,251 customer records** with information such as gender, age, marital status, state, occupation, product category, orders, and purchase amount. After cleaning missing values and removing unused columns, **11,239 records** were used for analysis.

## 🎯 Objectives

- Clean and prepare raw sales data.
- Analyze customer demographics and purchasing behavior.
- Identify high-performing product categories.
- Compare sales and orders across different states.
- Analyze purchasing patterns by gender and age group.
- Study occupation-wise customer spending.
- Build an interactive Power BI dashboard for business insights.

## 📂 Project Structure

```text
Diwali-Sales-Analysis/
│
├── Diwali Sales Data.csv
├── Diwali_Sales_Analysis.ipynb
├── Diwali Sales Analysis.pdf
└── README.md
```

## 🧹 Data Cleaning

The following preprocessing steps were performed:

- Loaded the CSV dataset using Pandas.
- Removed unrelated or blank columns:
  - `Status`
  - `unnamed1`
- Checked for missing values.
- Removed rows containing null values.
- Converted the `Amount` column to integer format.
- Prepared the cleaned data for exploratory analysis and visualization.

## 📊 Dataset Features

| Column | Description |
|---|---|
| User_ID | Unique customer identifier |
| Cust_name | Customer name |
| Product_ID | Product identifier |
| Gender | Customer gender |
| Age Group | Customer age category |
| Age | Customer age |
| Marital_Status | Marital status |
| State | Customer state |
| Zone | Geographic zone |
| Occupation | Customer occupation |
| Product_Category | Product category |
| Orders | Number of orders |
| Amount | Purchase amount |

## 📈 Key Metrics

| Metric | Value |
|---|---:|
| Cleaned Records | 11,239 |
| Unique Customers | 3,752 |
| Total Orders | 27,981 |
| Total Sales Amount | ₹106.25M |

## 🔍 Key Insights

- Female customers generated higher sales than male customers.
- The **Food** category generated the highest sales amount among product categories.
- Other major categories include **Clothing & Apparel**, **Electronics & Gadgets**, and **Footwear & Shoes**.
- Customer analysis was performed using age groups, states, occupations, and gender.
- The Power BI dashboard provides interactive views for customer, order, and sales analysis.

## 📊 Power BI Dashboard

The dashboard includes:

- Total Customers
- Total Orders
- Total Amount
- Age Group slicer
- Age Group by State
- Age Group by Occupation
- Age Group by Gender
- Orders by State
- Orders by Product Category
- Product Category by Gender
- Occupation-wise sales analysis

## 🛠️ Technologies Used

- **Python**
- **Jupyter Notebook**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Microsoft Power BI**

## 🚀 How to Run

### Python Analysis

1. Clone the repository.
2. Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn
```

3. Open `Diwali_Sales_Analysis.ipynb` using Jupyter Notebook.
4. Run the cells to perform data cleaning, analysis, and visualization.

### Power BI Dashboard

Open the Power BI project/dashboard file in **Microsoft Power BI Desktop** and refresh the data source if required.

## 📸 Dashboard Preview

The repository includes `Diwali Sales Analysis.pdf`, which contains the Power BI dashboard preview.

## 📌 Future Improvements

- Add a `.pbix` Power BI source file.
- Add dashboard screenshots in an `images/` folder.
- Add more DAX measures and KPIs.
- Publish the dashboard using Power BI Service.
- Add advanced customer segmentation and forecasting.

## 👨‍💻 Author

**Akash Singh**

If you found this project useful, consider giving the repository a ⭐.
