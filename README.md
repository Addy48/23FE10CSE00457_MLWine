🍷 23FE10CSE00457_MLWine

This repository contains the implementation of Machine Learning Laboratory experiments conducted as part of the Machine Learning Lab (CSE3231) curriculum at Manipal University Jaipur.

All experiments are implemented in Python using Google Colab, following the official lab lecture plan.
The Wine Quality Dataset from the UCI Machine Learning Repository is used as the base dataset for all experiments.

📊 Dataset Description

The Wine Quality dataset consists of physicochemical properties of Portuguese Vinho Verde wine samples.
The objective is to analyze and model the relationship between chemical attributes and perceived wine quality.

🔹 Datasets Used

winequality-white.csv

winequality-red.csv

🔹 Dataset Details

Total Features: 11 (real-valued)

Target Variable: quality (integer score between 0 and 10)

Task Type: Regression and Classification

Source: UCI Machine Learning Repository

🧪 Experiments Covered
🔬 Lab 1: Introduction to Python for Data Analysis

This experiment focuses on understanding the dataset and applying basic Python data analysis techniques.

Key Tasks:

Loading datasets using Pandas

Dataset inspection (shape, info, describe)

Basic NumPy operations

Understanding data structure and feature types

🔬 Lab 2: Data Preprocessing and Visualization

This experiment prepares the dataset for machine learning by cleaning, scaling, and visualizing the data.

Key Tasks:

Missing value analysis

Feature–target separation

Feature scaling using StandardScaler

Data visualization techniques:

Histograms

Boxplots

Correlation heatmap

🔬 Lab 3: Descriptive Statistical Analysis

This experiment applies statistical methods to summarize and interpret the dataset.

Key Tasks:

Computation of descriptive statistics:

Mean

Median

Variance

Standard Deviation

Analysis of:

Skewness

Kurtosis

Correlation analysis between features and target variable

Identification of key features influencing wine quality

🔬 Lab 4: Feature Selection and Linear Regression Analysis

📌 Objective

To perform feature and variable set preparation, apply feature scaling, build a Linear Regression model, and analyze the model parameters (intercept and coefficients) using the Wine Quality dataset.
🔹 Methodology

Dataset Loading
The dataset is loaded using Pandas and inspected to ensure correct structure.

Data Type Verification
The dataset is verified to be a Pandas DataFrame. Column data types are examined to identify non-numeric features.

Removal of Non-Numeric Columns
Any string or object-type columns (if present) are removed, as machine learning models require numerical input.

Feature and Target Variable Definition

Feature set (X): All physicochemical attributes

Target variable (y): Wine quality score

Feature Scaling
Standardization is applied using StandardScaler to scale features to zero mean and unit variance.
This ensures all features contribute equally to the regression model.

Train–Test Split
The dataset is split into training and testing sets to evaluate model generalization.

Linear Regression Model Training
A Linear Regression model is trained using the scaled training data.

Model Parameter Extraction

Intercept: Represents the predicted quality when all feature values are zero.

Coefficients: Represent the influence of each feature on wine quality.

Coefficient DataFrame Creation
The intercept and feature coefficients are stored in a Pandas DataFrame and sorted to analyze feature importance.

LAB 5 
Descriptive statistical analysis
 Data cleaning
 Feature scaling
 Feature selection
 Logistic Regression model
 Model evaluation
 Coefficients & intercept in DataFrame

📈 Observations

Alcohol content generally shows the strongest positive influence on wine quality.

Volatile acidity often exhibits a negative impact on quality.

Feature scaling is essential for meaningful coefficient comparison.
