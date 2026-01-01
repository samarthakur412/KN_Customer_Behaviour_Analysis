# 🛍️ Customer Shopping Behavior Analysis
  End-to-End Data Analytics Project | Python · SQL · Power BI
# 📌 Project Overview
This project analyzes customer shopping behavior for a retail company (Kamta Nath Shops) using real-world transactional data. The objective is to uncover actionable insights into customer demographics, purchasing patterns, discount behavior, loyalty, and revenue drivers to help the business improve sales performance, customer engagement, and long-term retention

The project follows an end-to-end analytics lifecycle, covering:

- Data cleaning & feature engineering (Python)
- Business-driven analysis (SQL)
- Executive dashboards (Power BI)
- Actionable business recommendations

# 🎯 Business Problem
Retail management observed changing customer behavior across:

- Demographics
- Product categories
- Discounts & promotions
- Subscription usage
- Shipping preferences (Standard vs Express)

Key Question:
How can consumer shopping data be leveraged to identify trends, improve engagement, and optimize marketing & product strategies?

# 📊 Dataset Summary
- Records: 3,900 transactions
- Features: 18 columns
- Key Attributes:
  - Customer demographics (Age, Gender, Location)
  - Purchase behavior (Category, Item, Amount, Season)
  - Marketing signals (Discount Applied, Review Rating)
  - Loyalty indicators (Subscription Status, Previous Purchases)
- Missing Data: Review ratings (handled via category-wise median imputation)

#🛠️ Tech Stack
| Layer                    | Tools                  |
| ------------------------ | ---------------------- |
| Data Cleaning & Modeling | Python (Pandas, NumPy) |
| Database & Querying      | MySQL / PostgreSQL     |
| Visualization            | Power BI               |
| Version Control          | Git & GitHub           |


#🔄 Project Workflow
Raw Dataset
   ↓
Python (Data Cleaning & Feature Engineering)
   ↓
SQL (Business Queries & Segmentation)
   ↓
Power BI (Interactive Dashboard)
   ↓
Insights & Business Recommendations

# 🧪 Data Preparation (Python)
- Cleaned and standardized column names (snake_case)
- Handled missing review ratings using median by product category
- Created engineered features:
- age_group
- purchase_frequency
- Validated redundant features and optimized dataset
- Loaded clean data into SQL database for analysis

# 🧮 SQL Analysis (Business-Focused Queries)
Key analyses include:
- Revenue contribution by gender
- High-spending customers who still use discounts
- Top-rated and top-selling products
- Subscription vs non-subscription revenue comparison
- Shipping type impact on average spend
- Discount-dependent products
- Customer segmentation: New · Returning · Loyal
- Repeat buyers vs subscription likelihood
- Revenue contribution by age group

# 📈 Power BI Dashboard
An interactive executive dashboard was built to visualize:
- Customer distribution & KPIs
- Revenue by category, age group, and gender
- Subscription impact on revenue
- Shipping behavior insights
- Sales & ratings overview
- Designed for non-technical stakeholders to quickly derive insights and take action

# 💡 Key Business Insights
- Subscribers generate more consistent revenue
- Loyal customers form the largest segment
- Express shipping users spend slightly more per order
- Certain products rely heavily on discounts
- Young and middle-aged customers drive the highest revenue

# 🚀 Business Recommendations
- Promote subscription benefits to boost recurring revenue
- Introduce loyalty rewards for repeat customers
- Optimize discount strategies to protect margins
- Highlight top-rated & best-selling products in campaigns
- Focus targeted marketing on high-revenue age groups

# 📂 Repository Structure
├── data/
│   └── raw_dataset.csv
├── python/
│   ├── data_cleaning.py
│   └── feature_engineering.py
├── sql/
│   ├── schema.sql
│   └── business_queries.sql
├── power_bi/
│   └── customer_behavior_dashboard.pbix
├── reports/
│   └── insights_and_recommendations.pdf
└── README.md

# 🧠 What This Project Demonstrates
✔ Business-first data thinking
✔ Strong SQL & Python fundamentals
✔ End-to-end analytics ownership
✔ Stakeholder-ready dashboards
✔ Industry-relevant problem solving

# 📬 Contact
If you’d like to discuss this project, collaborate, or explore improvements (FastAPI, Docker, cloud deployment), feel free to connect.
