# SyriaTel Customer Churn

## Business Overview

SyriaTel is a leading provider of telecommunications services in the United States. It offers a wide range of services, including wireless, wireline, and internet services. The company has been in business for over 50 years and has a strong customer base.

## Problem Statement

In recent years, the company has been facing an issue with customer churn. Churn is the rate at which customers cancel their service with a company. The company's churn rate has been increasing over the past few years. This is a major concern for the company because it is losing revenue and customers.

## Objectives

The goal of this project is to:-

- Predict customers who are likely to churn. This will help the company to identify customers who are at risk of leaving and take steps to prevent them from leaving.
- Check for relationship between various variables and churn.

## Data Understanding and Analysis

### Source of Data

- The data used can be found [here](https://www.kaggle.com/datasets/becksddf/churn-in-telecoms-dataset)
- The features of the dataset are explained [here](Data.md)

### Exploratory Data Analysis

- Our data had 21 features that we worked with to come up with the best predictive model.
- We started by analyzing each of the features individually by looking at their characteristics and distribution.
- As part of preparing our data for analysis and modeling, we cleaned it as outlined stepwise in our notebook.
- Next, we looked at the relationship amongst the individual variables with churn.
- Checked for outliers and multicollinearity

### Data Visualization

#### Area code with the highest churn

![area_code_churn](images/area_code_churn.png)

#### States with the highest churn

![States_churn](images/states_churn.png)

#### Distribution of numeric variables

![Numeric_distribution](images/numeric_dist.png)

## Modelling

- Before modelling our data that had categorical variables, we one hot encoded them and also scaled the data
- The data was modelled against three models namely, a logistic regression model (baseline model), a random forest model and hyperparameter tuned random forest model.

- Here is their ROC curves of the three models

![Roc](images/roc.png)

## Challenges

## Conclusion

## Recommendations

## Future work
