# Virtual Data Science with Python Apprentice Intern

## Titanic Survival Analysis and Prediction

This repository contains my 5-week **Virtual Data Science with Python
Apprentice Internship** project. The project uses the Titanic passenger
dataset to demonstrate an end-to-end data science workflow, including
data cleaning, exploratory analysis, visualization, statistical testing,
machine learning, and final recommendations.

## Project Structure

``` text
Virtual Data Science with Python Apprentice Intern/
│
├── Week 1/
│   ├── Data Acquisition
│   ├── Data Cleaning
│   ├── Exploratory Data Analysis
│   └── Visualizations
│
├── Week 2/
│   ├── Advanced Data Visualization
│   ├── Data Storytelling
│   └── Key Insights
│
├── Week 3/
│   ├── Hypothesis Testing
│   ├── Chi-Square Test
│   └── Statistical Results
│
├── Week 4/
│   ├── Data Preprocessing
│   ├── Logistic Regression
│   ├── Confusion Matrix
│   └── ROC Curve
│
└── Week 5/
    ├── Comprehensive Analysis
    ├── Final Visualizations
    ├── Strategic Recommendations
    └── Final Report
```

## Technologies Used

-   Python
-   Jupyter Notebook
-   Pandas
-   NumPy
-   Matplotlib
-   Seaborn
-   SciPy
-   Scikit-learn

## Dataset

The project analyzes the Titanic passenger dataset. Important variables
include:

-   Survival status
-   Passenger class
-   Gender
-   Age
-   Fare
-   Number of siblings/spouses
-   Number of parents/children
-   Embarkation details

## Week 1 -- Data Acquisition, Cleaning and EDA

The dataset was examined using Pandas and Python. Data-quality checks
included missing-value analysis, duplicate detection, data-type
inspection, descriptive statistics, and exploratory visualizations.

Key observations included differences in survival rates by gender and
passenger class, along with distributions of age and fare.

## Week 2 -- Advanced Visualization and Storytelling

More detailed visualizations were created to communicate relationships
between multiple variables.

Major analyses included:

-   Survival rate by gender and passenger class
-   Age distribution by survival status
-   Relationship between age, fare, and survival
-   Survival rate by family size
-   Gender and class survival heatmap

These visualizations helped identify important patterns and communicate
the findings clearly.

## Week 3 -- Statistical Analysis

A hypothesis test was performed to determine whether gender and survival
were statistically associated.

### Chi-Square Test Results

-   **Chi-Square Statistic:** 260.717
-   **p-value:** 1.197 × 10⁻⁵⁸
-   **Degrees of Freedom:** 1
-   **Cramer's V:** 0.5409

Since the p-value was far below 0.05, the null hypothesis was rejected.
The analysis provides strong evidence of an association between
passenger gender and survival.

## Week 4 -- Machine Learning

A Logistic Regression model was developed to predict passenger survival.

### Model Performance

  Metric         Score
  ----------- --------
  Accuracy      81.41%
  Precision     76.92%
  Recall        78.12%
  F1 Score      77.52%
  ROC-AUC       88.66%

The confusion matrix and ROC curve were used to evaluate the
classification model.

## Week 5 -- Comprehensive Data Science Project

The final week integrated the work completed during the previous weeks
into a complete data science project.

The final analysis included:

-   Overall survival analysis
-   Survival by gender and passenger class
-   Statistical validation
-   Logistic Regression
-   Model evaluation
-   Strategic recommendations
-   Project limitations and future improvements

### Final Model Performance

  Metric         Score
  ----------- --------
  Accuracy      80.45%
  Precision     79.31%
  Recall        66.67%
  F1 Score      72.44%
  ROC-AUC       84.36%

## Key Findings

1.  The overall Titanic survival rate was approximately **38.38%**.
2.  Female passengers had substantially higher survival rates than male
    passengers.
3.  First-class passengers generally had higher survival rates than
    passengers in lower classes.
4.  The combination of gender and passenger class showed strong
    differences in survival.
5.  The Chi-Square test confirmed a statistically significant
    relationship between gender and survival.
6.  Logistic Regression achieved useful predictive performance, with a
    final ROC-AUC of **0.8436**.

## Project Outcome

This project demonstrates the complete data science lifecycle:

**Data Acquisition → Data Cleaning → EDA → Visualization → Statistical
Analysis → Machine Learning → Evaluation → Recommendations**

The project provided practical experience in using Python-based data
science tools to transform raw data into meaningful insights and
predictive results.

## Author

**Virtual Data Science with Python Apprentice Intern**

**Project:** Titanic Survival Analysis and Prediction

**Duration:** 5 Weeks
