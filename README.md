# Efficient Market Hypothesis (EMH) Testing

## Overview:
This project evaluates whether firm-level financial characteristics can predict future stock returns, thereby testing the Efficient Market Hypothesis (EMH).

Using data from 142 firms (2014–2018), the study applies OLS regression to examine relationships between stock returns and financial variables such as profitability, leverage, earnings, and CEO compensation.


## Objective:
To determine whether firm-specific financial characteristics contain predictive information about future stock returns.


## Variables Used:

### Dependent Variable:
- Stock Returns (2014–2018)

### Independent Variables:
- Return on Equity (ROE)
- Return on Capital (ROC)
- Debt-to-Capital Ratio (DKR)
- Earnings Per Share (EPS)
- Net Income
- CEO Total Compensation(sal)


## Methodology:
- Descriptive Statistical Analysis
- Correlation Analysis
- OLS Regression Modeling
- Log Transformation of Skewed Variables
- Model Evaluation using R², Adjusted R², and p-values


## Tools Used:
- Microsoft Excel
- Excel Data Analysis ToolPak


## Key Findings:
- Most variables were not statistically significant at the 5% level.
- Results broadly support the Efficient Market Hypothesis.
- Some evidence of partial predictability was observed in select financial indicators.


## Repository Contents:
- `EMH_Report.pdf` → Complete project report and regression analysis
- `data/` → Dataset used for the study
- `charts/` → Correlation analysis and visualizations
