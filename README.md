# Week 1 - ML Fundamentals & Data Preprocessing

## Overview

This project is part of my Week 1 Machine Learning assignment. It focuses on basic data analysis and preprocessing using the Titanic dataset.

## Objectives

- Load and explore a dataset
- Understand dataset structure
- Calculate basic statistics
- Identify and handle missing values
- Perform categorical data encoding
- Visualize data
- Split data into training and testing sets
- Save the cleaned dataset as a CSV file

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Dataset

The Titanic dataset is used for this assignment.

The dataset contains information about passengers such as:

- Passenger Class
- Age
- Sex
- Fare
- Number of siblings/spouses
- Number of parents/children
- Survival status

## Data Preprocessing

The following preprocessing techniques were performed:

### Missing Value Handling

- Missing values in `Age` were replaced using the median.
- Missing values in `Fare` were replaced using the median.
- Missing values in `Embarked` were replaced using the mode.

### Encoding

- `LabelEncoder` was used to encode the `Sex` column.
- One-hot encoding was used for the `Embarked` column.

## Data Visualization

The project includes visualizations for:

- Age distribution
- Survival count
- Survival by sex
- Survival by passenger class

## Train-Test Split

The dataset was divided into:

- 80% Training Data
- 20% Testing Data

A `random_state` of 42 was used for reproducibility.

## Output

The cleaned dataset is saved as:

`titanic_cleaned.csv`

## Files

```text
week-1-ml-data-preprocessing/
│
├── Week_1_ML_Assignment.ipynb
├── titanic_cleaned.csv
└── README.md
