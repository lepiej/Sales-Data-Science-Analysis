# Background Information
This repository was forked from KeithGalli/Pandas-Data-Science-Tasks, which provided the original datasets and instructions on how to solve business questions using Pandas. The data sets were cleaned up and analyzed in this forked repository to answer the specific questions listed below. The original repository contains a series of Jupyter notebooks with step-by-step instructions and code snippets for solving a variety of data science tasks using Pandas, and is a valuable resource for anyone looking to improve their Pandas skills.

# Input Section
In this project, I analyzed a dataset of sales data using Python Pandas & Python Matplotlib and answered business questions about 12 months worth of sales data, following the instructions provided by KeithGalli. The data contains hundreds of thousands of electronics store purchases broken down by month, product type, cost, purchase address, etc.

I started by cleaning the data, removing any missing or duplicate values and converting the data types as needed. I then conducted several analyses to answer the following business questions:

- What was the best month for sales? How much was earned that month?
- What city sold the most product?
- What time should we display advertisemens to maximize the likelihood of customer’s buying product?
- What products are most often sold together?
- What product sold the most? Why do you think it sold the most?

To answer these questions I've used folowing pandas & matplotlib methods:

- Concatenating multiple csvs together to create a new DataFrame (pd.concat)
- Adding columns
- Parsing cells as strings to make new columns (.str)
- Using the .apply() method
- Using groupby to perform aggregate analysis
- Plotting bar charts and lines graphs to visualize our results
- Labeling our graphs

# Getting Started

To run the code in this repository, you will need to have Python 3.x and the following Python libraries installed:

Pandas
Numpy
Matplotlib

To get started, you can clone this repository to your local machine and then navigate to the notebooks/ folder. From there, you can open the notebooks in Jupyter and run the code cells to reproduce the analysis.
