# Phase 3 Project Description



## Overview

During this project, we will be building models for prediction companies bunkruptcy based on given set of financial features. For the sake of research, we will use the following dataset: 

https://www.kaggle.com/code/kaixiongf/company-bankruptcy-w-pycaret

The data collected from the Taiwan Economic Journal for the years 1999 to 2009 and to see what insight can be generated during data exploration and which model is able to predict company bankruptcy most accurately.
 
We will employ: 
 - Logistic Regression, 
 - KNN, 
 - Decision Tree, 
 - SMOTE and 
 - Random Forest. 
 

***

## Business Problem

The customer, Restructuring Investment Bank, wants to increase the precision of their forecast for their customers, debtors (the distressed companies), and creditors (banks, lenders) when capital structure issues arise, which primarily stem from over-leveraged companies with insufficient liquidity to meet their obligations.

We will build different models based on the given dataset of portfolio companies. 

***

## Findings


Due to the very strong effect of the data imbalance, it's hard to build a reliable model for companies' bankruptcy using a given dataset. 

## Further investigation:

We suggest further investigation of how features such as:

Net Income to Total Assets 
Debt Ratio
Inventory to Current Liability
Interest Expense Ratio
Cash Turnover Rate
Total Assets Price
Net Value per Share
Net (after tax) Continues Interest  Rate
Current Liability to Equity
Operating Funds to Liability


## Repository Structure

├── README.md                  <- The top-level README for reviewers of this project
├── project.ipynb              <- Narrative documentation of analysis in Jupyter notebook
├── presentation.pdf           <- PDF version of project presentation
├── data.csv                   <- Dataset
└── project.pdf                <- PDF version of the Jupyter Notebook
 
