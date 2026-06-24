# DDoS Detection Project

This project explores machine learning techniques for detecting DDoS attacks using an SDN-based dataset. The workflow is implemented in the notebook [DDos_Notebook.ipynb](DDos_Notebook.ipynb) and includes data preprocessing, feature selection, class balancing, model training, evaluation, and visualization.

## Project Overview

The goal of this project is to compare several classification models for identifying DDoS traffic versus benign traffic. The notebook evaluates:

- Random Forest
- Logistic Regression
- Decision Tree
- Support Vector Machine (SVM)
- Naive Bayes

## Dataset

The project uses a dataset named `dataset_sdn.csv`.

Note: in the notebook, the dataset is loaded from the Colab path `/content/dataset_sdn.csv`. If you are running it locally, update the file path to match your local dataset location.

## Workflow

The notebook performs the following steps:

1. Importing required libraries
2. Loading and inspecting the dataset
3. Cleaning the data by handling null values, duplicates, and outliers
4. Selecting important features
5. Balancing the dataset using undersampling
6. Splitting data into train and test sets
7. Training multiple classification models
8. Evaluating models using accuracy, precision, recall, F1 score, and confusion matrices
9. Visualizing model performance

## Requirements

Install the required Python packages before running the notebook:

```bash
pip install pandas numpy scikit-learn imbalanced-learn seaborn matplotlib
```

## How to Run

1. Open [DDos_Notebook.ipynb](DDos_Notebook.ipynb)
2. Make sure the dataset path is correct
3. Run the notebook cells in order

## Outputs

The notebook generates:

- Preprocessed CSV output
- Confusion matrix visualizations
- Performance comparison plots
- Model evaluation metrics

## Next Steps

Possible improvements for this project include:

- Testing more advanced models such as XGBoost or Gradient Boosting
- Performing hyperparameter tuning
- Comparing oversampling vs. undersampling strategies
- Adding a clean script version of the workflow outside the notebook
- Preparing the repository for GitHub with proper documentation and version control
