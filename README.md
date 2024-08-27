# Predict Customer Churn Analysis using Logistic Regression and Random Forest
![Python](https://img.shields.io/badge/Python-3.8+-green)
![Jupyter Notebook](https://img.shields.io/badge/Tools-Jupyter%20Notebook-orange)
![Scikit-learn](https://img.shields.io/badge/Library-Scikit--learn-blue)
![Pandas](https://img.shields.io/badge/Library-Pandas-yellow)
![Matplotlib](https://img.shields.io/badge/Library-Matplotlib-lightblue)

## Project Overview

This project focuses on predicting customer churn using Logistic Regression and Random Forest algorithms. Customer churn is a critical metric for businesses, particularly those operating on a subscription model. By accurately predicting which customers are likely to churn, businesses can take preemptive actions to retain them, thereby improving customer retention rates and overall profitability

## Table of Contents

- [Introduction](#introduction)
- [Dataset Description](#dataset-description)
- [Data Preprocessing](#data-preprocessing)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Model Building](#model-building)
- [Model Evaluation](#model-evaluation)
- [Conclusion](#conclusion)
- [How to Run](#how-to-run)
- [Dependencies](#dependencies)
- [License](#license)

## Introduction

Customer churn, the process of customers discontinuing their relationship with a business, can significantly impact a company's revenue. This project applies machine learning techniques to predict customer churn using a dataset that includes customer demographics, service usage, and account information. The analysis lays the groundwork for understanding factors contributing to churn and helps in developing strategies to retain customers.

## Dataset Description

This is a ticket pricing monitoring system. It scrapes ticket pricing data periodically and stores it in a database. Ticket pricing changes based on demand and time, and significant price differences can exist. We are creating this product mainly with ourselves in mind. Users can set up alarms using an email, choosing an origin and destination (cities), time (date and hour range picker) choosing a price reduction over mean price, etc.

Following is the description for columns in the dataset**

-insert_date:     date and time when the price was collected and written in the database

-origin:              origin city

-destination:      destination city

-start_date:        train departure time

-end_date:         train arrival time

-train_type:         train service name

-price:                 price

-train_class:      ticket class, tourist, business, etc.

-fare:                  ticket fare, round trip, etc

dataset link : https://www.kaggle.com/datasets/muhammadyasirsaleem/tickets-pricing-monitoring-system-dataset

## Data Preprocessing

Data preprocessing steps included:
- Handling missing values
- Encoding categorical variables (e.g., travel class, train type)
- Scaling numerical features (e.g., travel distance)

## Exploratory Data Analysis

In this section, the relationships between different features and ticket prices were analyzed. Visualizations and statistical methods were used to identify trends, correlations, and outliers in the data.

## Model Building

A Linear Regression model was built using Scikit-learn. The model was trained on the preprocessed dataset, using the features mentioned above to predict the train ticket prices.

## Model Evaluation

The model's performance was assessed using various metrics:
- **Mean Absolute Error (MAE)**
- **Mean Squared Error (MSE)**
- **R-squared (R²)**

These metrics helped evaluate the accuracy and effectiveness of the model.

## Conclusion

The Linear Regression model provided a good prediction of train ticket prices based on the selected features. This model can be further improved by incorporating additional data or using more complex algorithms.

## How to Run

To run the project:
1. Clone this repository.
2. Install the required dependencies.
3. Open the Jupyter Notebook and execute the cells to train and evaluate the model.

```bash
git clone https://github.com/yasirsaleem502/Train-Ticket-Price-Predicition-using-Linear-Regression.git
cd Train-Ticket-Price-Prediction
pip install -r requirements.txt
jupyter notebook
