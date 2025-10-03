# Customer Lifetime Value (CLV) Calculation and Segmentation
## Objective:

This project calculates the Customer Lifetime Value (CLV) for each customer segment (e.g., churned vs. non-churned) to help businesses understand the value each customer brings over time. The project leverages data on total purchase value and purchase frequency to estimate CLV and visualizes it across customer segments.

## Key Steps:

### Data Preprocessing:

The dataset includes customer behavior data, with fields such as Churn, Total Purchase Value Per Customer, and Number of Purchases.

The data is grouped by the Churn column (indicating whether a customer has churned or not).

### Calculation of Key Metrics:

Average Purchase Value (APV): The mean total purchase value per customer is calculated for each churn segment.

Purchase Frequency (PF): The average number of purchases per customer is calculated for each churn segment.

Retention Rate: A retention rate (e.g., 70%) is set to estimate how likely customers are to stay engaged.

CLV Formula:

CLV = APV × PF × Retention Rate

CLV is then calculated for each customer segment and added to the dataset.

## Visualization:

A bar plot is generated to visualize the Customer Lifetime Value (CLV) across customer segments (churned vs. non-churned).

## Results:

CLV Calculation: The CLV is calculated for each customer segment based on the formula.

Visualization: A bar plot visually represents the CLV for churned and non-churned customer segments.
