📊 **Online Retail Customer Churn — Exploratory Data Analysis (EDA)**

🧠 **Project Overview**
This project performs Exploratory Data Analysis (EDA) on an Online Retail Customer Churn dataset to understand customer behavior, spending patterns, engagement levels, and churn indicators. The notebook investigates customer demographics, purchase activity, satisfaction, promotion response, and retention signals using statistical summaries and visualizations.

The goal is to uncover patterns that help explain which customers are more likely to churn and how different behavioral factors relate to total spend and engagement.

🎯 **Objectives**
-Inspect dataset structure and data quality
-Check for missing values and duplicates
-Analyze customer demographics and spending behavior
-Compare high-value vs low-value customers
-Explore satisfaction and promotion response patterns
-Examine relationships between purchases, tenure, and spend
-Study churn variation across customer attributes

📁 **Dataset Features**
The dataset contains 1,000 customer records and 15 variables:
-Customer_ID — Unique customer identifier
-Age — Customer age
-Gender — Gender category
-Annual_Income — Yearly income
-Total_Spend — Total purchase spend
-Years_as_Customer — Customer tenure
-Num_of_Purchases — Number of purchases made
-Average_Transaction_Amount — Average spend per purchase
-Num_of_Returns — Number of returned purchases
-Num_of_Support_Contacts — Support interactions
-Satisfaction_Score — Customer satisfaction rating (1–5)
-Last_Purchase_Days_Ago — Recency indicator
-Email_Opt_In — Marketing email subscription status
-Promotion_Response — Promotion engagement behavior
-Target_Churn — Churn indicator (Yes/No)

🔍 **Analysis Performed**
✅ Data Quality Checks
-Dataset shape verification
-Column inspection
-Missing value check
-Data type validation
-Duplicate record detection

📈 Descriptive Statistics
-Mean, median, and standard deviation for:
-Age
-Annual Income
-Total Spend
-Distribution interpretation and variability analysis

💰 Customer Spend Segmentation
-Identified lowest 10% and highest 10% spenders using quantiles
-Compared statistical characteristics of:
-Low spenders
-High spenders
-Middle segment

😊 Satisfaction Analysis
-Satisfaction score distribution visualization
-Pattern interpretation across rating levels

👥 Demographic Distribution
-Gender distribution analysis
-Category balance visualization

📣 Promotion Response
-Promotion engagement breakdown
-Most common response types identified

🛒 Behavioral Relationships
-Years as Customer vs Total Spend (scatter plot)
-Number of Purchases vs Total Spend:
-Pearson correlation calculated
-Scatter plot visualization
-Positive relationship observed

📧 Marketing Engagement & Churn
-Email opt-in vs churn comparison
-Churn distribution by subscription status

📊 Key Insights
-Customer ages are relatively concentrated with moderate variation.
-Income and spending show high variability, suggesting strong segmentation potential.
-A small group of customers contributes disproportionately to total revenue.
-Satisfaction scores are fairly evenly distributed, with a slight mid-range concentration.
-Promotion responses show both strong engagement and notable unsubscribe behavior.
-Number of purchases has a strong positive relationship with total spend.
-Longer-tenure customers tend to contribute more revenue.
-Email engagement shows visible differences in churn patterns.

🛠️ Tools & Libraries Used
-Python
-Pandas
-NumPy
-Matplotlib
-Seaborn
-Google Colab

▶️ How to Run
-Open the notebook in Google Colab
-Upload or mount your dataset file
-Update the dataset path if needed
-Run cells from top to bottom

📌 Notes
-Dataset was pre-structured.
-Focus was placed on exploratory analysis and insight generation, not heavy data cleaning or feature engineering.
-Visualizations were used to support interpretation of behavioral patterns.
