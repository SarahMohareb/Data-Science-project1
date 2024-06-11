# Grocery Dataset Analysis Shiny App

This Shiny application allows users to upload a dataset in CSV format, perform data cleaning, visualize data through various plots, and apply k-means clustering and association rule mining. The application is designed to help users explore and analyze grocery data interactively.

## Features

- **Upload Dataset**: Users can upload a CSV file containing grocery data.
- **Data Cleaning**: The application removes duplicate entries from the dataset.
- **Data Visualization**: Provides various plots for data analysis including:
  - Pie chart comparing cash and credit totals.
  - Scatter plot of age vs. total spending.
  - Bar plot of total spending by city.
  - Box plot of the distribution of total spending.
- **Clustering**: Perform k-means clustering on customer spending.
- **Association Rule Mining**: Generate association rules from the dataset.

## Prerequisites

Make sure you have R and the following R packages installed:
- `shiny`
- `dplyr`
- `arules`

Install the necessary packages using:
```r
install.packages("shiny")
install.packages("dplyr")
install.packages("arules")
