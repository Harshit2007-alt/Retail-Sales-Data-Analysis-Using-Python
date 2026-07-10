# 📊 Retail Sales Data Analysis Using Python

## 📌 Project Overview

This project analyzes Walmart retail sales data using Python. The goal is to clean the data, perform exploratory data analysis (EDA), answer important business questions, and visualize sales trends to generate meaningful business insights.

The project combines multiple datasets, performs feature engineering, and creates various charts to understand store performance, sales trends, holiday impact, and relationships between different business variables.

---

# 🎯 Project Objectives

- Clean and preprocess retail sales data.
- Merge multiple datasets into a single dataset.
- Perform Exploratory Data Analysis (EDA).
- Create new date-based features for better analysis.
- Answer real-world business questions.
- Visualize sales trends using Python.
- Generate business insights from the data.

---

# 📂 Dataset Information

The project uses three datasets:

### 1. Sales Dataset
Contains weekly sales information for different stores and departments.

### 2. Stores Dataset
Contains information about:
- Store Number
- Store Type
- Store Size

### 3. Features Dataset
Contains additional information such as:
- Temperature
- Fuel Price
- CPI
- Unemployment
- Holiday Information

---

# 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

# 📚 Python Libraries

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
```

---

# 🔄 Project Workflow

## Step 1 : Import Libraries

Imported all required Python libraries for data analysis and visualization.

---

## Step 2 : Load Datasets

Loaded:

- Sales Data
- Stores Data
- Features Data

---

## Step 3 : Data Exploration (EDA)

Performed:

- View first records
- Check dataset shape
- Check data types
- Identify missing values
- Check duplicate records
- View statistical summary

---

## Step 4 : Data Cleaning

Performed:

- Removed duplicate records
- Converted Date column into datetime format
- Checked missing values

---

## Step 5 : Merge Datasets

Merged all datasets using common columns such as:

- Store
- Date
- IsHoliday

to create one final dataset.

---

## Step 6 : Feature Engineering

Created new columns from Date:

- Year
- Month
- Month Number
- Quarter
- Week
- Day Name

These features help perform better business analysis.

---

# 📊 Business Analysis Questions

## 1. Which store has the highest sales?

Purpose:
Identify the best-performing stores based on total weekly sales.

Visualization:
Bar Chart

---

## 2. How do sales change over time?

Purpose:
Analyze sales trends across different dates.

Visualization:
Line Chart

---

## 3. Which month has the highest sales?

Purpose:
Compare monthly sales performance.

Visualization:
Bar Chart

---

## 4. Do holidays increase sales?

Purpose:
Compare holiday and non-holiday sales.

Visualization:
Bar Chart

---

## 5. Which store type performs best?

Purpose:
Compare sales performance among Store Type A, B and C.

Visualization:
Bar Chart

---

## 6. Does store size affect sales?

Purpose:
Understand the relationship between store size and weekly sales.

Visualization:
Scatter Plot

---

## 7. Does temperature affect sales?

Purpose:
Analyze whether temperature impacts weekly sales.

Visualization:
Scatter Plot

---

## 8. Which variables have the strongest relationship?

Purpose:
Analyze correlation among numerical variables.

Visualization:
Heatmap

---

## 9. Detect sales outliers

Purpose:
Find unusually high or low sales values.

Visualization:
Box Plot

---

## 10. Understand sales distribution

Purpose:
Understand how weekly sales are distributed.

Visualization:
Histogram

---

# 📈 Visualizations Used

- Line Chart
- Bar Chart
- Scatter Plot
- Histogram
- Heatmap
- Box Plot

---

# 📌 Key Insights

- Identified top-performing stores.
- Analyzed overall sales trends.
- Compared holiday vs non-holiday sales.
- Identified the highest sales months.
- Compared different store types.
- Studied the impact of store size on sales.
- Studied the effect of temperature on sales.
- Identified correlations between business variables.
- Detected outliers in weekly sales.
- Understood overall sales distribution.

---

# 📂 Project Structure

```
Retail-Sales-Analysis
│
├── Retail_Sales_Analysis.ipynb
├── Sales.csv
├── Stores.csv
├── Features.csv
├── README.md
```

---

# 🚀 Skills Demonstrated

- Data Cleaning
- Data Preprocessing
- Data Merging
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Business Analysis
- Data Visualization
- Python Programming
- Statistical Analysis

---

# 💼 Business Value

This project demonstrates how Python can be used to transform raw retail sales data into meaningful business insights. The analysis helps businesses understand customer purchasing behavior, identify top-performing stores, analyze seasonal sales trends, evaluate holiday performance, and support data-driven decision-making.

---

# 📌 Future Improvements

- Build an interactive Power BI Dashboard.
- Create predictive sales forecasting models.
- Perform customer segmentation.
- Build an automated sales reporting system.

---

# 👨‍💻 Author

**Harshit Bhatia**

Aspiring Data Analyst

### Skills

- Python
- SQL
- Power BI
- Advanced Excel
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## ⭐ If you found this project helpful, don't forget to star the repository!
