# Supply Chain Analysis Using Python

**Data Analysis | Exploratory Data Analysis | Business Intelligence | Machine Learning**

## Overview

This project focuses on analyzing supply chain operations using Python to identify delivery delays, evaluate profitability, investigate operational bottlenecks, and predict late delivery risks.

The analysis uses historical supply chain data to generate meaningful business insights and support data-driven decision-making.

## Objectives

- Analyze overall supply chain performance.
- Identify late and on-time delivery patterns.
- Evaluate sales and profitability.
- Investigate factors influencing delivery delays.
- Analyze regional and shipping-mode performance.
- Predict late delivery risks using Machine Learning.

## Tech Stack

| Technology | Purpose |
|---|---|
| Python | Programming |
| Pandas | Data Manipulation |
| NumPy | Numerical Computing |
| Matplotlib | Data Visualization |
| Seaborn | Statistical Visualization |
| Scikit-learn | Machine Learning |
| Jupyter Notebook | Development Environment |

## Project Workflow

### 1. Data Collection
- Imported the dataset using Pandas.
- Inspected dataset structure and dimensions.

### 2. Data Cleaning & Preprocessing
- Checked missing values and duplicate records.
- Selected relevant analytical columns.
- Converted date columns into datetime format.
- Prepared data for analysis.

### 3. Exploratory Data Analysis (EDA)
- Order distribution analysis.
- Sales and profitability analysis.
- Delivery performance analysis.
- Regional performance analysis.

### 4. Feature Engineering

Created the following features:

- Order Processing Time
- Delivery Delay
- Is_Delayed
- Order Month
- Order Day
- Order Hour

### 5. Data Visualization

Developed charts to analyze:

- Profitability Distribution
- Delivery Delay Distribution
- Profit Analysis by Delay Days
- Monthly Late Delivery Trends
- Late Delivery by Weekday
- Regional Delivery Performance
- Shipping Mode Analysis

### 6. Root Cause Analysis

Investigated potential delivery delay factors:

- Shipping Mode
- Customer Segment
- Department Name
- Order Region
- Order Status
- Payment Type

### 7. Machine Learning

Implemented a Random Forest Classifier to predict late delivery risk using selected order and operational features.

## Key Business Insights

| Metric | Result |
|---|---:|
| Total Orders | 180,519 |
| Late Delivery Rate | 54.70% |
| On-Time Delivery Rate | 45.30% |
| Total Order Profit | $7.85M |
| Profit on Delayed Orders | $2.15M |
| Random Forest Accuracy | 73% |

### Key Findings

- Approximately 54.70% of orders experienced late delivery.
- Around 80.6% of orders were classified as profitable.
- Delivery delays persisted throughout the year.
- Shipping modes showed different delay patterns across regions.
- Operational improvements could help improve delivery performance.

*Note: Profit on delayed orders does not represent confirmed financial loss caused by delays.*

## Machine Learning Model

**Algorithm:** Random Forest Classifier

**Target Variable:** Late Delivery Risk

| Evaluation Metric | Score |
|---|---:|
| Accuracy | 73% |
| Precision | 0.78 |
| Recall | 0.75 |
| F1-Score | 0.75 |

The model provides an initial approach to identifying potential late deliveries. Further validation is recommended before practical deployment.

## Business Recommendations

1. Improve shipping and delivery operations.
2. Monitor shipping modes with higher delay rates.
3. Investigate regional delivery bottlenecks.
4. Optimize order fulfilment processes.
5. Strengthen predictive model validation.

## Conclusion

This project demonstrates the use of Python for supply chain data analysis, combining data cleaning, exploratory data analysis, data visualization, business insights, and predictive modelling.

It highlights how data analytics and machine learning can help identify operational challenges and support informed business decisions.

## Author

**Khushi Chaudhary**

B.Tech | Information Technology  
Aspiring Data Analyst
