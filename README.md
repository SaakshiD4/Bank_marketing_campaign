# Bank Marketing Campaign Analysis using PySpark and SQL 

My goal for this project was to understand which factors influence a customer's decision to subscribe to a bank term deposit.

Using PySpark and SQL, I cleaned and transformed over 11,000 records, explored key patterns, and extracted insights. 

This hands-on process helped me connect data with real business outcomes and improved my skills in data analysis and interpretation.

### Tools Used:

PySpark — for big data processing and transformations

Spark SQL — for querying and aggregating data

Databricks — cloud platform for running PySpark and SQL workloads

Pandas — for smaller data manipulation and visualization prep

Matplotlib & Seaborn — for data visualization

 ## What I Did Using PySpark

Loaded the original bank marketing dataset into PySpark.

Split the dataset into three separate tables for better organization and analysis:

Customer table with demographic and financial info (age, job, marital status, balance, loans).

Current campaign table with details of ongoing marketing contacts (call duration, contact method, campaign number).

Previous campaign table with historical campaign info (days since last contact, number of previous contacts, previous outcomes).

Dropped duplicate records and removed rows with missing important values (like age and job).

Renamed columns for better clarity .

Created a new column age_group to categorize customers by age ranges.

Cast columns to correct data types for consistency.

Selected only relevant columns for each table to keep data clean.

Ensured customer_id is included in all tables for easy joining later.

## Key Findings from SQL Analysis

Checked how many customers are in each marital status group to know who makes up most of the customers.

Looked at average account balance for different education levels to see which group has more money on average.

Found out which month had the most marketing calls so we can know when campaigns are busiest.

Found the top 5 jobs where people took personal loans the most.

Checked which customers got called many times in the current campaign.

Compared housing loans and personal loans to see how many customers have both or one of them.

Found job groups where calls lasted longer, which might mean those customers are more interested.

Found customers who got contacted more than 3 times in both current and previous campaigns.

Looked at which education groups have higher balances, to focus on richer customers.

Ranked customers by balance within their job groups to find top customers.

Grouped customers by risk level based on balance and checked how many have housing loans.

These results helped me understand customer groups better and where the marketing team should focus.

## Insights Through Visualizations

Previous campaign outcomes and success rates by contact count.

Balance categories across age groups.

Call duration distribution.

Customer job and age group distributions.

How often subscribed customers were contacted.

Subscription rates by job and loan status.

Monthly trends in subscriptions.

## Key Findings:

Cell phone contact leads to higher success.

May, August, October are best for campaigns.

Past success boosts future subscriptions.

Longer calls increase conversion chances.

Students and retirees are more likely to subscribe.



