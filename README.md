# Analyzing Data with Pandas and Visualizing Results with Matplotlib

## Description

This project demonstrates how to analyze a dataset using the Pandas library and visualize the results with Matplotlib. The classic Iris dataset from the UCI Machine Learning Repository is used for this analysis.

## Objective

- Load and explore a dataset.
- Perform basic data analysis (descriptive statistics and grouping).
- Visualize the dataset using various chart types with Matplotlib and Seaborn.
- Draw conclusions from the analysis.

## Dataset Used

- **Name:** Iris Dataset  
- **Source:** UCI Machine Learning Repository  
- **Loading Method:** Loaded using `sklearn.datasets.load_iris()`  
- **Description:** The dataset contains 150 samples with 4 features each (sepal length, sepal width, petal length, petal width) and a target label indicating the species (Setosa, Versicolor, or Virginica).

## Tasks Completed

### Task 1: Load and Explore the Dataset

- Loaded the dataset using `sklearn.datasets.load_iris()`.
- Converted it into a Pandas DataFrame for analysis.
- Displayed the first few rows using `.head()`.
- Explored the structure of the dataset, including data types and summary info.
- Verified that there are no missing or incorrect values.

### Task 2: Basic Data Analysis

- Computed descriptive statistics using `.describe()`.
- Grouped data by species to analyze average feature values.
- Compared patterns and differences across species.

### Task 3: Data Visualization

Created the following plots using Matplotlib and Seaborn:

- **Line Chart:** Showed petal length trends by species.
- **Bar Chart:** Compared average petal length across species.
- **Histogram:** Displayed the distribution of sepal width.
- **Scatter Plot:** Visualized the relationship between sepal length and petal length with species labels.

All plots were customized with appropriate titles, axis labels, and legends.

## Final Observations

- Setosa is well-separated with small petal measurements.
- Virginica has the largest features on average.
- Versicolor lies between the other two in terms of size.
- The scatter plot reveals clear clustering, especially for Setosa.
- No missing or incorrect values were found.

## Files Included

- `iris_analysis.ipynb` – Jupyter Notebook containing all code, visualizations, and explanations.

## Tools and Libraries

- Python 3.x  
- Pandas  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- Jupyter Notebook

## How to Run

1. Clone this repository.
2. Open `iris_analysis.ipynb` in Jupyter Notebook.
3. Run all cells to reproduce the analysis and visualizations.
