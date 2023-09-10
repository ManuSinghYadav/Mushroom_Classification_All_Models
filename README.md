# Classification of Mushrooms

In this project, I have used a dataset freely available on Kaggle to build a machine learning model for classifying mushrooms as either edible or poisonous.

## Problem Statement

The objective of this project is to develop a machine learning model that can accurately classify mushrooms based on their characteristics as either safe to eat or potentially poisonous.

## Solution / Approach Taken

In the process of solving this problem, I employed various key machine learning techniques during the dataset preprocessing phase, including:

1. **Categorical Column Encoding:** I utilized the OneHotEncoder technique to convert categorical columns into a format suitable for machine learning.

2. **Handling Imbalanced Data:** To address the issue of class imbalance, I applied the Synthetic Minority Over-sampling Technique (SMOTE) to create a more balanced dataset.

3. **Feature Selection:** I employed Recursive Feature Selection (RFE) to select the most relevant features for the classification task, improving the model's efficiency.

Once the dataset was successfully preprocessed, I evaluated its performance using several prominent machine learning models for classification, including:

1. Logistic Regression
2. K-Nearest Neighbors
3. Support Vector Machines
4. Naive Bayes
5. Decision Trees
6. Random Forest
7. XGBoost

As can be seen above, I explored two Ensemble Learning algorithms: Random Forest (Bagging) and XGBoost (Boosting), to enhance the classification results.

## Results

I am pleased to report that our models achieved nearly 100% accuracy during the evaluation phase. However, please note that the real-world application of these models may require further considerations and testing beyond this initial assessment.
