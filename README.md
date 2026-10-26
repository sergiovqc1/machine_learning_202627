# Everything & Then Some: Predicting Repeat Purchases with ML

## Project Overview

This project aims to predict whether a customer will make another purchase within the next 90 days (`repeat_purchase_90d`).

We use historical transaction data for exploratory data analysis, data preprocessing, feature engineering, and model training. Different classification algorithms are evaluated using temporal cross-validation and hyperparameter tuning.

The selected model is trained on the available labeled data to generate predictions for the test dataset.

## Environment Setup

**1. Install Conda**

Make sure [Anaconda or Miniconda](https://www.anaconda.com/download) is installed.

**2. Create the environment**

Extract the ZIP file and open a terminal in the project folder containing `environment.yml`.

Run:

```bash
conda env create -f environment.yml
```

**3. Activate the environment**

```bash
conda activate machine_learning_project
```

**4. Run the notebook**

```bash
jupyter notebook
```

Open the project notebook, select the `machine_learning_project` kernel, and execute the cells in order.

Alternatively, open the notebook in VS Code using the same environment.

## Output

The final predictions are saved in `submission.csv`, containing the purchase ID and the predicted `repeat_purchase_90d` value (0 or 1).