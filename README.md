# Rocket_Launch_Success

## About the Project
This project investigates the relationship between environmental and site-specific factors and the success of rocket launches. Using publicly available launch and weather data, we assess whether variables like wind speed, precipitation, and temperature meaningfully affect launch outcomes. The analysis is performed using linear regression techniques, with model refinement through backward elimination, F-tests, and variance inflation factor (VIF) analysis.

## What We Built
A dataset combining launch outcomes with weather data and site characteristics

A multiple linear regression model to predict launch success

Conducted diagnostic checks for regression assumptions (linearity, multicollinearity, residuals)

Improved model interpretability by iteratively dropping insignificant predictors using F-tests and VIF

Final model identifies key predictors with the greatest influence on launch success

## Tools & Libraries
Python

pandas, numpy

statsmodels

matplotlib

## Files in This Repository
part3-1.rmd: Code notebook with full data processing, analysis, and regression modeling

Final Report.pdf: Our project report detailing background, methodology, results, and interpretations

Flowchart.pdf: Visual representation of our project pipeline

## Dataset
Launch data from Kaggle (filtered for post-2000 launches)

Manually compiled launch site characteristics

