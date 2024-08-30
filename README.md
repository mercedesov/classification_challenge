# Pre-Interview Assessment

## Introduction

This project is centered around building machine learning models to evaluate candidate profiles and predict whether they are suitable for an interview based on various features. The goal is to create a model that can help streamline the recruitment process by automatically assessing candidate profiles with high accuracy.


## Getting Started

To get started with the project, follow these steps:

1. Clone the repository:
`git clone https://github.com/mercedesov/classification_challenge.git`
`cd classification challenge`

2. Install the required dependencies

3. Download the dataset:
[Kaggle](https://www.kaggle.com/datasets/raneemrefaie/pre-interview-acceptance)

## Libraries and Functions Used

The project leverages the following key libraries and functions:

- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical computations.
- **Scikit-learn**: For model building, training, and evaluation.
- **Matplotlib/Seaborn**: For data visualization and plotting.

These libraries were chosen for their efficiency and ease of use in handling data and building machine learning models.

## Output Examples

Throughout the notebook, you will find output examples demonstrating each step of the process, including:

- **Data Visualization**: Graphs and plots showing data distribution and correlations.
- **Model Performance**: Accuracy, precision, recall, and other metrics evaluating the model's effectiveness.
- **Predictions**: Examples of predictions made by the model on test data, highlighting its ability to assess candidate suitability.

## Model Results

The final model results are as follows:

- **Logistic Regression Accuracy**: 0.92
- **Naive Bayes Accuracy**: 0.87
- **KNN Accuracy**: 0.96

### Logistic Regression

- **Classification Report**:
  - Precision: 0.94 (False), 0.65 (True)
  - Recall: 0.97 (False), 0.42 (True)
  - F1-Score: 0.95 (False), 0.51 (True)
  - Support: 268 (False), 31 (True)

- **Confusion Matrix**:
  - True Negatives: 261
  - False Positives: 7
  - False Negatives: 18
  - True Positives: 13

### Naive Bayes

- **Classification Report**:
  - Precision: 1.00 (False), 0.44 (True)
  - Recall: 0.86 (False), 0.97 (True)
  - F1-Score: 0.92 (False), 0.61 (True)
  - Support: 268 (False), 31 (True)

- **Confusion Matrix**:
  - True Negatives: 230
  - False Positives: 38
  - False Negatives: 1
  - True Positives: 30

### KNN

- **Classification Report**:
  - Precision: 0.97 (False), 0.82 (True)
  - Recall: 0.98 (False), 0.74 (True)
  - F1-Score: 0.98 (False), 0.78 (True)
  - Support: 268 (False), 31 (True)

- **Confusion Matrix**:
  - True Negatives: 263
  - False Positives: 5
  - False Negatives: 8
  - True Positives: 23

## Conclusion

This assessment compared three different classification models for predicting candidate suitability for interviews. The **K-Nearest Neighbors (KNN)** model performed the best, achieving the highest accuracy of 0.96. Given its balance between precision and recall, it is the recommended model for this task.
