# 2.Car_data_analysis

## Overview

This project analyzes a car dataset using Python and pandas in a Jupyter Notebook. The notebook focuses on loading the dataset, understanding the structure, identifying missing values, and cleaning the data.

## Goal of the Project

* Understand the car dataset
* Identify missing values in the data
* Clean the dataset using pandas
* Prepare the dataset for further analysis

## Tools and Technologies

* Python
* Pandas
* Jupyter Notebook

## Dataset Loading

The dataset is loaded into a pandas DataFrame for analysis.

Example code used in the notebook

import pandas as pd
df = pd.read_csv("car_data.csv")

## Dataset Exploration

Basic pandas functions are used to explore the dataset.

df.head() – Displays the first rows of the dataset
df.info() – Shows column data types and non null values
df.shape – Displays number of rows and columns

## Checking Missing Values

Missing values are identified using the following function

df.isnull().sum()

This helps detect which columns contain null values.

## Handling Missing Values

Missing values are handled using pandas functions.

df.dropna() – Removes rows with null values
df.fillna() – Replaces missing values with suitable values

## Result

After cleaning the dataset, the data becomes ready for further analysis and visualization.

## Conclusion

Data cleaning is an important step in data analysis. Using pandas, missing values can be easily identified and handled, which prepares the dataset for accurate analysis.
