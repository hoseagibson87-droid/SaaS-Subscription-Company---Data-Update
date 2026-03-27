# SaaS-Subscription-Company---Data-Update
SaaS Customer Churn &amp; Revenue Analysis

Overview

This project analyzes customer churn and revenue trends for a SaaS business. The goal is to identify key drivers behind churn and revenue fluctuations, and provide actionable insights to improve customer retention and business performance.

Business Problem

A VP of Growth requested insights into:

What is driving fluctuations in revenue?
What factors are contributing to customer churn?
How do customer behavior, product performance, and regional trends impact churn?

Project Approach
1. Data Quality Assessment

Initial analysis revealed significant missing data across key fields (up to 73%), making the dataset unsuitable for reliable analysis.

Action Taken:

Identified data limitations
Avoided misleading analysis
Recommended upstream data fixes
2. Data Remediation

After addressing data quality issues, a cleaner dataset was obtained with significantly reduced missing values.

3. Data Cleaning
Standardized column names
Converted data types (dates, numeric fields)
Handled missing values using appropriate imputation techniques
Validated dataset consistency
4. Exploratory Data Analysis (EDA)

Key areas analyzed:

Revenue trends over time
Churn rate by region and product
Customer satisfaction and support behavior
Product distribution across regions
5. Deep Dive Analysis
Investigated whether product mix explains regional churn differences
Tested hypothesis: Does higher Enterprise adoption drive higher churn in certain regions?
Found that product mix only partially explains churn variation
Key Insights
 The West region has the highest churn rate (~36%), significantly higher than the East (~20%)
 Product type shows minimal impact on churn compared to regional differences
 Product mix partially explains churn differences, but is not the primary driver
 Customer behavior metrics (support tickets, satisfaction) showed weak correlation with churn in this dataset
Business Recommendations
Investigate region-specific factors in the West (e.g., customer experience, competition)
Improve data collection processes to ensure reliable analytics
Implement early churn detection systems
Focus retention strategies on high-risk regions
Limitations
Initial dataset had significant missing data, requiring remediation
Some variables showed weak relationships with churn, limiting explanatory power
Further data (e.g., customer tenure, pricing, engagement metrics) would improve analysis

Tools & Technologies
Python (Pandas)
Google Colab
Data Cleaning & EDA Techniques
