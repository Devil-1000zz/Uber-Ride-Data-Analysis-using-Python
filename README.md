Overview:
This project involves exploratory data analysis (EDA) on Uber ride data using Python, leveraging libraries such as Pandas, NumPy, Matplotlib, and Seaborn. 
The primary goal is to identify meaningful insights, visualize patterns, and inform strategic decisions for ride management and resource allocation.

Dataset:
File: UberDataset.csv

Records: 1,156 Uber ride entries.

Features: Include ride categories, distance, timestamps, and purpose (business/personal).

Tools & Libraries:
Python

Jupyter Notebook

Pandas

NumPy

Matplotlib

Seaborn

Analysis Performed:
Data Cleaning and Preprocessing

Handled null values and duplicates.

Timestamp formatting and feature engineering (time-of-day categories).

Visualization and Insights

Time-series plots for identifying peak hours (10 AM - 5 PM) and seasonal variations.

Bar plots and heatmaps highlighting patterns such as higher business usage (>60%) and minimal winter activity (Nov-Jan).

Analysis of ride distance showing median around 4-5 miles.

Correlation Analysis

Revealed negative correlation between business and personal rides, guiding targeted marketing.

How to Run:
1. Install dependencies:
pip install pandas numpy matplotlib seaborn jupyter

2. Navigate to the project folder and launch the Jupyter notebook:
jupyter notebook Uber_Rides_Data_Analysis_using_Python.ipynb

Files in this Repository:
UberDataset.csv: Original dataset used.

Uber_Rides_Data_Analysis_using_Python.ipynb: Jupyter notebook with detailed analysis.

Project_Execution.pdf: Step-by-step documentation of project execution.

Key Outcomes:
Actionable insights for resource and driver allocation.

Reusable code framework for future monthly analysis.

