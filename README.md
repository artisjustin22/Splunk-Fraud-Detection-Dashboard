# Splunk-Fraud-Detection-Dashboard
Analyzing financial transaction data to identify fraud patterns by age groups, gender, merchant and and transaction categories

# Splunk Fraud Detection Dashboard

## Project Overview

This project uses Splunk Enterprise to analyze financial transaction data and identify patterns in fraudulent activity. I created an interactive dashboard to visualize transaction trends and investigate fraud across different customer demographics, merchants, and transaction categories.

## Tools and Technologies

- Splunk Enterprise
- Splunk Search Processing Language (SPL)
- CSV Dataset
- Data Visualization
- Fraud Detection and Analysis

## Project Objectives

The goal of this project was to use transaction data to answer four main questions:

1. How are transactions distributed across categories, age groups, and merchants?
2. How does fraudulent activity vary by age, category, month, and gender?
3. Which gender has the highest number of fraudulent transactions, and in which categories?
4. Which age groups have the highest number of fraudulent transactions, and which merchants are involved?

## Dashboard Visualizations

I created 10 visualizations using SPL queries:

1. Transaction Count by Category
2. Fraudulent vs. Legitimate Transactions
3. Transaction Count by Age
4. Transaction Count by Merchant
5. Fraudulent Transactions by Age
6. Fraudulent Transactions by Category
7. Fraudulent Transactions by Month (Step)
8. Fraudulent Transactions by Gender
9. Fraudulent Transactions by Gender and Category
10. Fraudulent Transactions by Age and Merchant

## Technical Process

1. Imported a CSV dataset into Splunk Enterprise.
2. Configured the source type and indexing settings.
3. Used SPL searches to filter, count, group, and sort transaction records.
4. Filtered fraudulent transactions using the `fraud=1` field.
5. Created bar charts, column charts, pie charts, line charts, and statistical tables.
6. Combined the visualizations into a single fraud detection dashboard.

## Skills Demonstrated

- Splunk data ingestion and indexing
- Writing SPL queries
- Filtering and aggregating data
- Identifying fraud patterns
- Creating analytical dashboards
- Presenting findings through visualizations

## Conclusion

This project gave me hands-on experience using Splunk to investigate transaction data and build visualizations that make fraud patterns easier to identify. It strengthened my understanding of how to use search queries and dashboards to analyze large datasets, skills that are also valuable in security monitoring and SOC environments.


## Splunk Fraud Detection Dashboard Screenshots

### Dashboard 1
![Dashboard 1](screenshots/splunk%20fraud%20detection%20dashboard%201.png)

### Dashboard 2
![Dashboard 2](screenshots/splunk%20fraud%20detection%20dashboard%202.png)

### Dashboard 3
![Dashboard 3](screenshots/splunk%20fraud%20detection%20dashboard%203.png)

### Dashboard 4
![Dashboard 4](screenshots/splunk%20fraud%20detection%20dashboard%204.png)

### Dashboard 5
![Dashboard 5](screenshots/splunk%20fraud%20detection%20dashboard%205.png)

