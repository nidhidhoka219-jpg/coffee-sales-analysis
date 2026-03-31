# Coffee Sales Data Analysis and Dashboard

# Project overview 
This project analyzes a coffee shop's sales data to understand customer purchasing behaviour, payment methods and revenue patterns. The analysis was performed using Python in Google Colab for data cleaning and exploratory data analysis, and Power BI for building an interactive dashboard.The goal is to derive actionable insights that can help the business improve sales strategies and optimize product offerings.

# Dataset
Dataset name: coffee.csv
The dataset contains transaction level data of coffee sales with the following columns:

- date - Transaction date

- datetime - Exact timestamp of the transaction

- cash_type - Payment method type

- card - Card transaction information

- money - Amount paid by the customer

- coffee_name - Type of coffee purchased

# Tools used 
- Python

- Pandas

- Numpy

- Matplotlib

- Seaborn

- Scikit-learn

- Power BI

# Data analysis steps
1. Data Loading
   *Imported the dataset using Pandas.
2. Data Cleaning
   * Handled missing values.
   * Removed duplicate records.
   * Converted date columns into proper datetime format.
3. Feature Engineering
   * Extracted month, year, and day from the date column.
   * Prepared the dataset for analysis.
4. Exploratory Data Analysis (EDA)
   * Revenue distribution analysis.
   * Coffee type sales comparison.
   * Payment method analysis.
   * Outlier detection using boxplots.
5. Data Visualization
   * Bar charts for revenue by coffee type.
   * Boxplots for transaction distribution.
6. Machine Learning 
   * Implemented Linear Regression to understand relationships between variables.
  
# Power BI Dashboard
An interactive Power BI dashboard was created to present business insights visually.
Dashboard includes:
* Total Revenue KPI
* Sales by Day
* Sales by Hour
* Revenue by Coffee Type
* Payment Method Distribution
* Revenue trend over the time
The dashboard allows easy interpretation of sales patterns and customer preferences.


# Project Files
* coffee.csv – Dataset
* Coffee_Sales_Analysis.ipynb – Python analysis notebook
* Coffee_Dashboard.pbix – Power BI dashboard file
  
# Key Business Insights
* Latte contributes the highest revenue among all coffee types.

* Total revenue: 37.51K.
  - Why it matters: Shows overall scale of sales during the period.
  - Action: Use this as baseline for month-over-month targets and inventory planning.
  
* Average Order Value (AOV): 33.11
   - Why it matters: Customers spend ~33 per order on average which indicates upsell potential.
   - Action: Introduce combos, premium add-ons, and size-up promotions to increase AOV by 5–10%.

* Revenue growth: 22.6% (vs prior period).
   - Why it matters: Healthy growth — confirm whether driven by volume, price or product mix.
   - Action: Attribute growth to promotions or top products and scale the most effective tactics.

* Revenue distribution by day: Relatively consistent daily revenue with minor peaks on weekends.
   - Why it matters: Predictable weekly pattern for staffing and inventory.
   - Action: Increase staff and inventory on weekend peaks; run weekday promotions to smooth demand.

* Hourly sales pattern: Clear peak hours during morning rush(8 AM- 11 AM) + secondary evening peak
   - Why it matters: Operational pressure concentrated in short windows.
   - Action: Schedule more staff/prepare faster service during peaks; offer off-peak incentives.

* Payment behavior: One payment method dominates (cash/card), with digital payments growing.
   - Why it matters: Affects checkout speed, fees and customer convenience.
   - Action: Ensure fast POS options, consider digital-payment promos, and monitor payment fees.

* Operational efficiency (heatmap): The hour × day heatmap highlights specific slots with highest demand (use for staffing).
   - Why it matters: Direct lever to reduce wait times and improve satisfaction.
   - Action: Create a staff rota optimized to heatmap bands and measure average serve time.

# Conclusion
The analysis provides insights into customer preferences and revenue drivers within the coffee shop. These insights can help the business focus on high-performing products, improve payment systems, and optimize their product strategy.

# Author
Nidhi D

Aspiring Data Analyst

LinkedIn: https://www.linkedin.com/in/nidhi-dhoka-701743379
