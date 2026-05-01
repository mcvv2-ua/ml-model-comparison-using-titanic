# Supervised Learning on the Titanic Dataset

This repository contains a supervised learning study using the classic Titanic dataset. The work compares several classification algorithms and evaluates their performance on a stratified train/test split.

## Contents

- `supervised_learning_titanic.ipynb`: main notebook with preprocessing, training, tuning and evaluation.
- `REPORT.pdf`: final report with the methodology, results and conclusions.
- `data/titanic.csv`: Titanic dataset used in the experiments.
- `images/`: generated figures and confusion matrices.
- `requirements.txt`: Python dependencies.

## Models Evaluated

- Support Vector Machines
- Decision Trees
- Random Forest
- Gradient Boosting
- AdaBoost

## How to Run

Create a virtual environment, install the dependencies and open the notebook from the repository root:

```bash
pip install -r requirements.txt
jupyter notebook supervised_learning_titanic.ipynb
```

The notebook expects the dataset at `data/titanic.csv` and writes generated plots to `images/`.

## Dataset

The project uses the public Titanic passenger dataset, commonly used for machine learning classification examples. The original columns include passenger names, ticket identifiers and cabin values because they are part of the public dataset. The notebook removes high-cardinality columns such as `Name`, `Ticket`, `Cabin` and `PassengerId` during preprocessing.

## Main Result

The best reported model in the final report is an SVM model, with accuracy close to 80% on the test split.

## Reproducibility

The train/test split and model configurations use fixed random seeds where applicable.
