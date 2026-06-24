# DDoS Detection Project

This repository contains a machine learning workflow for detecting DDoS traffic using an SDN-based dataset. The implementation is provided in [DDos_Notebook.ipynb](DDos_Notebook.ipynb) and includes data preprocessing, feature selection, class balancing, model training, evaluation, and visualization.

## Project Goal

The aim of this project is to compare several classification models for distinguishing DDoS traffic from benign traffic.

### Models included

- Random Forest
- Logistic Regression
- Decision Tree
- Support Vector Machine (SVM)
- Naive Bayes

## Dataset

The project uses a dataset named `dataset_sdn.csv`.

> Note: the notebook currently loads the dataset from the Colab path `/content/dataset_sdn.csv`. If you are running it locally, update the file path to match your local dataset location.

## Workflow

The notebook performs the following steps:

1. Importing the required libraries
2. Loading and inspecting the dataset
3. Cleaning the data by handling missing values, duplicates, and outliers
4. Selecting important features
5. Balancing the dataset using undersampling
6. Splitting the data into training and testing sets
7. Training multiple classification models
8. Evaluating performance using accuracy, precision, recall, F1 score, and confusion matrices
9. Visualizing model performance

## Requirements

Install the required dependencies with:

```bash
pip install -r requirements.txt
```

## How to Run

1. Open [DDos_Notebook.ipynb](DDos_Notebook.ipynb)
2. Ensure the dataset path is correct for your environment
3. Run the notebook cells in order

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

## Outputs

The notebook generates:

- a preprocessed CSV file
- confusion matrix visualizations
- performance comparison plots
- evaluation metrics for each model

## Possible Next Steps

Future improvements could include:

- testing more advanced models such as XGBoost or Gradient Boosting
- performing hyperparameter tuning
- comparing undersampling and oversampling strategies
- converting the workflow into a standalone Python script
- adding more detailed results and visual explanations
