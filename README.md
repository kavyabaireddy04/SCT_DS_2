# Titanic Survival Analysis

## Overview

This repository contains a Python script that conducts exploratory data analysis (EDA) on the Titanic passenger dataset. The goal is to uncover insights about passenger demographics, survival rates, and the relationships between different features and survival outcomes.

## Objectives

* Load and inspect the Titanic dataset
* Handle missing data through imputation and column removal
* Explore distributions of key variables like age, gender, and passenger class
* Visualize survival counts and survival breakdowns by gender and class
* Analyze relationships between age, gender, class, and survival status
* Compute survival rates and generate summary pivot tables to aid deeper insights

## Features

* Initial data exploration with shape, info, missing values, and statistical summaries
* Missing value imputation for `Age` and `Embarked` columns
* Removal of columns with excessive missing data (`Cabin`)
* Data type conversions for categorical analysis
* Multiple visualizations including count plots, histograms, boxplots, and heatmaps
* Calculation and display of survival rates by gender and class
* Pivot table summarizing survival rates by sex and passenger class

## Technologies

* Python 3.x
* Pandas (data manipulation and cleaning)
* NumPy (numerical operations)
* Matplotlib (plotting)
* Seaborn (enhanced statistical visualization)
