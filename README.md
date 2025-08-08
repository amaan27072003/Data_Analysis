Data Analysis Project
Overview
This repository contains Python scripts demonstrating fundamental data analysis and visualization techniques using the pandas and matplotlib libraries. The project was built to showcase how to adapt analysis methods to different types of datasets, from salary information to auto sales figures.

What Was Built
The project contains two distinct data analysis pipelines:

Salary Data Analysis: A script that loads Salary_Data.csv and visualizes the relationship between "Years of Experience" and "Salary." It uses a scatter plot with a linear regression line to demonstrate a strong positive correlation, and the code also calculates the correlation coefficient.

Auto Sales Data Analysis: A script that loads Auto Sales data.csv and analyzes total sales by product line. It uses the powerful groupby() and sum() methods from pandas to aggregate data and then generates a bar chart to visualize which product lines are the most profitable.

Why It Was Built
This project was developed to provide a practical example of key data analysis concepts. It serves as a clear demonstration of:

Loading and inspecting data with pandas.

Adapting analysis methods to different data types (numerical vs. categorical).

Using groupby() and aggregation functions like sum() to derive insights.

Creating meaningful data visualizations with matplotlib to tell a story with data.

How to Run the Code
To run the code in this repository, you will need to have Python installed along with the following libraries:

pandas

matplotlib

numpy

You can install these using pip:

pip install pandas matplotlib numpy

Once the dependencies are installed, simply place the Salary_Data.csv and Auto Sales data.csv files in the same directory as the Python scripts and run them directly.