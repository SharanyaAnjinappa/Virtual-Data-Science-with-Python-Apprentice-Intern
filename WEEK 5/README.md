
# Week 5 – Comprehensive Data Science Project Reporting and Strategic Recommendations

## Project Title
**Titanic Survival Analysis and Prediction**

## Objective

The objective of Week 5 is to combine the knowledge and techniques developed throughout the previous weeks into a complete end-to-end data science project. The Titanic dataset was analyzed to identify important survival patterns, validate relationships statistically, develop a machine learning model, and provide meaningful conclusions and recommendations.

## Dataset

The project uses the Titanic passenger dataset containing information about passengers such as:

- Passenger class
- Gender
- Age
- Fare
- Family information
- Survival status
- Embarkation details

## Work Completed

The Week 5 project integrates the following stages:

1. Data acquisition and preparation
2. Data cleaning and preprocessing
3. Exploratory data analysis
4. Advanced data visualization
5. Statistical hypothesis testing
6. Machine learning model development
7. Model evaluation
8. Strategic recommendations
9. Limitations and future improvements

## Key Findings

### Overall Survival

The dataset contains **891 passengers**.

- Did not survive: **549**
- Survived: **342**
- Overall survival rate: **38.38%**

### Survival by Gender and Passenger Class

Female passengers had significantly higher survival rates than male passengers.

| Gender | Passenger Class | Survival Rate |
|--------|-----------------|---------------|
| Female | 1st | 96.81% |
| Female | 2nd | 92.11% |
| Female | 3rd | 50.00% |
| Male | 1st | 36.89% |
| Male | 2nd | 15.74% |
| Male | 3rd | 13.54% |

The results show that both **gender and passenger class** were important factors associated with survival.

## Statistical Analysis

A Chi-Square test was performed to determine whether there was a statistically significant association between gender and survival.

### Results

- **Chi-Square Statistic:** 260.717
- **p-value:** 1.197 × 10⁻⁵⁸
- **Degrees of Freedom:** 1
- **Cramer's V:** 0.5409

Since the p-value is much smaller than the significance level of 0.05, the null hypothesis was rejected.

This provides strong statistical evidence that **gender and survival were significantly associated** in the Titanic dataset.

## Machine Learning Model

A **Logistic Regression** model was developed to predict passenger survival.

The model was evaluated using accuracy, precision, recall, F1-score, ROC-AUC, and a confusion matrix.

### Final Model Performance

| Metric | Score |
|--------|-------|
| Accuracy | 80.45% |
| Precision | 79.31% |
| Recall | 66.67% |
| F1 Score | 72.44% |
| ROC-AUC | 84.36% |

The ROC-AUC score of **0.8436** indicates that the model provides good discrimination between passengers who survived and those who did not.

## Visualizations

The project includes visualizations such as:

- Overall survival distribution
- Survival rate by passenger class and gender
- Final model confusion matrix
- Final model ROC curve

These visualizations help communicate the major findings and evaluate the machine learning model.

## Strategic Recommendations

Based on the analysis:

1. Passenger characteristics such as gender and passenger class should be considered when studying historical survival patterns.
2. Further analysis should investigate the combined effects of age, family size, fare, and passenger class.
3. Additional machine learning algorithms could be compared with Logistic Regression.
4. Model performance could potentially be improved through feature engineering and hyperparameter tuning.
5. Cross-validation should be used to obtain more reliable estimates of model performance.

## Limitations

- The Titanic dataset represents a historical event and may not generalize to modern situations.
- Some variables contain missing values, particularly age and deck information.
- Logistic Regression assumes a relatively simple relationship between predictors and the outcome.
- Model performance may vary depending on preprocessing, feature selection, and train-test splitting.

## Future Improvements

Future work could include:

- Testing Decision Tree and Random Forest models
- Comparing multiple machine learning algorithms
- Performing hyperparameter tuning
- Applying cross-validation
- Creating additional engineered features
- Developing an interactive dashboard
- Performing more detailed statistical analysis

## Conclusion

The Week 5 project successfully combines the complete data science workflow, from data preparation and exploratory analysis to statistical testing and predictive modeling. The analysis identified strong differences in survival based on gender and passenger class. Statistical testing confirmed a significant relationship between gender and survival, while the Logistic Regression model achieved an accuracy of **80.45%** and an ROC-AUC of **84.36%**.

Overall, the project demonstrates the practical application of Python-based data science techniques to transform a raw dataset into meaningful insights, statistical evidence, and predictive results.

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Scikit-learn

## Project Structure

```text
Week 5/
│
├── README.md
├── Week5_Titanic_Comprehensive_Report.docx
├── Jupyter Notebook
├── Visualizations
└── Analysis Files
