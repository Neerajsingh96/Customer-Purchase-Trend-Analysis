Customer Purchase Trend Analysis

  This project analyzes 3,900 customer purchase records to identify trends in buying behavior, product demand, revenue contribution, and customer engagement. It   includes data loading, EDA, cleaning, SQL queries, a Power BI dashboard, a written report, and a final presentation created using Gamma.

⭐ Overview
  The goal of this project is to understand who the customers are, what they buy, and how they shop.
  The analysis examines demographics, purchase details, discount patterns, subscription behavior, shipping choices, and seasonal buying trends to produce   actionable insights for business decisions.
  This end-to-end analytics workflow demonstrates skills across Python, SQL, visualization, storytelling, and dashboard development.

📁 Dataset
  Rows: 3,900
  Columns: 18
  Includes: demographics, purchase amount, item data, season, ratings, subscription, shipping type, previous purchases, and more.
  37 missing values in Review Rating column
  Data loaded and analyzed in:
  customer_shopping_behavior_analysis.ipynb
  SQL queries in: cuatomer_behavior.sql 
  cuatomer_behavior
  
🛠 Tools & Technologies
  Python (Pandas, NumPy, Matplotlib, Seaborn)
  SQL (PostgreSQL / MySQL / SQL Server)
  Power BI (Interactive dashboard)
  Gamma.app (AI-powered presentation creation)
  Jupyter Notebook
  Excel/CSV Dataset
  
<img width="4872" height="2656" alt="500731798-8bbd5dc9-eb6c-40c1-8f19-c08b4107f654" src="https://github.com/user-attachments/assets/1627d0b0-c180-4f17-9521-f0592d422bd9" />


🔎 Project Steps
1. Data Loading (Python)
  Imported dataset using Pandas
  Inspected structure, datatypes, missing values
  Created age groups and other derived columns

2. Exploratory Data Analysis (EDA)
  Distribution of Age, Gender, Category, Shipping Type
  Revenue by Category, Item, and Season
  Discount and Subscription patterns
  Correlation between attributes
  Statistical summary and visualizations

3. Data Cleaning
  Treated missing values (Review Rating)
  Removed duplicates
  Standardized text fields
  Converted datatypes (e.g., ratings, purchase amount)

4. SQL Analysis (16+ Business Queries)
  Revenue by gender
  Customers using discounts but spending above average
  Top 5 products by review rating
  Average spend: Standard vs Express shipping
  Subscriber vs non-subscriber total revenue
  Products with highest discount usage
  Customer segmentation (New, Returning, Loyal)
  Top 3 items per category
  Repeat buyers likely to subscribe
  Revenue by age group
  Customers in Winter season
  Average customer age
  Customers from specific location
  Revenue by product category
  Customers with rating > 4
  Percentage of Express shipping usage

5. Power BI Dashboard
  Designed to visualize:
  Revenue by Category
  Top Items
  Customer Demographics
  Subscription & Discount Impact
  Shipping Preferences
  Seasonal Purchase Trends
  Review Rating Summary
  Dashboard highlights the key KPIs and allows interactive exploration.

6. Report Creation
  A structured written report summarizing:
  Insights & trends
  Customer segments
  Most profitable categories
  Impact of discounts & shipping types
  Business recommendations based on data

7. PPT with Gamma
  Created a visually clean presentation covering:
  Problem statement
  Data understanding
  EDA visuals
  SQL insights
  Dashboard walk-through
  Business recommendations
  Final conclusion

📊 Key Results
  Clothing category generated the highest revenue
  Top items: Blouse, Shirt, Dress, Jewelry
  Young Adults & Middle-aged groups spend the most
  Express shipping linked with higher purchase intent
  Subscribers spend more than non-subscribers
  Discount usage is high but needs margin review
  Review rating average ~3.75

🚀 How to Run the Project
1. Clone Repository
  git clone https://github.com/Neerajsingh96/Customer-Purchase-Trend-Analysis.git cd Customer-Purchase-Trend-Analysis

2. Run Python Notebook
  Open: customer_shopping_behavior_analysis.ipynb

3. Execute SQL Queries
  Import the SQL script: cuatomer_behavior.sql, Run in PostgreSQL / MySQL / SQL Server.

4. View Power BI Dashboard
Open: customer_behavior.pbix

5. View Report & PPT
Report: Customer-Purchase-Trend-Analysis.pdf
PPT: Customer-Purchase-Trend-Analysis.pdf

📞 Contact
neerajsingh0558@gmail.com
If you're interested in collaboration or feedback, feel free to reach out!
