# Practical 7: Correlation, Regression, T-Test and ANOVA using Python

## Aim

To analyse the relationship between teaching evaluation scores, beauty ratings, gender and age using correlation, linear regression, T-test and ANOVA techniques in Python.

## Libraries Used

- **Pandas:** For loading, handling and analysing the dataset.
- **NumPy:** For numerical operations.
- **Matplotlib:** For data visualization.
- **Seaborn:** For statistical data visualization.
- **Statsmodels:** For performing linear regression, T-test and ANOVA.
- **SciPy:** For calculating Pearson correlation and its p-value.

## Dataset

The Teaching Ratings dataset is obtained from the file `TeachingRatings(1).csv`. It contains information about professors, including age, gender, beauty ratings, teaching evaluation scores, tenure and student details.

## Description

The following operations were performed:

1. Imported the required Python libraries.
2. Loaded the Teaching Ratings dataset using Pandas.
3. Displayed the first five rows using `head()`.
4. Displayed all column names using `columns`.
5. Checked missing values in the dataset using `isnull().sum()`.
6. Calculated the correlation between teaching evaluation scores and beauty ratings.
7. Applied linear regression using gender and evaluation scores.
8. Performed a T-test to check whether gender has a statistically significant association with teaching evaluation scores.
9. Divided professors into three age groups: Young, Middle and Older.
10. Applied ANOVA to compare beauty ratings across different age groups.
11. Calculated Pearson correlation and its p-value between evaluation scores and beauty ratings.
12. Applied simple linear regression to study the relationship between beauty ratings and teaching evaluation scores.
13. Analysed the regression coefficient, R-squared value, t-statistic and p-value.

## Important Results

| Measurement | Result |
|---|---:|
| Total observations | 463 |
| Missing values | 0 |
| Correlation between Evaluation and Beauty | 0.1890 |
| Gender Regression Coefficient | 0.1680 |
| Gender T-statistic | 3.250 |
| Gender P-value | 0.001 |
| AN
