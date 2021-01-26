# matplotlib-challenge
This study compares the performance of Pymaceuticals' drug of interest, Capomulin, versus several other treatment regimens:
  - 249 mice identified with SCC tumor growth were treated through a variety of drug regimens. 
  - Over the course of 45 days, tumor development was observed and measured. 
  - The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens.

The project consists of:
- a Jupyter notebook (MT_Pymaceuticals.ipnyb) that analyzes the mouse metadata and study results.
- the mouse metadata and study results stored in Resources\Study_results.csv and Resources\Mouse_metadata.csv

The Jupyter notebook contains:
- an analysis report (at the beginning of the notebook), 
- the Python code that organizes, analyzes, formats and visualizes the data using the Pandas, Matplotlib and Scipy.stats libraries  
- several tables and charts visualizing key metrics, trends and relationships between data:
  - Summary Statistics for each Drug regimen in the study
  - Bar Charts showing the number of measurements taken per Drug regimen
  - Pie Charts showing the breakdown of mice in the study by gender
  - Calculations of the quartiles and IQR for Average Tumor Volume in the 4 Drug regimens (Capomulin, Ramacane, Infubinol & Ceftamin) and identification of any outliers in this data 
  - Side-by-side Box and Whisker Plots visualizing these calculations  
  - A Line Plot showing the progression of tumor volume over the 45 days of treatment with Capomulin for Mouse 'm601'
  - A Scatter Plot showing the relationship between mouse weight and average tumor volume in the Capomulin study
  - Calculation of the correlation coefficient and linear regression model for these two variables
  
