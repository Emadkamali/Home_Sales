## Project Overview

This project showcases the application of SparkSQL and PySpark for in-depth analysis of home sales data. The goal is to leverage Spark's capabilities to manipulate and analyze the data, extracting meaningful insights.

## Contents
Data Loading
Data Analysis
Performance Comparison

### Data Loading
The home sales dataset is loaded from an AWS S3 bucket into a Spark DataFrame using PySpark, setting the stage for subsequent analysis.

### Data Analysis
We employ SparkSQL to conduct the following analyses:

Average Price of Four-Bedroom Houses per Year

Calculate the average selling price for four-bedroom houses, categorized by year.
Average Home Price by Year Built

Determine the average price of homes based on the year they were built, applying specific filters to the data.
Data Partitioning

Partition the dataset based on the "date_built" field to enhance query performance.
Caching for Speed

Cache a temporary table to expedite query execution.
Average Price Analysis by View Rating

Analyze the average home price according to the "view" rating, considering specific conditions.
Performance Comparison
This section includes a comparative analysis of query runtimes with and without caching, and evaluates the impact of data partitioning on performance.

## Requirements
Apache Spark
Python (with PySpark)
Jupyter Notebook or Google Colab (optional)
How to Run
Install Apache Spark on your machine.
Clone this repository.
Open the project notebook in Jupyter Notebook or Google Colab.
Execute each cell sequentially to run the analysis.
