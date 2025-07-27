# rfm-looker-dashboard

This project involves a comprehensive RFM (Recency, Frequency, Monetary) analysis of the following [default GCP e-commerce dataset](https://www.kaggle.com/datasets/mustafakeser4/looker-ecommerce-bigquery-dataset/data?select=events.csv) using GCP and Looker Studio.

The main steps of the project are outlined below:
- **Local Data Setup**: Loading the dataset into a local SQLite database and defining appropriate table schemas for data integrity
- **Exploratory Data Analysis** : Performing initial data exploration, descriptive statistics, analysis of missing values, and examination of categorical distributions
- **SQL Queries**: Exploration of each relevant table to understand the data better through numerous SQL queries
- **RFM Calculation and Customer Segmentation**: Refining of the RFM query in the local SQLite database and then on GCP: calculating Recency, Frequency, and Monetary values for customers and segmenting them into various categories ('Champions', 'Loyal Customers', 'At Risk', etc ...) based on their RFM scores
- **Looker Studio Dashboard**: A dashboard providing interactive visualizations of key points in the RFM analysis.

Here is are screenshots of the pages of the dashboard: 
- **Customer Segment Distribution Breakdowns**
<img width="523" height="423" alt="image" src="https://github.com/user-attachments/assets/847294a0-cec5-4242-85af-ec3872782d81" />
- **Average RFM Metrics By Customer Segment**
- **Customer Segment Value & Spending Insights**
- **Top 25 Cutomers By Monetary Value**
- **Top 25 Cutomers By RFM Score**

# Repository Overview
This repository contains [1 Jupyter notebook](Notebook.ipynb) and the full dashboard can be found [here](https://lookerstudio.google.com/reporting/0dc70163-4b22-491c-a2f4-de37fb6b7158).
