# Artificial Intelligence Based Methods in Credit Card Fraud Detection

This project aims to develop an AI-based system for fraud detection. The system utilizes machine learning techniques to identify fraudulent activities in financial transactions.

## Table of Contents

- [Project Description](#project-description)
- [Datasets](#dataset)
- [Algorithms](#algorithms)


## Project Description

The AI-Based Fraud Detection project leverages advanced machine learning algorithms to detect fraudulent transactions. By analyzing a given dataset, the system learns patterns and characteristics associated with fraudulent activities, allowing it to classify new transactions as either fraudulent or legitimate.

The project includes several key components:

- Data preprocessing: The dataset undergoes cleaning, normalization, and feature engineering to prepare it for model training.
- Model training: Machine learning and deep learning models, such as XGBOOST or ANN, are trained using the preprocessed data.
- Evaluation: The trained models are evaluated using various metrics, such as precision, recall, AUC, and F1 score.
- Fraud detection: The system applies the trained model to new, unseen data to identify potential fraudulent transactions.

## Dataset

### Dataset Information

The datasets used within the project were researched from Kaggle, Google Dataset Search, UCI Machine Learning Repository, OpenML, DataHub, Papers with Code, EU Open Data Portal, Awesome Public Dataset resources and selected among the most preferred ones in the literature. Each dataset offers unique characteristics and can be utilized for different purposes. Below is a summary of the datasets:


| Dataset Name                              | Dataset Link                                                               | Number of Samples | Number of Features |
|-------------------------------------------|---------------------------------------------------------------------------|-------------------|--------------------|
| Credit Card Fraud Detection               | [Link](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)            | 284,807           | 31                 |
| Credit Card Transactions Fraud Detection  | [Link](https://www.kaggle.com/datasets/kartik2112/fraud-detection)         | 1,048,576         | 23                 |
| Fraud E-commerce                          | [Link](https://www.kaggle.com/datasets/vbinh002/fraud-ecommerce)           | 150,000           | 11                 |
| Synthetic data from a financial payment system | [Link](https://www.kaggle.com/datasets/ealaxi/banksim1)                   | 594,643           | 10                 |

## Algorithms
Within the scope of the project, the most used machine learning and deep learning algorithms in the literature for this project were examined comparatively.

| Machine Learning                    | Deep Learning                  |
|-------------------------|----------------------------|
| XGBClassifier           | ANN  |
| CatBoostClassifier      | CNN                   |
| AdaBoostClassifier      | RNN         |
| GradientBoostingClassifier | LSTM       |
| LGBMClassifier          | Autoencoder                   |


