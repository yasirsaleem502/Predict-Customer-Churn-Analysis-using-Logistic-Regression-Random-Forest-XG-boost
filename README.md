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
- [Modelling](#modelling)
- [Model Evaluation](#model-evaluation)
- [Conclusion](#conclusion)
- [Dependencies](#dependencies)
- [How to Run](#how-to-run)

## Introduction

Customer churn, the process of customers discontinuing their relationship with a business, can significantly impact a company's revenue. This project applies machine learning techniques to predict customer churn using a dataset that includes customer demographics, service usage, and account information. The analysis lays the groundwork for understanding factors contributing to churn and helps in developing strategies to retain customers.

## Dataset Description

Companies want to improve and maintain a healthy relationship and environment for their employees. This can be achieved by recognizing and understanding the important factors that are associated with employee turnover and taking care of them might add into the productivity and growth of the employees. These insights can help managers for grabing the opportunity to take corrective steps to build and preserve their successful business.

Column Description

-**satisfacion_level**:           Showing satisfaction of a particular employee

-**last_evaluation**:             Showing last evaluation of a particular employee

-**number_project**:              Showing number of projects handled a particular employee

-**average_montly_hours**:        Showing the monthly hours that were spent the particular employee

-**time_spend_company**:         Shows the number of years spent by the particular employee in the company.

-**Work_accident**:             Showing an employee has whether been part of the company or not.

-**left**:                     Tells either and employee has left the company or not. Shows two values 0= not left, 1= left

-**promotion_last_5years**:   Shows that the whether the employee has got any promotion in the last 5 years or not.

-**dept**:                    Shows the departments

-**salary**:                  Shows the salary type of the employee


## Data Preprocessing

To prepare the data for modelling, the following steps were taken:

**Handling Missing Values**: Imputing missing values or removing rows/columns with missing data.

**Encoding Categorical Variables**: Transforming categorical features into numerical formats using one-hot encoding.

**Feature Scaling**: Normalizing numerical features to improve model performance.

**Data Splitting**: Dividing the dataset into training and testing sets to evaluate the models.


## Exploratory Data Analysis

Exploratory Data Analysis (EDA) helps uncover patterns, correlations, and relationships within the data. Key aspects include:

-**Distribution Analysis**: Understanding the spread and central tendency of features.

-**Correlation Matrix**: Visualizing correlations between different features.

-**Churn Rate Analysis**: Investigating how features like contract type, tenure, and charges relate to churn.


# Modelling

**Logistic Regression**:
Logistic Regression is employed as a baseline model for churn prediction. It is a linear model particularly effective for binary classification tasks like this one.

**Random Forest**:
Random Forest, an ensemble method, builds multiple decision trees and merges them to provide a more accurate and stable prediction. It handles large datasets with numerous features efficiently and captures complex interactions between variables.

# Model Evaluation
The models are evaluated using several metrics:

-Accuracy: The ratio of correctly predicted instances to the total instances.

-Precision: The ratio of correctly predicted positive observations to the total predicted positives.

-Recall: The ratio of correctly predicted positive observations to all observations in the actual class.

-F1-Score: The weighted average of Precision and Recall.

-ROC-AUC Score: The area under the Receiver Operating Characteristic curve, indicating model performance in distinguishing between the classes.

# Conclusion
This project demonstrates the effectiveness of Logistic Regression and Random Forest in predicting customer churn. By identifying key factors influencing churn, businesses can implement targeted strategies to retain customers and reduce churn rates.

# Dependencies
This project requires the following libraries:

-Python 3.8+

-Jupyter Notebook

-Pandas

-Scikit-Learn

-Seaborn

-Matplotlib

-NumPy


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
