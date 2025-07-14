# Red Wine Quality Analysis

## Project Overview
This project performs exploratory data analysis (EDA) and visualization on the Red Wine Quality dataset to understand the chemical properties influencing wine quality. It aims to identify correlations between features and the quality score, supporting potential predictive modeling efforts in the future.

## Tech

- Programming language - *Python 3.x*
- Data handling - *Pandas, Numpy*
- Data Visualization - *matplotlib, seaborn*

## Features

- Exploratory Data Analysis (EDA)
- Correlation Heatmap
- Boxplots and Histograms for feature distributions
- Insightful visualizations to understand the influence of acidity, alcohol, and more on wine quality

## Workflow
1) Import and Load Dataset-
Load the Red Wine Quality dataset into a Pandas DataFrame.

2) Basic EDA-
-Understand shape, info, and statistical summary of data
-Identify missing values

3) Univariate Analysis
-Plot histograms of all numeric features
-Inspect the distribution of wine quality ratings

4) Bivariate Analysis
-Analyze how each chemical property (e.g., alcohol, acidity) correlates with wine quality
-Use boxplots to identify impactful features

5) Correlation Analysis
-Compute Pearson correlation matrix
-Visualize heatmap for strongly/weakly correlated features

## Key Insights
- Alcohol and volatile acidity significantly affect wine quality
- Residual sugar and chlorides have low correlation with quality

## Folder Structure
Red-wine-analysis/
├─ Red-wine-analysis.ipynb
├─ README.md

## How to run this?
Step 1) Clone the repo
```sh
git clone https://github.com/ajitaabhardwaj/Wine-quality-analysis.git
```
Step 2) Install Requirements
```sh
pip install pandas matplotlib seaborn jupyter
```
Step 3) Launch Jupyter notebook
```sh
jupyter notebook Red-wine-analysis.ipynb
```

#Future Enhancements
#Build a classification model to predict wine quality
#Use advanced techniques like PCA for dimensionality reduction
#Optimize data preprocessing and feature engineering

