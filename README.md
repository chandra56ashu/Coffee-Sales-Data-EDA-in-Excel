☕ Sales Data Analysis & Exploratory Data Analysis (EDA)

📌 Project Overview

This project performs an exploratory data analysis (EDA) on a coffee shop sales dataset to uncover customer purchasing patterns, peak demand periods, best-selling products, and seasonal trends. The objective is to transform raw transactional data into actionable business insights that can support operational planning, inventory management, pricing strategy, and targeted promotions.

The analysis follows a descriptive analytics framework, combining statistical summaries and visual exploration to understand what happened and when it happened in sales performance. 

Data Source : Kaggle

🎯 Business Objectives

Identify peak sales hours and time-of-day demand patterns

Determine best-selling and least-selling coffee products

Analyse weekday vs weekend performance

Understand monthly and seasonal sales trends

Provide data-driven recommendations for staffing, inventory, pricing, and promotions

📊 Dataset Description

The dataset contains transactional-level sales data from a coffee shop. Each row represents a single product sale.
| Column Name   | Description                            |
| ------------- | -------------------------------------- |
| `ID`          | Unique identifier for each transaction |
| `cash_type`   | Mode of payment                        |
| `coffee_name` | Type of coffee sold                    |
| `Time_of_Day` | Morning / Afternoon / Night            |
| `Weekday`     | Day of the week                        |
| `Month_name`  | Month of the year                      |
| `hour_of_day` | Hour of transaction (1–24)             |
| `money`       | Price of the product                   |
| `Date`        | Date of sale                           |
| `Time`        | Time of sale                           |
| `Unit_sold`   | Number of units sold                   |

🔍 Analysis Performed :

1. Data Exploration

Column-level understanding and validation
Distribution checks for numeric variables
Frequency analysis for categorical features

2. Descriptive Statistics

Mean, median, and mode analysis for:

Hour of day

Transaction value

Weekday and month ordering

3. Sales Pattern Analysis

Time-based analysis

10 AM identified as the single busiest hour

Strong afternoon demand (1–3 PM)


Product analysis
Americano with Milk, Latte, and Americano are the core volume drivers

Weekly trends

Sales strongest mid-week (Tuesday–Thursday)

Sunday is consistently the weakest day

Seasonal trends

Peak demand in March and October

Noticeable dip in April

📈 Key Insights

Customer behavior is stable and predictable, enabling reliable planning

A small set of products drives the majority of sales volume

Premium drinks contribute higher revenue per order

Weekday footfall significantly exceeds weekend demand

Seasonal demand patterns create clear promotion windows

💡 Business Recommendations

Operations & Staffing

Increase staffing during 9–11 AM and 1–3 PM

Optimise workforce allocation based on weekday demand

Inventory & Menu Management

Maintain high inventory for:

Americano with Milk

Latte

Americano

Bundle low-selling items (e.g., Espresso + Pastry) to improve uptake

Promotions & Marketing

Launch campaigns during March, October, and February

Introduce discounts in April to counter demand dip

Focus promotions on mid-week, especially Tuesday

Pricing Strategy

Gradual price increases on premium beverages

Keep high-volume products price-stable to protect demand elasticity

🛠 Tools & Technologies

Excel – Data cleaning and structuring

Descriptive Statistics – Central tendency and distribution analysis

Data Visualisation – Sales trends and comparisons

(The project is designed to be reproducible using Python / SQL for future extensions.)

📁 Repository Structure

├── Sales_Data_Analysis_EDA.xlsx

├── Sales_Data_Ashutosh_Chandra.pdf

├── README.md

🚀 Future Scope

Time-series forecasting for demand prediction

Customer segmentation using clustering

Price elasticity modelling

Migration to Python (Pandas, Matplotlib, Seaborn) for automation

👤 Author
Ashutosh Chandra
