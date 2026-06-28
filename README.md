#  Swiggy Sales Data Analysis

##  Project Overview

This project focuses on analyzing Swiggy food order data to understand customer ordering patterns, restaurant performance, sales trends, and revenue distribution. The analysis was performed using Python in Jupyter Notebook with the help of popular data analysis and visualization libraries.

The goal of this project is to transform raw food delivery data into meaningful business insights that can help improve decision-making.

---

##  Dataset

The dataset contains information related to Swiggy food orders, including:

* Order Date
* State
* City
* Restaurant Name
* Location
* Food Category
* Dish Name
* Price (INR)
* Rating
* Rating Count

---

## 🛠️ Tools & Libraries Used

* Python
* Pandas
* NumPy
* Matplotlib
* Plotly
* RapidFuzz
* Jupyter Notebook

---

## 📊 Project Workflow

### 1. Data Loading

* Imported the dataset from an Excel file.
* Loaded the data into a Pandas DataFrame.

### 2. Data Cleaning

* Checked dataset dimensions.
* Identified missing values.
* Removed duplicate records.
* Standardized column names.
* Formatted state names for consistency.

### 3. Exploratory Data Analysis (EDA)

Performed detailed analysis on:

* Number of states and cities
* Restaurants available
* Food categories
* Popular dishes
* Dataset summary and statistics

---

##  Key Performance Indicators (KPIs)

The notebook calculates several important business metrics, including:

* Total Sales
* Average Rating
* Average Order Value
* Median Order Value
* Total Rating Count
* Total Orders

---

##  Visualizations

The project includes multiple visualizations to better understand the data:

* Monthly Sales Trend
* Daily Sales Trend
* Revenue by State
* Top 5 Cities by Sales
* Quarterly Performance Summary
* Veg vs Non-Veg Revenue Distribution
* Food Category Analysis
* Price Distribution
* Box Plot for Outlier Detection

---

##  Food Classification

One interesting part of this project is classifying dishes into:

* Veg
* Non-Veg

This was done using keyword matching and fuzzy string matching with the RapidFuzz library, making the classification more flexible and accurate.

---

##  Insights Generated

Some of the insights that can be obtained from this analysis include:

* Sales trends over time
* Highest revenue-generating states and cities
* Customer ordering behavior across weekdays
* Revenue contribution of vegetarian and non-vegetarian food
* Restaurant and dish popularity
* Quarterly business performance
* Detection of unusual pricing using outlier analysis

---

##  Conclusion

This project demonstrates a complete data analysis workflow, starting from data cleaning and preprocessing to visualization and business insight generation. It showcases how Python can be used to analyze real-world food delivery data and uncover trends that support better business decisions.

---

##  Author

**Muhammad Yasir Masood**

If you found this project helpful, feel free to explore, modify, and build upon it for your own learning or portfolio.
