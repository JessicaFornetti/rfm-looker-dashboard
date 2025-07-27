# rfm-looker-dashboard

This project involves a comprehensive RFM (Recency, Frequency, Monetary) analysis of the following [default GCP e-commerce dataset](https://www.kaggle.com/datasets/mustafakeser4/looker-ecommerce-bigquery-dataset/data?select=events.csv) using GCP and Looker Studio.

The main steps of the project are outlined below:
- **Local Data Setup**: Loading the dataset into a local SQLite database and defining appropriate table schemas for data integrity
- **Exploratory Data Analysis** : Performing initial data exploration, descriptive statistics, analysis of missing values, and examination of categorical distributions
- **SQL Queries**: Exploration of each relevant table to understand the data better through numerous SQL queries
- **RFM Calculation and Customer Segmentation**: Refining of the RFM query in the local SQLite database and then on GCP: calculating Recency, Frequency, and Monetary values for customers and segmenting them into various categories ('Champions', 'Loyal Customers', 'At Risk', etc ...) based on their RFM scores
- **Looker Studio Dashboard**: A dashboard providing interactive visualizations with filters of key points in the RFM analysis.

Below are screenshots of each page of the current dashboard: 
- **Customer Segment Distribution Breakdowns** <img width="523" height="423" alt="image" src="https://github.com/user-attachments/assets/847294a0-cec5-4242-85af-ec3872782d81" />
- **Average RFM Metrics By Customer Segment** <img width="503" height="431" alt="image" src="https://github.com/user-attachments/assets/5e413da8-da67-417a-986b-e32e7d64cf74" />
- **Customer Segment Value & Spending Insights** <img width="554" height="439" alt="image" src="https://github.com/user-attachments/assets/acb54f21-34e1-4c33-9ceb-9e9077433afd" />
- **Top 25 Cutomers By Monetary Value** <img width="592" height="429" alt="image" src="https://github.com/user-attachments/assets/15f4988d-469c-4d63-957d-0de8d68d0238" />
- **Top 25 Cutomers By RFM Score** <img width="593" height="427" alt="image" src="https://github.com/user-attachments/assets/89ec5fe3-3625-4d3e-bad4-eab25f0036a3" />

# Repository Overview
This repository contains [1 Jupyter notebook](Notebook.ipynb) and the full dashboard can be found [here](https://lookerstudio.google.com/reporting/0dc70163-4b22-491c-a2f4-de37fb6b7158).
