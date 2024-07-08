# Classification Tree Learning Algorithm

## Objective
The goal of this project is to implement a classification tree learning algorithm from scratch to make predictions for the "Introduction to Machine Leearning" course. The project emphasizes creating an original implementation without using existing code from libraries such as Scikit Learn or WEKA. This is intended to ensure a deep understanding of the underlying principles and to develop coding skills in building machine learning algorithms.

## Project Overview
1. Preprocessing Steps
   * Handling Missing Values: Imputed missing values with means using pandas.
   * Outlier Detection and Removal: Identified and removed outliers using pandas.
   * Data Transformation: Applied standard scaling using StandardScaler from sklearn.
   * Categorical Data Processing: Cleaned by removing special characters, stop words, and applying stemming.
2. Classification Tree Creation:
   * Built a decision tree classifier using gini and entropy criteria.
   * Implemented functions for tree construction, splitting, and prediction.
   * Visualized feature importance with bar plots.

## Conclusion
This project successfully demonstrates the implementation of a classification tree learning algorithm from scratch. Through comprehensive preprocessing steps and careful construction of the decision tree, the algorithm achieved training accuracies of 60% and 52.58% on two different datasets. This project not only highlights the importance of thorough data preprocessing but also provides a deep understanding of the mechanics behind classification trees, contributing to a solid foundation in machine learning principles.
