# Titanic ML Project

## Description

This repository contains a complete laboratory project analyzing the Titanic dataset from Kaggle using three different machine learning approaches of increasing complexity:

1. **Logistic Regression** – A baseline linear model for binary classification.
2. **Random Forest** – An ensemble of decision trees capturing non-linear relationships and providing feature importance.
3. **Feedforward Neural Network (PyTorch)** – A deep learning approach capable of modeling complex patterns in the tabular dataset.

The project includes:

* Data preprocessing and feature engineering.
* Implementation of three models.
* Evaluation of models using accuracy, precision, recall, and F1-score.
* Analysis of feature importance for Random Forest and Neural Network.
* Comparisons and conclusions about model performance.

## Files

* `train.csv`, (`test.csv`, `gender_submission.csv`) – Original Kaggle Titanic dataset files. (used only `train.csv`)
* `AI1.ipynb` – Notebook with Logistic Regression implementation, Random Forest implementation, PyTorch feedforward neural network implementation
* `report.docx` – Complete report summarizing all three variants, comparisons, and references. Detailed explanation of parameter choices and model architectures.

## How to Run

1. Open the corresponding Jupyter Notebook (`.ipynb`) in PyCharm or Jupyter Lab.
2. Ensure Python 3.8+ and required packages (`pandas`, `numpy`, `scikit-learn`, `torch`, `matplotlib`) are installed.
3. Run each cell sequentially to reproduce data preprocessing, model training, evaluation, and feature importance analysis.

## References

* Kaggle Titanic Dataset: [https://www.kaggle.com/c/titanic](https://www.kaggle.com/c/titanic)
* Random Forest Tutorial: [https://www.kaggle.com/code/startupsci/titanic-data-science-solutions](https://www.kaggle.com/code/startupsci/titanic-data-science-solutions)
* Neural Network PyTorch Example: [https://simulationbased.com/2021/02/03/a-deep-feedforward-network-in-pytorch-for-the-titanic-challenge](https://simulationbased.com/2021/02/03/a-deep-feedforward-network-in-pytorch-for-the-titanic-challenge)
* Logistic Regression Documentation: [https://scikit-learn.org/stable/modules/linear_model.html#logistic-regression](https://scikit-learn.org/stable/modules/linear_model.html#logistic-regression)
