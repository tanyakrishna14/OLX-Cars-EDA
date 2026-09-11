# Exploratory Data Analysis on OLX Cars Dataset

## Project Overview

This project focuses on performing Exploratory Data Analysis (EDA) on an OLX Cars Dataset. The main aim is to understand the dataset, clean the available data, identify patterns and relationships between different car attributes, detect possible outliers, and present the findings using suitable visualisations.

## Dataset

* **Dataset Name:** OLX Cars Dataset
* **Number of Records:** 9,179
* **Original Columns:** 18
* **Dataset Source:** Kaggle
* **Dataset Link:** https://www.kaggle.com/datasets/abdullahkhanuet22/olx-cars-dataset

The dataset contains information such as car name, make, model, manufacturing year, kilometres driven, price, fuel type, transmission, registration city, condition, and seller location.

## Objectives

* Understand the structure and characteristics of the dataset.
* Check missing values and duplicate records.
* Perform data cleaning.
* Analyse numerical and categorical variables.
* Study relationships between car attributes.
* Identify possible outliers.
* Create meaningful visualisations.
* Extract useful insights from the dataset.

## Data Cleaning

The following steps were performed during data cleaning:

* Checked the shape and structure of the dataset.
* Checked data types of all columns.
* Identified missing values.
* Checked for duplicate records.
* Filled missing values in the `Car Profile` column using the mode.
* Removed the `Description` column as it was not required for the analysis.
* Checked categorical columns for unique values.
* Used box plots to identify possible outliers.

## Exploratory Data Analysis

The analysis included:

* Descriptive statistics
* Univariate analysis
* Bivariate analysis
* Multivariate analysis
* Outlier detection
* Correlation analysis

### Visualisations Used

* Price Distribution – Histogram
* Fuel Type vs Transmission – Count Plot
* Correlation Heatmap
* Box Plots
* Scatter Plots
* Count Plots

## Key Findings

* Petrol cars are the most frequently available fuel category.
* Manual cars are more commonly listed than other transmission categories.
* Car prices show considerable variation across the dataset.
* Newer cars generally tend to have higher prices than older cars.
* Kilometres driven may influence the resale price of cars.
* Car prices vary across different manufacturers.
* Some unusual values were observed in numerical variables such as price and kilometres driven.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Google Colab
* Jupyter Notebook

## Project Files

```text
OLX-Cars-EDA/
│
├── OLX_Cars_EDA.ipynb
├── TANYAKRISHNA_MINOR_1.pdf
└── README.md
```

## Author

**Tanya Krishna**

B.E. Computer Science and Engineering (AI & ML)
