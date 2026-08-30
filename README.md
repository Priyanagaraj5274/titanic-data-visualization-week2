# Titanic Data Visualization - Week 2

## Project Overview

This project was completed as part of Week 2 of the Virtual Data Science with Python Apprenticeship Internship.

The objective of this task was to explore advanced data visualization and storytelling techniques using Python and the Titanic passenger dataset. The analysis focuses on transforming data into meaningful visual narratives that can communicate important patterns, relationships, and insights clearly.

## Dataset

The Titanic dataset contains passenger information including:

- Passenger ID
- Survival status
- Passenger class
- Name
- Sex
- Age
- Number of siblings/spouses aboard
- Number of parents/children aboard
- Ticket
- Fare
- Port of embarkation
- Family size
- Age group

The final dataset used for analysis contains 891 passenger records.

## Technologies and Libraries

The project was developed using Python in Google Colab.

The following libraries were used:

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly

## Visualizations

The project contains several visualizations designed to communicate different aspects of the Titanic dataset:

1. Survival by Gender and Passenger Class
2. Age Distribution by Survival Status
3. Fare Distribution by Passenger Class
4. Family Size and Survival
5. Correlation Heatmap
6. Interactive Age-Fare-Survival Visualization
7. Survival by Age Group

All visualization outputs are available in the `visualizations_week2` folder.

## Key Insights

### 1. Overall Survival Rate

The overall survival rate was **38.38%**, indicating that fewer than half of the passengers in the dataset survived.

### 2. Gender and Survival

Female passengers had a survival rate of **74.20%**, while male passengers had a survival rate of **18.89%**.

This shows a strong relationship between gender and survival outcome.

### 3. Passenger Class

First-class passengers had the highest survival rate at **62.96%**.

Third-class passengers had the lowest survival rate at **24.24%**.

This indicates that passenger class was an important factor associated with survival.

### 4. Age Pattern

The average age of survivors was **28.29 years**, compared with **30.03 years** for passengers who did not survive.

### 5. Family Size

Passengers with a family size of **4** had the highest observed survival rate of **72.41%**.

### 6. Fare Pattern

Survivors paid an average fare of **48.40**, while non-survivors paid an average fare of **22.12**.

This suggests a relationship between fare level, passenger class, and survival.

## Project Files

```text
titanic-data-visualization-week2/
│
├── visualizations_week2/
│   ├── 01_survival_by_gender_and_class.png
│   ├── 02_age_distribution_survival.png
│   ├── 03_fare_distribution_by_class.png
│   ├── 04_family_size_survival.png
│   ├── 05_correlation_heatmap.png
│   ├── 06_interactive_age_fare_survival.html
│   └── 07_survival_by_age_group.png
│
├── Week2_Titanic_Advanced_Visualization.ipynb
├── week2_key_insights.txt
├── week2_summary.csv
└── README.md

Conclusion

The analysis demonstrates how advanced visualizations can be used to transform a dataset into an understandable data story. The visual analysis highlights important survival patterns related to gender, passenger class, age, family size, and fare.

The project also demonstrates the use of both static and interactive visualizations to communicate analytical findings effectively to both technical and non-technical audiences.

Author

Priya N
