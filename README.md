# Data Analysis of Student Scores and Related Features

This project involves the analysis of student scores and various related features using Python and its data analysis libraries. The goal is to understand the relationship between different features and student performance.

## Libraries Used

- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`

## Steps Performed

###  - Data Loading and Initial Inspection

Load the dataset using pandas.
Display the first 10 rows of the dataset.
Generate descriptive statistics and information about the dataset.
Check for missing values.

### - Data Cleaning

Drop rows with missing values.
Remove the Unnamed: 0 column.

### - Gender Distribution

Plot a count plot to show the distribution of students by gender.

### - Student Scores by Parent Education

Group the data by ParentEduc and calculate the mean scores for Math, Reading, and Writing.
Plot a heatmap to visualize the average scores by parents' education.

### - Parents' Marital Status

Plot a count plot to show the distribution of students by their parents' marital status.
Group the data by ParentMaritalStatus and calculate the mean scores for Math, Reading, and Writing.
Plot a heatmap to visualize the average scores by parents' marital status.

### - Practice of Sports

Plot a bar chart to show the count of students who practice sports, grouped by their parents' marital status.
Plot a bar chart to show the count of students who practice sports, grouped by gender.
Plot a bar chart to show the count of students who practice sports, grouped by gender and parents' marital status.

### - Ethnic Group Analysis

Plot a count plot to show the distribution of students by ethnic group.
Plot a bar chart to show the count of students by ethnic group, study hours, and gender.
Plot boxen plots to visualize the distribution of Reading, Math, and Writing scores by ethnic group and gender.
