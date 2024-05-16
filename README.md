# Customer Insights and Marketing Strategies

## Introduction
This repository contains code for unlocking customer insights and implementing data-driven marketing strategies for business growth. It covers various aspects including customer segmentation, sales forecasting, association rules for product recommendations, shelf arrangement strategies, churn prediction, and churn risk analysis.

## Setup and Requirements
- Python 3.x
- Libraries:
  - pandas
  - scikit-learn
  - statsmodels
  - mlxtend
  - matplotlib
  - seaborn
  - networkx
  - pmdarima

Install the required libraries using:
```
pip install  pandas scikit-learn statsmodels mlxtend matplotlib seaborn networkx pmdarima
```

## Usage
1. Clone the repository:
```
git clone https://github.com/shivanshtri010/CustomerInsightsStrategies.git
```
2. Navigate to the cloned directory:
```
cd CustomerInsightsStrategies
```
3. Run the Jupyter Notebook `customer_insights_marketing.ipynb` to execute the code and analyze the data.

## Contents
- `customer_insights_marketing.ipynb`: Jupyter Notebook containing the code for customer insights and marketing strategies.
- `customer_transactions_sample.xlsx`: Sample dataset containing customer transaction records.(https://docs.google.com/spreadsheets/d/1-31wL1vkNU8-yxfc2ItAX6KE4Re7RuUP/edit?usp=drive_web&ouid=108182797203391057464&rtpof=true)

## Data
The dataset (`customer_transactions_sample.xlsx`) includes information about customer transactions, such as Invoice ID, Stock Code, Quantity, Price, Invoice Date, and Country.

## Results
- **Customer Segmentation**: Identified clusters of customers based on Recency, Frequency, and Monetary Value.
- **Sales Forecasting**: Forecasted future sales using ARIMA and Exponential Smoothing models.
- **Association Rules**: Generated product recommendations using association rules mining.
- **Churn Prediction**: Built a logistic regression model to predict customer churn.
- **Churn Risk Analysis**: Analyzed churn risk by country and month.
