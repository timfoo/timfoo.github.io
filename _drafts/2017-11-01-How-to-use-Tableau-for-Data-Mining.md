---
title: "How to use Tableau for Data Mining"
header:
  #image: /assets/images/data-img.jpg
  #caption: "Photo credit: [**StockSnap.io**](https://stocksnap.io/)"
categories:
  - Tableau
  - Data
tags:
  - Tableau
  - Data Mining
---

## Describing the Data

[Download the data](http://www.superdatascience.com/wp-content/uploads/2015/08/Churn-Modelling.xlsx)

This excel sheet has a few headers:
- **Row Number** - Each row is a unique customer
- **Customer ID** - Unique customer ID
- **Surname** - Customer's last name
- **Credit Score** - Customer's credit score
- **Gender** - Customer's gender
- **Age** - Customer's  age
- **Tenure** - Term with the bank
- **Balance** - Account balance
- **NumOfProducts** - Number of products with the bank
- **HasCrCard** - Does the customer have a credit card?
- **IsActiveMember** - Has the customer exhibited activity in the past month?
- **EstimatedSalary** - Estimated salary of the customer
- **Exited** - Whether or not they have left the bank.

*Note*: Tableau may automatically recognize "Exited" as a measure, not a dimension. In this case, "Exited" is a category and should be moved into the Dimensions category.

## Simple A-B Testing
