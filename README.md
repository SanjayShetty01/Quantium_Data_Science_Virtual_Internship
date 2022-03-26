# Quantium Data Scienc Virtual Internship

### Background:
You are part of Quantium’s retail analytics team and have been approached by your client, the Category Manager for Chips, who wants to better understand the types of customers who purchase Chips and their purchasing behaviour within the region.

The insights from your analysis will feed into the supermarket’s strategic plan for the chip category in the next half year.


### Task 1: Data preparation and customer analytics

Conduct analysis on your client's transaction dataset and identify customer purchasing behaviours to generate insights.


To get started, download the resource csv data files below and begin performing high level data checks such as:

- Creating and interpreting high level summaries of the data
- Finding outliers and removing these (if applicable)
- Checking data formats and correcting (if applicable)


You will also want to derive extra features such as pack size and brand name from the data and define metrics of interest to enable you to draw insights on who spends on chips and what drives spends for each customer segment. Remember our end goal is to form a strategy based on the findings to provide a clear recommendation to Julia the Category Manager so make sure your insights can have a commercial application.

`Solution:` [Notebook](https://github.com/SanjayShetty01/Quantium_Data_Science_Virtual_Internship/blob/main/QVI_Data_Science_in_R(Task_1).ipynb)


### Task 2: Experimentation and uplift testing

Extend your analysis from Task 1 to help you identify benchmark stores that allow you to test the impact of the trial store layouts on customer sales.

Julia has asked us to evaluate the performance of a store trial which was performed in stores 77, 86 and 88.


We have chosen to complete this task in R, however you will also find Python to be a useful tool in this piece of analytics. We have also provided an R solution template if you want some assistance in getting through this Task.


To get started use the QVI_data dataset below or your output from task 1 and consider the monthly sales experience of each store. 


This can be broken down by:

- total sales revenue 
- total number of customers
- average number of transactions per customer


Create a measure to compare different control stores to each of the trial stores to do this write a function to reduce having to re-do the analysis for each trial store. Consider using Pearson correlations or a metric such as a magnitude distance e.g. 1- (Observed distance – minimum distance)/(Maximum distance – minimum distance) as a measure.


Once you have selected your control stores, compare each trial and control pair during the trial period. You want to test if total sales are significantly different in the trial period and if so, check if the driver of change is more purchasing customers or more purchases per customers etc.

`Solution 2:` [Notebook](https://github.com/SanjayShetty01/Quantium_Data_Science_Virtual_Internship/blob/main/QVI_Data_Science_in_R(Task_1).ipynb)
