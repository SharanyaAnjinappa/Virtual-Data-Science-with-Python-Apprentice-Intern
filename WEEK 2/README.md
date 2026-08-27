
# Week 2 – Advanced Data Visualization and Storytelling with Python

## 📌 Overview

This project is part of the **Virtual Data Science with Python Apprentice Internship**.

Week 2 focuses on **Advanced Data Visualization and Storytelling with Python** using the Titanic dataset. The objective is to transform data into meaningful visual stories that can be easily understood by both technical and non-technical audiences.

The analysis builds on the data cleaning and exploratory analysis performed during Week 1.

## 🎯 Objectives

- Create advanced visualizations using Python.
- Explore relationships between multiple variables.
- Identify important patterns and trends in passenger survival.
- Use data visualization to communicate insights clearly.
- Develop a meaningful data story from the analysis.

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

## 📊 Dataset

The analysis uses the **Titanic passenger dataset**.

The dataset contains information such as:

- Passenger class
- Gender
- Age
- Fare
- Number of siblings/spouses
- Number of parents/children
- Survival status
- Embarkation information

The cleaned dataset prepared during Week 1 was used for the visualization analysis.

## 📈 Visualizations Created

Five visualizations were developed:

### 1. Survival Rate by Passenger Class and Gender

This visualization compares survival rates across passenger classes for male and female passengers.

### 2. Age Distribution by Survival Status

A histogram with density curves was used to compare the age distributions of survivors and non-survivors.

### 3. Relationship Between Age, Fare and Survival

A scatter plot was used to examine the relationship between age and fare while representing survival status and passenger class through visual properties.

### 4. Survival Rate by Family Size

A new `family_size` feature was created from `sibsp` and `parch`. The visualization examines how family size relates to survival.

### 5. Survival Rate by Gender and Passenger Class

A heatmap was created to clearly show the combined relationship between gender, passenger class, and survival.

## 🔍 Key Findings

- Female passengers had considerably higher survival rates than male passengers.
- Female passengers in first class had the highest observed survival rate of **96.77%**.
- Male passengers in third class had the lowest observed survival rate of **15.88%**.
- Survivors had an average fare of **50.19**, compared with **24.03** for non-survivors.
- Survivors had an average age of **28.33 years**, compared with **30.50 years** for non-survivors.
- Passengers with a family size of four had the highest observed survival rate at **71.43%**.
- Very large family-size groups had low observed survival rates, although these groups contained relatively few observations.
