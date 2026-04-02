# 🍷 23FE10CSE00457_MLWine

This repository contains the implementation of Machine Learning Laboratory experiments conducted as part of the **Machine Learning Lab (CSE3231)** curriculum at Manipal University Jaipur.

All experiments are implemented in **Python using Google Colab**, following the official lab structure. The **Wine Quality Dataset (UCI Machine Learning Repository)** is used consistently across experiments.

---

## 📊 Dataset Description

The Wine Quality dataset consists of physicochemical properties of Portuguese Vinho Verde wine samples. The objective is to analyze and model the relationship between chemical attributes and wine quality.

### 🔹 Datasets Used
- `winequality-red.csv`
- `winequality-white.csv`

### 🔹 Dataset Details
- Total Features: 11 (real-valued)
- Target Variable: `quality` (integer score between 0 and 10)
- Task Type: Regression and Classification
- Source: UCI Machine Learning Repository

---

## 🧪 Experiments Covered

### 🔬 Lab 1: Introduction to Python for Data Analysis
This experiment focuses on understanding the dataset and applying basic Python data analysis techniques.

**Key Tasks:**
- Loading datasets using Pandas  
- Dataset inspection (`shape`, `info`, `describe`)  
- Basic NumPy operations  
- Understanding data structure and feature types  

---

### 🔬 Lab 2: Data Preprocessing and Visualization
This experiment prepares the dataset for machine learning by cleaning, scaling, and visualizing the data.

**Key Tasks:**
- Missing value analysis  
- Feature–target separation  
- Feature scaling using StandardScaler  
- Data visualization:
  - Histograms  
  - Boxplots  
  - Correlation heatmap  

---

### 🔬 Lab 3: Descriptive Statistical Analysis
This experiment applies statistical methods to summarize and interpret the dataset.

**Key Tasks:**
- Mean, Median, Variance, Standard Deviation  
- Skewness and Kurtosis analysis  
- Correlation analysis  
- Identification of important features  

---

### 🔬 Lab 4: Feature Selection and Linear Regression Analysis

**Objective:**  
To perform feature preparation, scaling, and build a Linear Regression model to analyze relationships between features and wine quality.

**Key Steps:**
- Dataset loading and inspection  
- Removal of non-numeric columns (if any)  
- Feature (X) and target (y) definition  
- Feature scaling using StandardScaler  
- Train–test split  
- Linear Regression model training  
- Extraction of intercept and coefficients  
- Feature importance analysis  

---

### 🔬 Lab 5: Logistic Regression

**Key Tasks:**
- Data cleaning and preprocessing  
- Feature scaling  
- Feature selection  
- Logistic Regression model training  
- Model evaluation  
- Analysis of coefficients and intercept  

**Observations:**
- Alcohol shows strong positive correlation with quality  
- Volatile acidity shows negative correlation  
- Scaling is essential for meaningful comparison  

---

### 🔬 Lab 6: Support Vector Machine (SVM) Classification

This experiment implements **SVM classification** to predict wine quality based on physicochemical properties.

**Key Steps:**
- Data preprocessing and scaling  
- Train–test split  
- Training SVM model using `SVC`  
- Prediction on test data  
- Evaluation using:
  - Confusion Matrix  
  - Classification Report  
- Hyperparameter tuning using **GridSearchCV**  

**Outcome:**
- Improved classification performance after tuning  
- Demonstrates impact of kernel-based learning  

---

### 🔬 Lab 7: Decision Tree Classification

This experiment implements **Decision Tree classification** to model wine quality prediction.

**Key Steps:**
- Data preprocessing and feature scaling  
- Train–test split  
- Training Decision Tree model  
- Visualization of decision tree structure  
- Model evaluation using:
  - Confusion Matrix  
  - Classification Report  

**Outcome:**
- Provides interpretable model structure  
- Highlights feature importance in decision making  

*(Aligned with supervised learning tasks as per lab handout: classification model building and evaluation)*  [oai_citation:0‡MachineLearningLabHandouts (3) (2).pdf](sediment://file_00000000d5c071fabe644a01036eaad1)

---

### 🔬 Lab 8: K-Means Clustering (Unsupervised Learning)

This experiment implements **K-Means clustering** to identify patterns in unlabeled wine data.

**Key Steps:**
- Combining red and white wine datasets  
- Encoding categorical feature (`type`)  
- Removing target variable (`quality`)  
- Feature scaling  
- Determining optimal clusters using Elbow Method  
- Applying K-Means clustering  
- PCA-based visualization  
- Cluster evaluation using:
  - Silhouette Score  
  - Cluster vs Quality comparison  

**Outcome:**
- Identifies hidden structure in data  
- Demonstrates difference between clustering and classification  

*(Aligned with unsupervised learning objective: pattern identification in unlabeled data)*  [oai_citation:1‡MachineLearningLabHandouts (3) (2).pdf](sediment://file_00000000d5c071fabe644a01036eaad1)

---
### 🔬 Lab 9: Artificial Neural Network (ANN)

This experiment implements an Artificial Neural Network for wine quality prediction.

**Key Steps:**
- Data preprocessing and scaling  
- Conversion of target variable to binary classification (`quality ≥ 6`)  
- Train–test split  
- Building ANN model using dense layers  
- Model training with validation  
- Evaluation using accuracy and loss curves  
- Confusion matrix analysis  

**Outcome:**
- ANN performs well on tabular data  
- Binary classification improves prediction performance  
- Demonstrates learning patterns through deep neural networks  

---

### 🔬 Lab 10: Convolutional Neural Network (CNN)

This experiment implements a 1D Convolutional Neural Network adapted for tabular data.

**Key Steps:**
- Reshaping input data for CNN  
- Building Conv1D model  
- Model training and validation  
- Evaluation using accuracy, loss curves, and confusion matrix  

**Outcome:**
- CNN can be applied to tabular data with reshaping  
- Performance is generally comparable or slightly lower than ANN  
- Highlights importance of matching model architecture with data type  

---


## ⚙️ Technologies Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  

---

## 🎯 Key Takeaways

- End-to-end ML workflow from preprocessing to modeling  
- Implementation of both **supervised and unsupervised learning techniques**  
- Importance of scaling, evaluation, and model tuning  
- Understanding differences between regression, classification, and clustering  
