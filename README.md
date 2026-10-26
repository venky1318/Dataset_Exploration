# Task 17 — Dataset Exploration Using Pandas

## Project Overview

This project explores a dataset using Python and Pandas. It examines dataset dimensions, column names, data types, summary statistics, missing values, duplicate rows, and species distribution.

The goal is to understand the structure and basic characteristics of the data before machine-learning modelling.

## Objectives

- Load a dataset into a Pandas DataFrame.
- Display the first five and last five records.
- Inspect dataset dimensions and columns.
- Examine data types and non-null values.
- Generate descriptive statistics.
- Identify numerical and categorical columns.
- Check missing values and duplicates.
- Record at least five observations about the dataset.

## Tools Used

- Python
- Pandas
- NumPy
- Scikit-learn dataset utilities
- Google Colab
- GitHub

## Dataset Description

The Iris dataset contains 150 observations, four numerical measurement features, and one species label.

The numerical features are sepal length, sepal width, petal length, and petal width. The species column identifies the Iris species.

Dataset reference: https://archive.ics.uci.edu/dataset/53/iris

## Pandas Functions Used

- `df.head()` — displays the first five rows.
- `df.tail()` — displays the last five rows.
- `df.shape` — returns the number of rows and columns.
- `df.columns` — displays column names.
- `df.info()` — displays data types and non-null counts.
- `df.describe()` — summarizes numerical columns.
- `df.isnull().sum()` — counts missing values.
- `df.duplicated().sum()` — counts duplicate rows.
- `df.groupby()` — summarizes measurements by species.

## Files

- `Task_17_Dataset_Exploration.ipynb` — completed Colab notebook.
- `iris_dataset.csv` — exported dataset.
- `README.md` — project documentation.
- `project_report.pdf` — formatted project report.
- `screenshots/` — screenshots of the executed notebook and results.

## Key Findings

The dataset contains 150 observations and five columns, including four numerical features and one categorical species label. It contains three Iris species, with 50 observations per species. The notebook also examines missing values, duplicate rows, descriptive statistics, and species-wise petal length.

## Conclusion

This project demonstrates how Pandas can be used to inspect and understand a dataset before further analysis or modelling.
