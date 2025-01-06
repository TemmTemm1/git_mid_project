## Heart Disease Data Analysis - Mid Project - Rotem Hajaj

### Project Description

**This project analyzes a dataset on heart disease and explores the relationships between various factors like age, gender, exercise habits, smoking, and family history with the occurrence of heart disease.**

**The project is written in Jupyter Notebook and divided to sections -**
1. Importing relevant packages and lib.
2. Data Observation and Verification - showing the size of data, statistics, data type and unique values in columns. 
3. Data Cleaning - choosing the relevant columns for the analysis, checking duplicates, dropna, filling null values with the mean of numerical columns and data types changes.
4. Plot - General plots for showing the distribution of age and gender in all data. also, creating age groups to show the count of people with heart disease for each age group.
5. Interactive Plot 1 - showing the relationship between Heart Disease Status and Smoking/Family Heart Disease by user selection. the user choosing 1 for Smoking or 2 for Family Heart Disease and matches the choice by the boolplot function. the function includes excetions.
6. Interactive Plot 2 - Plotting Avg prcnt of heart disease with selected column that includes ranges (low,high,medium...). the user choosing 1 for Exercise Habits, 2 for Stress Level, 3 for Sugar Consumption. in the avgprcnt function - I created a list that holds the values of the columns, and then implement it in the plot attributes with the formula x-1, for getting the values from the index of the list. the function includes excetions.
7. Output the result into json file.




 

