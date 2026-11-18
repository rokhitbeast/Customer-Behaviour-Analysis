Customer Shopping Behavior Analysis
An end-to-end Data Analytics project focused on analyzing retail customer shopping behavior using Python, PostgreSQL, SQL, and Power BI. The project explores customer purchasing patterns, product preferences, discount usage, subscription behavior, and spending trends to generate actionable business insights.

Project Overview
The objective is to understand customer shopping patterns and help retail businesses make data-driven decisions related to sales, customer engagement, marketing strategies, and customer retention.

The analysis uses a dataset containing 3,900 purchase records and 18 attributes covering customer demographics, product categories, purchase amounts, shipping preferences, discounts, and shopping frequency.

Tech Stack
Python: Pandas, Jupyter Notebook
Database: PostgreSQL
Query Language: SQL
Visualization: Microsoft Power BI
Libraries: SQLAlchemy, Psycopg2
Project Workflow
1. Data Cleaning and Exploratory Data Analysis (Python)
Imported and explored the dataset using Pandas.
Identified and handled 37 missing values in the Review Rating column using category-wise median imputation.
Standardized column names using snake_case.
Created customer age groups using age-based segmentation.
Converted purchase frequency into numerical days.
Identified redundant columns and removed unnecessary attributes.
Prepared the cleaned dataset for database analysis.
2. Database Integration (PostgreSQL)
Connected Python with PostgreSQL using SQLAlchemy and Psycopg2.
Loaded the cleaned dataset into a PostgreSQL database.
Structured the customer data for business-oriented SQL analysis.
3. Business Analysis (SQL)
Developed 10 SQL queries to investigate important business questions:

Revenue comparison between male and female customers.
Identification of high-spending customers using discounts.
Top 5 products based on average customer ratings.
Comparison of average purchase amounts across shipping methods.
Spending and revenue comparison between subscribers and non-subscribers.
Products with the highest percentage of discounted purchases.
Customer segmentation into New, Returning, and Loyal groups.
Top 3 most-purchased products within each category.
Relationship between repeat purchases and subscription status.
Revenue contribution across different customer age groups.
SQL concepts used include aggregations, subqueries, CASE statements, CTEs, window functions, and filtering.

4. Interactive Dashboard (Power BI)
Developed a Power BI dashboard to visualize important customer behavior metrics.

Key Performance Indicators:

Total Customers: 3.9K
Average Purchase Amount: $59.76
Average Review Rating: 3.75
Dashboard Features:

Customer distribution by subscription status.
Revenue and sales analysis by product category.
Revenue and sales analysis by age group.
Interactive filters for gender, subscription status, category, and shipping type.
5. Business Recommendations
The analysis supports business decisions such as:

Improving subscription programs through exclusive customer benefits.
Strengthening customer retention through loyalty programs.
Optimizing discount strategies.
Promoting highly rated and frequently purchased products.
Developing targeted marketing strategies using customer demographics and purchasing patterns.
Repository Structure
Customer-Shopping-Behavior-Analysis/
│
├── customer_shopping_behavior.csv
├── Customer_Shopping_Behavior_Analysis.ipynb
├── customer_behavior_sql_queries.sql
├── customer_behavior_dashboard.pbix
├── Customer Shopping Behavior Analysis.pdf
├── Business Problem Document.pdf
├── Customer-Shopping-Behavior-Analysis.pptx
├── LICENSE
└── README.md
How to Run the Project
1. Clone the repository

git clone https://github.com/<your-username>/<your-repository>.git
cd <your-repository>
2. Install dependencies

pip install pandas sqlalchemy psycopg2-binary jupyter
3. Run the Python notebook

Open Customer_Shopping_Behavior_Analysis.ipynb and execute the cells to explore, clean, transform, and load the dataset.

4. Configure PostgreSQL

Create a PostgreSQL database named customer_behavior.
Configure your database connection credentials in the notebook.
Execute the notebook's PostgreSQL integration section to load the cleaned data.
5. Execute SQL queries

Run customer_behavior_sql_queries.sql using PostgreSQL to reproduce the business analysis.

6. Explore the Power BI dashboard

Open customer_behavior_dashboard.pbix in Microsoft Power BI Desktop to explore the interactive visualizations.

Key Skills Demonstrated
Data Cleaning and Preprocessing
Exploratory Data Analysis (EDA)
Feature Engineering
Python and Pandas
PostgreSQL Database Integration
SQL Business Analysis
Data Visualization and Dashboard Development
Business Insights and Data-Driven Decision Making
License
This project is available under the MIT License. See the LICENSE file for details.
