# Anthropometric Analysis of Height and Arm Length
This repository contains an analysis of height and arm length data, exploring their relationship and the influence of gender.

## Project Overview
The project analyzes a dataset of height and arm length measurements and gender information. The analysis includes data cleaning, summary statistics, correlation analysis, various regression models, and an examination of the arm-to-height ratio.

## Data
The analysis uses data from an Excel file containing height and arm length measurements and gender for a sample of individuals.

## Analysis Steps
The analysis involved several stages:

- Data Preparation: The raw data was loaded and cleaned to remove extraneous information, standardize formats, and prepare it for analysis.
- Descriptive Analysis: Summary statistics for height and arm length were calculated for the entire sample and separated by gender to understand the basic characteristics of the data.
- Relationship Exploration: The correlation between height and arm length was examined.
- Regression Modeling:
  - Simple linear regression was used to model the relationship between height and arm length.
  - Multiple linear regression was conducted to include gender as a predictor.
  - Ridge and Lasso regression were applied as regularization techniques.
  - ANCOVA was used to investigate if the relationship between height and arm length differs significantly between genders by including an interaction term.
- Robustness Check: Regression models were re-run after identifying and excluding influential data points to check the stability of the results.
- Ratio Analysis: The arm-to-height ratio was calculated, its distribution analyzed, and a t-test was performed to compare the ratio between genders.
- Model Comparison: The performance and results of the different regression models were compiled and compared.
- Model Diagnostics: Residuals from the final model were analyzed visually to check model assumptions.



