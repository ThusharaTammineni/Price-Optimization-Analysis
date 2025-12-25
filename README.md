# Price-Optimization-Analysis
Price Optimization Analysis using Regression and Price Elasticity
Project Overview

Pricing directly influences customer demand and overall business revenue. This project applies statistical regression techniques to analyze the relationship between product price and demand, estimate price elasticity, and identify an optimal price point that maximizes revenue.

The analysis is performed using historical retail sales data and focuses on demonstrating a structured, data-driven approach to pricing decisions.

**Objectives**

Analyze how price impacts product demand

Estimate price elasticity using regression analysis

Identify the price that maximizes revenue

Visualize revenue behavior across different price levels

Provide business-oriented pricing recommendations

**Dataset**

Source: Kaggle – Retail Sales Dataset

Key Features Used:

Price per Unit – Selling price of the product

Quantity – Number of units sold

Total Amount – Transaction value

Since proprietary data was not provided, a publicly available dataset was used to demonstrate the methodology.

**Methodology**
**1. Data Loading & Cleaning**

Loaded historical sales data from CSV

Removed missing, zero, and invalid price or quantity values

Created a derived Revenue variable

**2. Exploratory Data Analysis**

Visualized the relationship between price and quantity

Observed an inverse relationship consistent with demand theory

**3. Linear Regression (Baseline Model)**

Modeled the absolute relationship between price and quantity

Verified the expected negative price–demand relationship

Evaluated statistical significance and model fit

**4. Log–Log Regression (Elasticity Model)**

Applied logarithmic transformation to price and quantity

Estimated price elasticity of demand directly from regression coefficients

Interpreted elasticity in percentage terms for pricing decisions

**5. Revenue Optimization**

Simulated multiple price points

Predicted demand using the elasticity model

Calculated expected revenue for each price

Identified the revenue-maximizing price

Visualized revenue vs price behavior

Applied logarithmic transformation to price and quantity

Estimated price elasticity of demand directly from regression coefficients

Interpreted elasticity in percentage terms for pricing decisions

**price-optimization-analysis/**
│
├── retail_sales_dataset.csv
├── Price_Optimization_Analysis.ipynb
└── README.md

**Conclusion**

This project demonstrates how regression analysis and price elasticity concepts can be applied to real sales data to support informed pricing decisions. The approach highlights how data-driven methods can guide revenue optimization under clearly stated assumptions.
