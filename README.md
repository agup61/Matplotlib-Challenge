# Matplotlib-Challenge

This repository contains code to analyze the effectiveness of various drugs on treating squamous cell carcinoma (SCC) in 249 mice. The analysis calculates key metrics, such as mean, median, variance, standard deviation, and standard error of the mean (SEM) for each drug.

**Data Source**
The analysis is based on a dataset of mouse metadata and study results, which includes information on each mouse and the effect of different treatment drugs on their squamous cell carcinoma (SCC). The dataset is available in the Pymaceuticals/data repository.

**Getting Started**
To perform the analysis, clone the repository and run the Pymaceuticals_AnalysisCode.ipynb notebook in the Pymaceuticals folder. The notebook includes code to read the data, calculate metrics, and create summary DataFrames.

**Requurments**
The analysis requires the following libraries:

pandas
numpy
scipy.stats
matplotlib.pyplot

**Analysis Results**

The analysis includes:

- A summary statistics table showing mean, median, variance, standard deviation, and SEM for tumor volume of each drug regimen
- A bar plot displaying the number of data points for each treatment regimen
- A pie plot showing the gender distribution of mice in the study
- Calculation of final tumor volume, quartiles, IQR, and potential outliers for four treatment regimens
- A box and whisker plot highlighting any potential outliers
- A line plot showing the relationship between time point and tumor volume for a single mouse treated with Capomulin
- A scatter plot displaying the relationship between mouse weight and average tumor volume for the Capomulin treatment regimen
- Calculation of correlation coefficient and linear regression model for the Capomulin treatment, overlaid on the scatter plot.
