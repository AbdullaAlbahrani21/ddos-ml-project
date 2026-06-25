# DDoS Detection Project

A practical machine learning project for detecting DDoS traffic using an SDN-based dataset. The workflow is implemented in [DDos_Notebook.ipynb](DDos_Notebook.ipynb) and covers data preprocessing, feature selection, class balancing, model training, evaluation, and visualization.

## Overview

This project compares several classification models to distinguish benign traffic from DDoS traffic. It is designed as a reproducible, educational example of applying supervised learning to network intrusion detection.

### Models included

- Random Forest
- Logistic Regression
- Decision Tree
- Support Vector Machine (SVM)
- Naive Bayes

## Dataset

The project uses a dataset named `dataset_sdn.csv`.

> Note: the notebook currently loads the dataset from the Colab path `/content/dataset_sdn.csv`. If you are running it locally, update the file path to match your local dataset location.

## Project Workflow

The notebook performs the following stages:

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

Install the dependencies with:

```bash
pip install -r requirements.txt
```

## Getting Started

1. Clone the repository
2. Install the dependencies
3. Open [DDos_Notebook.ipynb](DDos_Notebook.ipynb)
4. Ensure the dataset path is correct for your environment
5. Run the notebook cells in order

## Outputs

The notebook generates:

- a preprocessed CSV file
- confusion matrix visualizations
- performance comparison plots
- evaluation metrics for each model

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

## Contributing

Contributions are welcome. Please see [CONTRIBUTING.md](CONTRIBUTING.md) for details.

## Security

If you discover a security issue, please review [SECURITY.md](SECURITY.md) for reporting guidance.

## Citation

If you use this project in your work, please cite it using [CITATION.cff](CITATION.cff).
