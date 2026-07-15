# Task-1: Data Distribution Visualization

This project visualizes the distribution of a categorical variable (Gender) 
and a continuous variable (Age) from the Titanic dataset using a bar chart 
and a histogram.

## Task
Create a bar chart or histogram to visualize the distribution of a categorical 
or continuous variable, such as the distribution of ages or genders in a population.

## Dataset
Titanic dataset:
- `train.csv`
- `test.csv`
- `gender_submission.csv`

Source: [Prodigy InfoTech Data Science Datasets](https://github.com/Prodigy-InfoTech/data-science-datasets/tree/main/Task%201)

## What this notebook does
1. Loads the dataset using pandas
2. Explores the data using `df.info()`, `df.describe()`, and `df.isnull().sum()`
3. Renames the `Sex` column to `Gender`
4. Plots a **bar chart** showing the distribution of Gender (categorical variable)
5. Plots a **histogram** showing the distribution of Age (continuous variable)

## Tools used
- Python
- Pandas
- Matplotlib
- Seaborn

## Output
- Bar chart comparing count of male vs female passengers
- Histogram showing age distribution with a KDE curve
