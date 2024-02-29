# Breast Cancer Detection Using Logistic Regression

This repository contains a Python script for building a predictive model to detect breast cancer using logistic regression. The dataset used for training and testing the model is the Breast Cancer Wisconsin (Diagnostic) dataset, which is available in the scikit-learn library.

## Overview
Breast cancer is one of the most common cancers among women worldwide. Early detection plays a crucial role in successful treatment outcomes. Machine learning techniques, such as logistic regression, can aid in the early detection of breast cancer by analyzing various features extracted from diagnostic tests.

## Machine Learning Approach
## Dataset
The Breast Cancer Wisconsin (Diagnostic) dataset consists of features computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. These features describe the characteristics of cell nuclei present in the image. The dataset contains 569 instances with 30 features each.

## Logistic Regression
Logistic regression is a supervised learning algorithm used for binary classification problems. It models the probability that a given instance belongs to a particular class. In this project, logistic regression is employed to predict whether a breast mass is malignant or benign based on the extracted features from diagnostic tests.

## Conclusion
This project demonstrates the application of machine learning, specifically logistic regression, in breast cancer detection. By analyzing features extracted from diagnostic tests, the model can provide valuable insights to aid medical professionals in early diagnosis and treatment decision-making.


# Data Visualization
1. Determine skewness by visualizing the distribution
2. Visualize the outliers for detection
3. Scatter plots to determine the correlation between variables
4. Box plots to check whether the mean and median are close to each other
5. Check the distribution of the target variable
6. Construct a heat map to visualize the correlation matrix

# Inference from EDA & Data Visualization:
1. No missing values
2. All are continuous numerical values except for the Target column
3. The mean is slightly more than the median for most of the features, hence, the data is right-skewed.
4. Slight imbalance in the dataset (there are more Benign(0) cases than Malignant(1) cases)
5. The mean of most features is clearly larger for Malignant cases compared to the benign cases (Groupby)
7. The Correlation Matrix reveals that most of the features are highly correlated. For further analysis, we should remove certain features for accurate analysis
