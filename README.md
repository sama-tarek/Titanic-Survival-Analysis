# Titanic Survival Analysis

## Overview

This project explores the famous Titanic dataset to uncover the factors that influenced passenger survival. Using Python and data visualization techniques, the analysis examines relationships between passenger characteristics and survival outcomes.

## Objectives

* Perform exploratory data analysis (EDA).
* Handle missing values and clean the dataset.
* Engineer new features to gain deeper insights.
* Visualize patterns and relationships affecting survival.
* Draw meaningful conclusions from the data.

## Dataset

The dataset contains information about Titanic passengers, including:

* Passenger Class (`Pclass`)
* Sex
* Age
* Fare
* Embarked Port
* Number of Siblings/Spouses (`SibSp`)
* Number of Parents/Children (`Parch`)
* Survival Status (`Survived`)

## Data Cleaning

The following preprocessing steps were performed:

* Removed the `Cabin` column due to a large number of missing values.
* Filled missing values in `Age` using the median.
* Filled missing values in `Embarked` using the mode.
* Created additional features to improve analysis.

## Feature Engineering

New features created:

* **Family Size** = `SibSp + Parch + 1`
* **IsAlone** = Indicates whether a passenger traveled alone.
* **Age Categories** for grouping passengers into different age groups.

## Exploratory Data Analysis

The project investigates:

* Survival by gender
* Survival by passenger class
* Survival by age group
* Distribution of passenger fares
* Family size effects on survival
* Correlations between numerical features

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

## Key Findings

* Females had a significantly higher survival rate than males.
* First-class passengers were more likely to survive.
* Younger passengers generally had better survival chances.
* Family size influenced survival probability.
* Socioeconomic status played an important role in survival.

## Repository Structure

```
Titanic-Survival-Analysis/
│
├── Titanic.ipynb
├── data/
│   ├── train.csv
│   └── test.csv
├── README.md
└── images/
│   └── visualizations
```

## Future Improvements

* Build machine learning models to predict survival.
* Compare Logistic Regression, Random Forest, and XGBoost.
* Evaluate models using accuracy, precision, recall, and F1-score.

## Author

**Sama Tarek**

Aspiring Data Scientist passionate about data analysis, visualization, and machine learning.
