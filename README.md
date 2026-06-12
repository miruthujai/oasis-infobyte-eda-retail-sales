# 🛍️ Retail Sales Data - Exploratory Data Analysis (EDA) 1

## 🏢 Internship Details
- **Organization:** Oasis Infobyte
- **Domain:** Data Analytics
- **Level:** Level 1
- **Project Number:** Project 1
- **Project Title:** EDA on Retail Sales Data

---

## 📌 What is This Project About?

In this project, I worked with a retail sales dataset.
The goal was to perform Exploratory Data Analysis (EDA)
to find hidden patterns, trends, and useful business insights
that can help a retail business make better decisions.

---

## 📁 About the Dataset

| Property | Details |
|----------|---------|
| Source | Kaggle |
| Total Rows | 1000 |
| Total Columns | 9 |
| Missing Values | None (Zero) |
| File Format | CSV |

### Column Names:
1. **Transaction ID** - Unique ID for each sale
2. **Date** - Date of the transaction
3. **Customer ID** - Unique ID for each customer
4. **Gender** - Male or Female
5. **Age** - Age of the customer
6. **Product Category** - Type of product sold
7. **Quantity** - Number of items bought
8. **Price per Unit** - Cost of one item
9. **Total Amount** - Final sale amount

---

## 🛠️ Tools and Technologies Used

| Tool | Purpose |
|------|---------|
| Python | Programming Language |
| Pandas | Data Loading and Cleaning |
| NumPy | Numerical Calculations |
| Matplotlib | Creating Charts |
| Seaborn | Beautiful Visualizations |
| Google Colab | Online Coding Platform |

---

## 📊 Steps I Performed

### Step 1 - Data Loading
- Loaded the CSV file using Pandas
- Checked the shape, columns, and data types

### Step 2 - Data Cleaning
- Checked for missing values → Found ZERO missing values
- Checked for duplicate rows → Found ZERO duplicates
- Converted Date column to proper datetime format
- Extracted Month, Year from Date column

### Step 3 - Descriptive Statistics
- Calculated Mean Sales = ₹456.0
- Calculated Median Sales = ₹135.0
- Calculated Mode Sales = ₹50
- Calculated Standard Deviation = ₹560.0
- Found Maximum Sale = ₹2000
- Found Minimum Sale = ₹25
- Total Revenue = ₹4,56,000

### Step 4 - Time Series Analysis
- Analyzed monthly sales trends
- Found which month has highest sales
- Found which month has lowest sales

### Step 5 - Customer Analysis
- Analyzed customer gender distribution
- Found spending patterns by gender
- Analyzed customer age distribution
- Found average customer age = 41.4 years

### Step 6 - Product Analysis
- Compared sales across 3 product categories
- Compared quantity sold across categories

### Step 7 - Data Visualization
Created 6 professional charts:
- Bar Chart - Sales by Product Category
- Line Chart - Monthly Sales Trend
- Pie Chart + Bar Chart - Gender Analysis
- Histogram - Age Distribution
- Heatmap - Correlation between Variables
- Horizontal Bar - Quantity by Category

### Step 8 - Business Recommendations
Provided actionable insights based on analysis

---

## 📈 Key Findings

| # | Finding |
|---|---------|
| 1 | **Total Revenue = ₹4,56,000** |
| 2 | **Electronics** generates the highest revenue |
| 3 | **Age group 25-45** are the most active buyers |
| 4 | **Seasonal trends** are clearly visible in sales |
| 5 | **Near-equal** male and female customer ratio |
| 6 | **Average** customer age is 41.4 years |

---

## 💡 Business Recommendations

1. **Focus on Electronics** - It gives maximum revenue, increase stock and marketing
2. **Target Age 25-45** - This age group buys the most, run targeted campaigns
3. **Prepare for Peak Season** - Stock up before high sales months
4. **Gender-Based Offers** - Create specific deals for male and female customers
5. **Bundle Deals** - Introduce combo offers for Clothing category

---

## 📂 Files in This Repository

| File Name | Description |
|-----------|-------------|
| `Retail_Sales_EDA.ipynb` | Main Python Jupyter Notebook with all code |
| `retail_sales_dataset.csv` | The original dataset used for analysis |
| `chart1_category_sales.png` | Bar chart - Sales by Product Category |
| `chart2_sales_trend.png` | Line chart - Monthly Sales Trend Over Time |
| `chart3_gender_analysis.png` | Pie and Bar chart - Gender Analysis |
| `chart4_age_distribution.png` | Histogram - Customer Age Distribution |
| `chart5_heatmap.png` | Heatmap - Correlation Between Variables |
| `chart6_quantity.png` | Horizontal Bar - Quantity Sold by Category |

---

## 🚀 How to Run This Project

### Option 1 - Google Colab (Recommended for Beginners)
1. Download `Retail_Sales_EDA.ipynb` from this repository
2. Go to [colab.research.google.com](https://colab.research.google.com)
3. Click **File** → **Upload notebook**
4. Upload the `.ipynb` file
5. Also upload `retail_sales_dataset.csv` to Colab files
6. Click **Runtime** → **Run all**
7. All charts will be generated automatically!

### Option 2 - Jupyter Notebook (Local)
1. Install Python on your computer
2. Install required libraries:


## 👨‍💻 About Me

- **Name:** Miruthu Jai
- **Internship:** Oasis Infobyte Data Analytics
- **LinkedIn:** https://www.linkedin.com/in/miruthujais/
- **GitHub:** https://github.com/miruthujai
