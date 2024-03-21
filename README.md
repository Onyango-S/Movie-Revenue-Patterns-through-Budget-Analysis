# Decoding Movie Revenue Patterns through Budget Analysis


This project aims to uncover insights from the connection between movie budgets and gross revenue in the film industry. By using Ordinary Least Squares Regression, we'll analyze a dataset sourced from Kaggle.

## Project Questions

1. Does the relationship between the budget and gross revenue of movies follow a linear pattern?
2. Are both the budget and gross revenue variables normally distributed?
3. How is the Ordinary Least Squares (OLS) approach applied to estimate the parameters of the linear regression model?
4. What is the y-intercept and slope?
5. What is the Linear Expression that would express the relationship between the budget and the gross revenue in the form of y = mx + c?
6. How well does the budget explain the variability in gross revenue?
7. Are the residuals of the regression model normally distributed?
8. Does the variability in the residuals of the regression model remain consistent across different budget levels?
9. What insights can be drawn from the summary of the regression model results, particularly regarding the coefficients, p-values, and goodness-of-fit measures?

## Processes

### Data Preparation

I imported the requisite libraries and loaded the dataset into our notebook. The objective was to ensure data integrity and explore key variables. Through comprehensive data cleaning and exploratory analysis, I aimed to verify the suitability of the dataset for regression analysis, focusing particularly on the budget and gross revenue columns.

### Model

Verified the assumption of linearity, as it is a prerequisite for our analysis. Upon confirming that this assumption holds true, I proceeded with regression modeling using the dataset.

### Outcomes

The model indicates that for every additional dollar allocated to the budget, there is an average increase of $3.3351 million in gross revenue. This relationship is statistically significant, with a very low p-value of 0.000, suggesting a strong relation between the two variables. The overall model explains approximately 54.8% of the variability in gross revenue, demonstrating the substantial impact of budget allocation on revenue generation.

View code : https://github.com/Onyango-S/Movie-Revenue-Patterns-through-Budget-Analysis/blob/main/budget_vs_revenue_insights.ipynb
