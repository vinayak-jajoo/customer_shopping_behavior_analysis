# Customer Shopping Behavior Analysis

## Project Overview

This project analyzes customer shopping behavior using transactional data to uncover insights into purchasing patterns, customer segments, and product preferences. The objective is to support data-driven business decisions through structured analysis and visualization.

---

## Dataset Summary

* Total Records: 3,900
* Features: 18
* Key Attributes:

  * Customer demographics (Age, Gender, Location, Subscription Status)
  * Purchase details (Item Purchased, Category, Purchase Amount, Season, Size, Color)
  * Behavioral metrics (Discount Applied, Promo Code Used, Previous Purchases, Frequency of Purchases, Review Rating, Shipping Type)

---

## Tech Stack

* Python – Data cleaning and preprocessing
* PostgreSQL – Data storage and SQL-based analysis
* Power BI – Data visualization and dashboard creation
* pgAdmin – Database management

---

## Project Workflow

### Data Preprocessing (Python)

* Loaded and explored dataset using pandas
* Handled missing values in the Review Rating column
* Standardized column names for consistency
* Performed feature engineering (age groups, purchase frequency)
* Prepared cleaned dataset for database integration

### Database Integration (PostgreSQL)

* Created database and structured tables
* Imported cleaned dataset into PostgreSQL
* Validated data integrity

### SQL Analysis

* Revenue analysis by gender
* Identification of high-spending discount users
* Top-rated products analysis
* Shipping type comparison
* Subscription versus non-subscription behavior
* Customer segmentation (New, Returning, Loyal)
* Product-level and category-level performance insights

### Data Visualization (Power BI)

* Built an interactive dashboard
* Visualized revenue trends, customer segments, product performance, and age-group contributions

---

## Key Insights

* Male customers generated higher total revenue compared to female customers
* Loyal customers represent a significant portion of repeat purchases
* Certain products show strong dependency on discount-based sales
* Subscription status influences purchasing behavior and spending patterns
* Younger age groups contribute a substantial share of overall revenue

---

## Dashboard Preview

<img width="1808" height="996" alt="image" src="https://github.com/user-attachments/assets/709bb5b5-530d-41a2-a002-c3dac4863c0d" />

---

## Business Recommendations

* Introduce loyalty programs to retain high-value customers
* Optimize discount strategies to balance revenue and profitability
* Promote top-performing and highly rated products
* Implement targeted marketing strategies based on customer segments

---

## Future Improvements

* Extend analysis with advanced customer metrics (e.g., lifetime value, segmentation models)
* Enhance dashboard with KPI-driven visuals
* Automate the data pipeline for scalability
* Integrate predictive analytics for forecasting

---

## Acknowledgment

This project is inspired by the original work by Amlan Mohanty:
https://github.com/amlanmohanty1/customer-trends-data-analysis-SQL-Python-PowerBI

While the project structure and dataset are derived from the original source, the implementation, analysis, and insights have been independently executed as part of my learning in data analytics.

---

## Author

Vinayak Jajoo
