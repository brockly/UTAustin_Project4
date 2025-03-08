# Bank Churn Prediction

## Overview
This repository contains the **Bank Churn Prediction** project, completed as part of the Introduction to Neural Networks course offered by Great Learning in collaboration with UT Austin. The goal of the project is to build a neural network-based classifier to predict customer churn in the banking sector.

## Context
Banks frequently face the issue of customer churn, which involves customers leaving their current bank to join another service provider. Understanding what influences customers to churn is crucial to improving customer retention by focusing efforts on critical service aspects.

## Objective
The project's objective is to build a neural network model to predict whether customers are likely to leave the bank within the next six months. This predictive capability will enable proactive customer retention strategies.

## Data Dictionary

The dataset includes the following attributes:

| Attribute         | Description                                                               |
|-------------------|---------------------------------------------------------------------------|
| `CustomerId`      | Unique identifier for each customer                                       |
| `CreditScore`     | Customer’s credit history score                                           |
| `Geography`       | Customer’s geographical location                                          |
| `Gender`          | Gender of the customer                                                    |
| `Age`             | Age of the customer                                                       |
| `Tenure`          | Number of years the customer has been associated with the bank            |
| `NumOfProducts`   | Number of banking products used by the customer                           |
| `Balance`         | Current account balance                                                   |
| `HasCrCard`       | Whether the customer has a credit card (0=No, 1=Yes)                      |
| `IsActiveMember`  | Whether the customer actively uses bank products (0=No, 1=Yes)            |
| `EstimatedSalary` | Estimated annual salary of the customer                                   |
| `Exited`          | Customer churn status (0=No, 1=Yes)                                       |

## Analysis & Modeling Steps
- Exploratory data analysis and data preprocessing
- Feature engineering and selection
- Model construction using neural networks (TensorFlow/Keras)
- Model evaluation, tuning, and interpretation

## Tools and Libraries
- Python 3.x
- Pandas
- NumPy
- Scikit-Learn
- TensorFlow / Keras
- Matplotlib
- Seaborn

## How to Use
1. Clone the repository:
```bash
git clone [repository_url]
```

2. Open the provided Jupyter Notebook file and execute the cells to replicate the analysis and neural network modeling.

---

**Author:** Alex Brockman  
**Course:** Introduction to Neural Networks, Great Learning @ UT Austin  
**Date:** June 2024

