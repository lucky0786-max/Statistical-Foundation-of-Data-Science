# Practical 8: Decision Tree Classification Using Python

## Aim
To implement the Decision Tree Classification algorithm using Python and understand how Entropy, Information Gain, and Gini Index are used to split data and classify outcomes.

## Libraries Used
- **Pandas:** For loading and handling the dataset.
- **NumPy:** For numerical operations.
- **Matplotlib:** For visualizing the decision tree.
- **Scikit-learn:** For splitting the dataset, training the classifier, and evaluating model accuracy.

## Dataset
The **Pima Indians Diabetes Dataset** was used in this practical.

- Total records: 768
- Total columns: 9
- Independent variables: 8
- Dependent variable: `Outcome`

The target variable `Outcome` represents whether a person has diabetes:
- 0 – No Diabetes
- 1 – Diabetes

## Description
The following steps were performed:

1. Imported the required Python libraries.
2. Loaded the diabetes dataset using Pandas.
3. Separated the independent variables (`X`) and dependent variable (`y`).
4. Split the dataset into training and testing sets using an 80:20 ratio.
5. Created and trained a Decision Tree Classifier using the Entropy criterion.
6. Predicted the outcomes for the testing data.
7. Evaluated the model using accuracy score.
8. Visualized the decision tree using Matplotlib.
9. Compared Entropy and Gini Index to understand the decision-making process.
10. Identified the root feature selected by both criteria.

## Important Results

| Parameter | Result |
|---|---:|
| Total records | 768 |
| Total features | 8 |
| Training records | 614 |
| Testing records | 154 |
| Model criterion | Entropy |
| Model accuracy | 72.08% |
| Root feature using Entropy | Glucose |
| Root feature using Gini | Glucose |
| Entropy of root node | 0.9313 |
| Information Gain of root split | 0.3385 |
| Gini Index of root node | 0.4531 |

## Observations
- The Decision Tree model achieved an accuracy of approximately **72.08%** on the testing dataset.
- The dataset was divided into 614 training records and 154 testing records.
- Both Entropy and Gini Index selected **Glucose** as the root feature.
- The information gain of the root split was approximately 0.3385.
- The decision tree was visualized to understand how the model makes classification decisions.

## Tools Used
- Google Colab
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

## Conclusion
In this practical, we successfully implemented the Decision Tree Classification algorithm using the Pima Indians Diabetes dataset. We learned how to load data, split it into training and testing sets, train the model, make predictions, visualize the decision tree, and compare Entropy and Gini Index. This practical helped us understand how a Decision Tree is used for classification problems.
