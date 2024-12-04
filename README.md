# Statistical-Measures-

# Overview

This repository contains code and analysis for the House Price Dataset, which includes property prices in the city of Bangalore. The purpose of this analysis is to explore the data, detect outliers, and analyze the correlation between variables.

# Analysis and Steps Performed

# Q1. Perform Basic EDA

      The following steps were performed for EDA:
      1. Loading the dataset.
      2. Checking the shape and structure of the data (columns, data types, missing values).
      3. Displaying basic summary statistics for numerical columns.

# Q2. Detect Outliers Using Various Methods

      We detected outliers in the price_per_sqft column using the following methods:
      1. Mean and Standard Deviation Method: Identifying values that fall outside the range defined by mean ± standard deviation.
      2. Percentile Method: Detecting outliers using fixed percentiles (e.g., 1st and 99th percentiles).
      3. IQR (Inter Quartile Range): Using IQR to define upper and lower bounds for normal data points.
      4. Z-Score Method: Identifying data points where the Z-score exceeds a given threshold (usually 3).

# Q3. Create Box Plot to Compare Outlier Removal Methods

      We created box plots to visually compare the effect of the outlier removal methods, which allowed us to determine which method works best for the price_per_sqft column.

# Q4. Check Normality of price_per_sqft

      We checked the distribution of price_per_sqft by plotting a histogram. The following transformations were considered if the data was skewed:
      1. Log Transformation to handle skewness.
      2. Checking skewness and kurtosis before and after the transformation.

# Q5. Check the Correlation Between All Numerical Columns

      We computed the correlation matrix for numerical features and visualized it using a heatmap. This helped identify the strength of the relationships between various numerical variables.

# Q6. Draw Scatter Plots for Correlation

      Scatter plots were created for pairs of numerical variables to visually check the relationships between them.

# Output Visualizations

  *. Box Plots: Used to detect and compare the effects of outlier removal methods.
  *. Histograms: Used to check the distribution of price_per_sqft and apply transformations for normality.
  *. Heatmap: Displays the correlation matrix of numerical features.
  *. Scatter Plots: Show relationships between numerical variables.

# Conclusion

This analysis provides a thorough examination of the price_per_sqft column and other numerical features in the dataset. The outlier detection methods and correlation analysis provide insights into data quality and relationships between the features.

