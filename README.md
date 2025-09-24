# Clustering and Outlier Detection in Simulated Data

## Author: Christian Amaro 

## Project Description

This project demonstrates a reproducible workflow in R to identify outliers in a simulated dataset. The analysis focuses on agricultural production data (example: Nopal verdura) and applies a univariate approach to detect anomalies.

## The process includes:

- Data loading and preprocessing: importing an Excel file, filtering a subset of interest, and replacing missing values with zeros.

- Clustering with k-means: using a single centroid as the reference point to calculate distances.

- Outlier detection: applying the ±3 standard deviations rule to flag anomalous records.

- Visualization and reporting: generating a scatter plot with highlighted outliers and a frequency table summarizing the results.

This workflow illustrates how to approach data cleaning, exploratory analysis, and anomaly detection in numeric variables.

# Technologies

Language: R

## Packages:

- dplyr and tidyverse for data manipulation

- readxl for importing Excel files

- ggplot2 for data visualization

- cluster, KMEANS.KNN, caTools as supporting packages


# Usage

Clone this repository.

Place the Excel file (e.g., captacion simulada act.xlsx) in the root folder.

Open and run the .Rmd file in RStudio.

An HTML report will be generated with the analysis results.
