# Support-Vector-Machine-SVM-on-Wine-Quality
This repository contains an analysis of wine quality using Support Vector Machines (SVM). The objective is to classify wine quality based on various physicochemical properties.


#Dataset Overview
The dataset includes features such as:
Fixed Acidity: The amount of fixed acids in the wine.
Volatile Acidity: The amount of acetic acid in the wine.
Citric Acid: The citric acid content in the wine.
Residual Sugar: Sugar remaining after fermentation.
Chlorides: The amount of salt in the wine.
Free Sulfur Dioxide: Free SO2 in the wine.
Total Sulfur Dioxide: Total SO2 in the wine.
Density: The density of the wine.
pH: The pH level of the wine.
Sulphates: The sulfate content in the wine.
Alcohol: The alcohol content in the wine.
Quality: Quality score (0-10) assigned by wine experts.

#Key Steps in the Analysis
Data Loading and Overview: Load the dataset using Pandas and display basic statistics, shape, and missing values.
Exploratory Data Analysis (EDA):
Visualize the distribution of wine quality using count plots.
Generate a correlation matrix to assess relationships among features.
Data Preparation:
Split the dataset into features (X) and target variable (y) and create training and testing sets.
Modeling:
Train a linear SVM model and evaluate its performance using accuracy, classification report, and confusion matrix.
Use One-vs-Rest strategy for multiclass classification and generate ROC curves.
Model Evaluation:
Train and evaluate an RBF SVM model, comparing its performance to the linear model.
Generate ROC curves to visualize the performance for each class.

#Requirements
To run this analysis, you will need the following Python libraries:
numpy
pandas
matplotlib
seaborn
scikit-learn
