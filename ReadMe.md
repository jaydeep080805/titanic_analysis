# Titanic Analysis

## Overview
This project explores the Titanic dataset using Python, Pandas, Seaborn, and Matplotlib. The aim is to identify key patterns in passenger survival by examining factors such as sex, class, and age.

## Tools Used
- Python
- Pandas
- Seaborn
- Matplotlib
- Jupyter Notebook

## Dataset
The dataset was loaded directly from Seaborn using:

```python
sns.load_dataset("titanic")
```

It includes passenger information such as survival status, sex, age, and class.

## Analysis Performed
The notebook includes the following analysis:

### 1. Overall Survival Count
A bar chart was created to compare the number of passengers who survived and did not survive.

**Finding:** More passengers died than survived, with a rough ratio of around 5:3.

### 2. Survival by Sex
A count plot was used to compare survival counts for male and female passengers.

**Finding:** A much higher number of female passengers survived compared to male passengers.

### 3. Survival by Passenger Class
A count plot and average survival rate chart were used to compare outcomes across first, second, and third class.

**Finding:** First class passengers had the highest survival rate, second class passengers had a moderate survival rate, and third class passengers had the lowest survival rate.

### 4. Survival by Age Group
Passenger ages were grouped into ranges (0-10, 11-20, 21-30, etc.) using `pd.cut()`. A bar chart was then used to show the average survival percentage for each age group.

**Finding:** Children had the highest survival rates, while older passengers had lower survival rates overall.

### 5. Survival by Age Group and Sex
The data was grouped by both age group and sex to compare average survival percentages across both variables.

**Finding:** In most age groups, women had higher survival rates than men.

## Key Skills Demonstrated
- Loading and inspecting datasets
- Cleaning data by removing missing values
- Creating grouped categories with `pd.cut()`
- Using `groupby()` and `mean()` for aggregation
- Creating clear visualisations with Seaborn
- Drawing conclusions from real data

## How to Run
1. Create a virtual environment and activate it
2. install the requirements with `pip install -r requirements.txt`
2. Open the notebook in Jupyter Notebook or VS Code.


## Conclusion
This project shows that survival on the Titanic was strongly influenced by passenger class and sex, while age also had an impact, particularly for children and older passengers. The analysis demonstrates how data visualisation can be used to identify meaningful trends in historical datasets.
