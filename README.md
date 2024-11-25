## Overview

A machine learning project for classifying bank marketing campaign success. This project includes data preprocessing, model training, and evaluation using techniques like SMOTE, ADASYN, and more to handle class imbalance.

## Features

- **Data Preprocessing**: Cleaning and transforming raw data into a suitable format for model training.
- **Handling Imbalanced Data**: Utilizing techniques such as SMOTE, ADASYN, and undersampling to balance the dataset.
- **Model Training**: Implementing various machine learning algorithms including MLPClassifier, Random Forest, Decision Tree, KNN, and SVM.
- **Evaluation**: Assessing model performance using metrics like accuracy, precision, recall, and F1 score.

## Dataset

The dataset is sourced from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Bank+Marketing). It includes details on customers' bank accounts and marketing interactions.

## Results

The dataset is highly imbalanced with approximately 88% 'no' responses and 12% 'yes' responses. This imbalance necessitates the use of techniques like SMOTE and ADASYN to balance the classes. After balancing and training various models, the best results achieved are:

- **Best Accuracy**: 0.90

- **Best F1 Score**: 0.50
