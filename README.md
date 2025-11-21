📊 Customer Behavior Analysis — End-to-End Data Analytics Project
🔍 Overview

This project focuses on analyzing customer shopping behavior using a complete data analytics pipeline. The goal is to derive insights that help businesses understand customer patterns, spending habits, and product performance.
The workflow covers everything from data loading → EDA → cleaning → database integration → SQL analysis → Power BI dashboard → final reporting.

This project demonstrates proficiency in:

Python (EDA, preprocessing, visualization)

SQL (PostgreSQL / MySQL / SQL Server)

Data modeling

BI dashboard development (Power BI)

Business storytelling (Report + Gamma PPT)

📁 Dataset

Name: Customer Shopping Behavior Dataset
Contains:

Customer demographics (age, gender, location)

Shopping details (items purchased, discount usage, payment method)

Purchase frequency

Product ratings

Shipping & subscription data

File Format: CSV

🛠️ Tools & Technologies
Category	Tools
Programming	Python (Pandas, NumPy, Matplotlib, Seaborn)
Databases	PostgreSQL, MySQL, SQL Server
ORM / Connector	SQLAlchemy, psycopg2 / PyMySQL / ODBC
Visualization	Power BI
Reporting	MS Word / PDF
Presentation	Gamma App
🚀 Project Steps
1️⃣ Load & Explore Data (Python)

Import dataset using Pandas

Inspect structure, check shape, datatypes

Handle missing values

Identify anomalies & outliers

2️⃣ Data Cleaning & Preprocessing

Convert columns → lowercase, standardized names

Map values (e.g., “Quarterly” → 90 days)

Fix inconsistent category entries

Drop redundant columns

Create new engineered features (e.g., purchase_frequency_days)

3️⃣ Exploratory Data Analysis (EDA)

Distribution of spending

Relationship between discounts & sales

Top selling products

High-value customer segments

Shipping type behavior

Subscription impact

4️⃣ SQL Database Integration

Load cleaned dataframe into any SQL database:

🔹 PostgreSQL using psycopg2
🔹 MySQL using PyMySQL
🔹 SQL Server using ODBC driver

Performed analytical SQL queries such as:

Revenue by gender

Highest-rated products

Discount patterns

Age group revenue

Repeat buyer behavior

Category insights

5️⃣ Power BI Dashboard

Built a fully interactive dashboard including:

Total Revenue Overview

Customer Segmentation

Product Performance

Discount Impact Analysis

Shipping Trends

Rating & Subscription Insights

6️⃣ Insights & Summary Report

A professional report was created summarizing:

Key business findings

Patterns & correlations

Customer behavior insights

Actionable recommendations

7️⃣ Gamma.ai Presentation

Created a pitch-style PPT covering:

Project objective

Methodology

Key visualizations

Dashboard snapshots

Insights & conclusion

📊 Dashboard Highlights

Dynamic filters for gender, category, shipping, subscription

KPI Cards: Revenue, Avg Rating, Repeat Customers, Discount Usage

Category-wise top product comparison

Trend visuals & heatmaps

Drill-through for customer-level analytics

📈 Key Results

✔ Male vs Female revenue differences
✔ Top 5 highest-rated product categories
✔ How discounts affect spending
✔ Which customer segments generate the most revenue
✔ High-value age groups
✔ Loyal vs new customer comparison
✔ Discount-driven product performance

🧪 How to Run the Project
1️⃣ Install Dependencies
pip install pandas numpy sqlalchemy psycopg2 pymysql pyodbc matplotlib seaborn

2️⃣ Run the Python Scripts
python load_and_clean.py
python eda_analysis.py
python sql_loader.py

3️⃣ Connect to SQL Database

Update your connection string inside:

config/db_config.py

4️⃣ Open Power BI File

Import the cleaned dataset or SQL connection.

5️⃣ View the Dashboard

Open the .pbix file inside the dashboard folder.

6️⃣ Read the Report & PPT

/reports/Customer_Behavior_Report.pdf

/presentation/Customer_Analytics_PPT_Gamma.pdf

📬 Contact / Feedback

If you’d like to improve the dashboard or extend this project (ML model, forecasting, churn analysis), feel free to connect!
