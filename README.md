# Customer_Behaviour_Analysis
End-to-end retail analytics project: cleaned &amp; transformed customer shopping data in Python, analysed purchasing trends and loyalty patterns with SQL, and built an interactive Power BI dashboard. Includes a full project report and stakeholder presentation with business recommendations.
# Consumer Shopping Behaviour Analysis

An end-to-end data analytics project exploring consumer shopping behaviour to uncover purchasing trends, customer loyalty patterns, and key sales drivers for a national retail organisation. The project covers the full pipeline: data cleaning in Python, relational database analysis with SQL, an interactive Power BI dashboard, and a business-facing report and presentation.

Business Question

How can consumer shopping data be analysed to identify purchasing trends, improve customer engagement, and support more effective marketing and product decisions?

Project Structure
File	Description
customer_shopping_behavior__2_.csv	Raw dataset (3,900 customer records) with demographics, purchase details, product categories, review ratings, subscription status, shipping type, discounts, and purchase frequency.
Customer_Shopping_Behavior_Analysis.ipynb	Python notebook for data cleaning and preparation — handling missing values, standardising column names, engineering features (age_group, purchase_frequency_days), and loading the cleaned data into a SQL database (PostgreSQL/MySQL/SQL Server).
customer_behavior_sql_queries.sql	SQL queries analysing revenue by gender, discount behaviour, top-rated and most-purchased products, shipping type comparisons, subscriber spend, customer segmentation (New/Returning/Loyal), and revenue by age group.
customer_behavior_dashboard_dark.pbix	Interactive Power BI dashboard visualising customer demographics, sales performance, product categories, and shopping channel trends with filters and slicers.
Consumer_Shopping_Behaviour_Analysis_Project.pdf	Project report summarising methodology, analysis, findings, and business recommendations.
Consumer_Shopping_Behaviour_Analysis_Presentation.pptx	Stakeholder presentation communicating key insights and recommendations.
Tools & Technologies
Python (pandas) — data cleaning and transformation
SQL (PostgreSQL/MySQL/SQL Server) — relational database design and analytical queries
Power BI — interactive dashboarding and visualisation
SQLAlchemy — Python-to-database connectivity
Key Analyses
Revenue breakdown by gender and age group
Discount usage vs. spending patterns
Top-rated and most-purchased products by category
Standard vs. Express shipping comparison
Subscriber vs. non-subscriber spending behaviour
Customer segmentation (New, Returning, Loyal)
Repeat buyer subscription likelihood
How to Use
Run the Jupyter notebook to clean the raw CSV and load it into your database of choice.
Execute the SQL queries against the loaded customer table to generate analytical outputs.
Open the .pbix file in Power BI Desktop to explore the interactive dashboard.
Refer to the PDF report and PPTX presentation for the full write-up and business recommendations.
