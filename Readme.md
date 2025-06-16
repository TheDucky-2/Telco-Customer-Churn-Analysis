# Customer Churn Analysis Project

This project analyzes customer churn data using Python for data cleaning and transformation, and Power BI for visualization and insights.

## Table of Contents

- [Overview]
- [Dataset]
- [Technologies Used]
- [Data Cleaning and Transformation]
- [Exploratory Data Analysis]
- [Power BI Dashboard]
- [Results & Insights]
- [How to Run]
- [Future Work]

## Overview

The goal of this project is to analyze customer churn to identify key factors contributing to churn risk and provide actionable business insights.

## Dataset

- **Source**

   https://www.kaggle.com/datasets/blastchar/telco-customer-churn


- **Features**:

- **CustomerID**: Unique identifier for each customer
- **Gender**: Customer gender (Male/Female)
- **SeniorCitizen**: Indicates whether the customer is a senior citizen
- **Partner**: Whether the customer has a partner
- **Dependents**: Whether the customer has dependents
- **Tenure**: Number of months the customer has stayed
- **PhoneService**: Whether the customer has phone service
- **MultipleLines**: Multiple phone lines indicator
- **InternetService**: Type of internet service subscribed
- **OnlineSecurity**: Whether online security is active
- **OnlineBackup**: Whether online backup is active
- **DeviceProtection**: Whether device protection is active
- **TechSupport**: Availability of technical support
- **StreamingTV**: Access to streaming TV
- **StreamingMovies**: Access to streaming movies
- **Contract**: Type of contract (month-to-month, one year, two year)
- **PaperlessBilling**: Indicates if billing is paperless
- **PaymentMethod**: Payment method used by the customer
- **MonthlyCharges**: Monthly charges billed to the customer
- **TotalCharges**: Total charges billed to the customer
- **Churn**: Target variable indicating if customer churned (Yes/No)

  
## Technologies Used

- **Python (Jupyter Notebook)**: Data cleaning, feature engineering, exploratory data analysis
- **Pandas**: Data manipulation
- **Power BI**: Interactive dashboards and advanced visualizations
- **Git/GitHub**: Version control

## Data Cleaning and Transformation

Performed the following steps:
- Remoes
- Feature engineering (e.g.,ved duplicates and null values
- Converted categorical variabl tenure groups, contract types)
- Normalized numerical fields

## Exploratory Data Analysis

- Distribution of churn vs non-churn customers
- Correlation analysis
- Key indicators for churn

## Power BI Dashboard

The Power BI dashboard includes:
- Overview of churn rate
- Customer demographics
- Service usage patterns
- Payment methods and contract types
- Key churn drivers

## Results & Insights

Observations:

Churn Rate is 26.54% overall out of 7043 customers.
Churn Rate is 42.71% for month to month contracts, which is the highest among all the contract types.
Month-to-month contracts have a churn of 54.64% for senior citizens, as opposed to 15.26% for one year and 4.14% two year contracts.
Month to Month contracts have 44.69 % churn rate without a partner added as opposed to the churn rate 39.13% if with a partner.
Across all the contracts, the churn rate is 19.66% with a partner as opposed to 32.96% if no partner is added to the contract.
Also, the churn rate for senior citizens is 34.55% if a partner is added to the contract as opposed to 48.86% if no partner is added.
Customers with lower tenure like 15 months are more likely to churn, across month-to-month contracts.

Insights:

Since month to month contracts offer freedom to cancel and flexibility to leave, customers are more likely to churn as they could be trying the service or leaving right after promotion offer ends.
Senior citizens are more likely to churn without a partner with a tenure of less than 12 months.
Customers with two year contract are least likely to churn.


Recommendations: 

For month-to-month contracts, offer retention incentives like "one free month after 3 paid months" or flexible free-month vouchers customers can use anytime during service disruptions or personal hardship.
For annual contracts, offer 1-2 flexible free months per year that can be redeemed anytime, giving customers more control and improving satisfaction.
Develop partner-based incentives: offer special discounts or benefits for adding partners to contracts, especially targeting senior citizens who show reduced churn when partners are involved.


## How to Run

1. Clone this repository:
   
   https://github.com/TheDucky-2/Telco-Customer-Churn-Analysis.git
