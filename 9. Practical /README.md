# Practical 9: K-Nearest Neighbors (KNN) Classification using Python

## Aim

To implement the K-Nearest Neighbors (KNN) classification algorithm using Python to classify Iris flowers into different species and evaluate the model's performance.

## Libraries Used

- **Pandas:** For data loading and manipulation.
- **NumPy:** For numerical operations.
- **Matplotlib:** For data visualization.
- **Scikit-learn:** For machine learning, data preprocessing, model training and evaluation.

## Dataset

The Iris dataset is used for classification. It contains 150 flower observations belonging to three different species.

The dataset includes:
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width
- Species (Target Variable)

### Species Categories
- Setosa
- Versicolor
- Virginica

## Description

The following operations were performed:

1. Imported the required Python libraries.
2. Loaded the Iris dataset using Pandas.
3. Displayed the first five rows using `head()`.
4. Generated descriptive statistics using `describe()`.
5. Counted the number of flowers in each species using `groupby()`.
6. Separated independent variables and the target variable.
7. Divided the dataset into training and testing sets using an 80:20 ratio.
8. Applied feature scaling using `StandardScaler()`.
9. Implemented the K-Nearest Neighbors classifier with K = 5.
10. Trained the model using `fit()` and predicted flower species using `predict()`.
11. Evaluated model performance using a confusion matrix and accuracy score.
12. Generated a classification report containing precision, recall and F1-score.
13. Calculated error rates for K values from 1 to 10.
14. Created a graph to visualize error rates for different K values.
15. Identified the K value with the minimum error rate.
16. Compared actual and predicted flower species.
17. Visualized correct and incorrect predictions using a bar graph.

## Important Results

| Measurement | Result |
|---|---:|
| Total observations | 150 |
| Training samples | 120 |
| Testing samples | 30 |
| K value initially used | 5 |
| Initial model accuracy | 100% |
| Best K value found | 1 |
| Minimum error rate | 0% |
| Best model accuracy | 100% |

### Confusion Matrix

| Actual / Predicted | Setosa | Versicolor | Virginica |
|---|---:|---:|---:|
| Setosa | 10 | 0 | 0 |
| Versicolor | 0 | 9 | 0 |
| Virginica | 0 | 0 | 11 |

### Observations

- The KNN model successfully classified all 30 test samples.
- Feature scaling was applied to bring all numerical features to a similar scale.
- All tested K values from 1 to 10 produced a zero error rate on the test dataset.
- K = 1 was selected as the best K value because it was the first value with the minimum error.
- The confusion matrix shows that all predictions were correct.

## Tools Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

## Conclusion

Successfully implemented the K-Nearest Neighbors classification algorithm using the Iris dataset. Learned how to perform data preprocessing, feature scaling, model training, prediction and evaluation. The model achieved 100% accuracy on the test dataset, demonstrating successful classification of Iris flower species.
