# Exploratory Data Analysis of Water Potability

This repository contains the Exploratory Data Analysis (EDA) of a water potability dataset. The goal of this EDA is to understand the factors that influence water potability and to prepare the data for further analysis or machine learning modeling.

## Dataset

The dataset used in this analysis contains various water quality parameters and a binary 'Potability' label indicating whether the water is safe for human consumption (1) or not (0).

The dataset includes the following features:

* **ph:** pH of water (acidity or alkalinity)
* **Hardness:** Measure of minerals in water
* **Solids:** Total dissolved solids
* **Chloramines:** Amount of chloramine
* **Sulfate:** Amount of sulfates
* **Conductivity:** Electrical conductivity of water
* **Organic_carbon:** Amount of organic carbon
* **Trihalomethanes:** Amount of trihalomethanes
* **Turbidity:** Measure of water cloudiness
* **Potability:** Target variable (1 = Potable, 0 = Non-Potable)

## EDA Steps

The following EDA steps were performed:

1.  **Data Loading and Inspection:**
    * Loaded the dataset using pandas.
    * Checked the data types and missing values.
    * Displayed basic statistics of the numerical features.

2.  **Univariate Analysis:**
    * Histograms and box plots were used to understand the distribution of each numerical feature.
    * Count plot and pie chart were used to analyze the distribution of the target variable 'Potability'.

3.  **Bivariate Analysis:**
    * Scatter plots were used to visualize the relationships between pairs of numerical features, colored by 'Potability'.
    * Correlation matrix heatmap was generated to show the relationships between all numerical features and their correlation with 'Potability'.

4.  **Observations:**
    * The 'Potability' variable exhibits a slight class imbalance.
    * Scatter plots showed no clear separation between potable and non-potable samples based on individual features.
    * Correlation analysis revealed weak correlations between individual features and 'Potability'.
    * Outliers were observed in several numerical features.
    * The distribution of pH was observed to be slightly skewed.

## Tools and Libraries

The following Python libraries were used for this EDA:

* **pandas:** For data manipulation and analysis.
* **seaborn:** For data visualization.
* **matplotlib:** For plotting.
