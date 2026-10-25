Advertising Spend and Sales Analysis
A Python project exploring the relationship between advertising spending and sales, using data visualization and simple linear regression.
Project Overview
This project examines advertising spending across TV, radio, and newspapers, then builds a regression model to predict sales from TV advertising spend.

The analysis was developed in Jupyter Notebook as a learning project.
Dataset
The dataset contains 200 records with four variables:
- TV: TV advertising spend
- Radio: Radio advertising spend
- Newspaper: Newspaper advertising spend
- Sales: Recorded sales
Input file: Company_data.csv

Tools and Libraries
- Python
- pandas and NumPy
- Matplotlib and Seaborn
- scikit-learn
- statsmodels
- 
Analysis Workflow
1. Parsed the input data and converted columns to numeric values.
2. Reviewed data types and descriptive statistics.
3. Created scatterplots and a correlation heatmap.
4. Split the data into 70% training and 30% testing sets.
5. Built a simple linear regression model using TV advertising spend.
6. Examined residual plots to assess model fit.
7. Evaluated predictions using R².
8. Implemented the model with both statsmodels and scikit-learn.
