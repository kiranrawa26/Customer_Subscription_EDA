 🧠 Customer Subscription Insights — Exploratory Data Analysis (EDA)

📌 Project Overview
This project focuses on performing Exploratory Data Analysis (EDA) on a Customer Subscription dataset to uncover insights about user behavior, subscription patterns, referral performance, and revenue distribution.  
The goal is to transform raw data into meaningful insights that can support marketing, pricing, and retention strategies.

 🧰 Tools & Technologies Used
| Category | Tools / Libraries |
|-----------|-------------------|
| Programming | Python |
| Libraries | Pandas, NumPy, Matplotlib, Seaborn |
| Environment | Jupyter Notebook / VS Code |
| Version Control | Git & GitHub |

 🧾 Dataset Description
The dataset contains customer transaction and subscription details.

| Column Name | Description |
|--------------|-------------|
| `cust_id` | Unique identifier for each customer |
| `transaction_type` | Type of transaction (new / renewal / cancel) |
| `transaction_date` | Date of transaction |
| `subscription_type` | Type of plan (Basic / Pro / Max) |
| `subscription_price` | Price paid for the plan |
| `customer_gender` | Gender of the customer |
| `age_group` | Age category (e.g., 18-25, 26-35, etc.) |
| `customer_country` | Customer’s country |
| `referral_type` | How the customer discovered the service |


🧮 Steps Performed in EDA

1. Data Import & Cleaning
   - Loaded CSV data using Pandas  
   - Removed duplicates and handled missing values  
   - Converted `transaction_date` into datetime format  

2. Descriptive Statistics
   - Calculated mean, median, mode, standard deviation  
   - Checked data distribution and unique value counts  

3. Exploratory Visualizations
   - Subscription type distribution  
   - Gender-based revenue comparison  
   - Monthly revenue trends  
   - Revenue contribution by referral channel  
   - Country-wise analysis  

4. Correlation Analysis
   - Analyzed relationships between numerical features  
   - Identified factors influencing subscription pricing  

5. Outlier Detection
   - Used IQR method and boxplots to detect abnormal price values  

6. Insights Summary
   - Consolidated key business insights using visual dashboards  

 
 📊 Visualizations & Insights

🔹 Subscription Type Distribution
- Basic plan dominates user count  
- Max plan contributes **highest revenue** despite smaller user base  

🔹 Revenue by Gender
- Female customers spend 35% more on average than male customers  

🔹 Monthly Revenue Trend
- Shows steady month-on-month growth, with minor dips due to seasonality  

🔹 Referral Channel Performance
- Google Ads and Facebook bring the highest revenue  
- Underperforming channels: Bing & TV ads  

🔹 Outlier Detection
- Detected few high-priced outliers representing annual or enterprise plans

📈 Summary of Findings
| Insight | Business Impact |
|----------|------------------|
| Premium (MAX) plans bring 50%+ of total revenue | Focus marketing on high-tier conversions |
| Female customers have higher ARPU | Target retention & upselling campaigns |
| Google & Facebook referrals outperform others | Optimize marketing spend on top channels |
| Minor seasonal drop in recent months | Investigate churn or pricing strategy |










































### 🧩 Project Structure
