EEG Signal Classification using Machine Learning and Statistical Analysis

Project Overview

This project focuses on the classification of EEG (Electroencephalogram) signals using machine learning techniques. The objective is to analyze complex brain signal patterns and identify distinguishable cognitive states through structured data analysis.

The project integrates statistical analysis, feature engineering, dimensionality reduction, and comparative evaluation of multiple machine learning models to build a complete analytical pipeline.

⸻

Objectives
	•	Analyze EEG data and understand its statistical properties
	•	Perform exploratory and statistical analysis on extracted features
	•	Apply multiple machine learning models for classification
	•	Compare model performance across different algorithms
	•	Handle class imbalance using SMOTE
	•	Reduce dimensionality using PCA
	•	Explore optimization techniques for performance enhancement

⸻

Dataset

The dataset consists of multi-channel EEG recordings collected under experimental conditions. The raw signals are processed and transformed into structured feature vectors suitable for machine learning models.

Key characteristics:
	•	High-dimensional data
	•	Multi-channel signal representation
	•	Presence of noise and variability
	•	Class imbalance in target labels

⸻

Technologies Used
	•	Python
	•	NumPy, Pandas
	•	Matplotlib, Seaborn
	•	Scikit-learn
	•	Imbalanced-learn

  DATASET AVAILABLE HERE :https://www.kaggle.com/datasets/ayushtibrewal/raw-eeg-stress-dataset-sam40

⸻

Project Workflow
	1.	Data Loading and Preprocessing
	•	Extraction of EEG signals from source files
	•	Conversion into feature matrix
	•	Cleaning and structuring of data
	2.	Statistical Analysis
	•	Distribution analysis of features
	•	Correlation heatmap
	•	Feature relationship exploration
	3.	Handling Class Imbalance
	•	Application of SMOTE (Synthetic Minority Oversampling Technique)
	4.	Feature Engineering and Dimensionality Reduction
	•	Principal Component Analysis (PCA) for reducing feature space
	5.	Model Development and Comparison
	•	Logistic Regression
	•	Support Vector Machine (SVM)
	•	Random Forest
	6.	Model Evaluation
	•	Accuracy comparison
	•	Confusion matrix analysis
	•	Performance visualization

⸻

Key Features of the Project
	•	Multi-model comparative analysis
	•	Handling of high-dimensional EEG data
	•	Integration of statistical insights with machine learning
	•	Visualization-driven interpretation of results
	•	Exploration of optimization techniques

⸻

Results
	•	Random Forest achieved the most stable and consistent performance
	•	SVM showed improved performance over linear models
	•	Logistic Regression served as a baseline model
	•	PCA reduced dimensionality and improved computational efficiency
	•	SMOTE helped balance class distribution and improve learning

⸻

Optimization Exploration

Optimization techniques such as Simulated Annealing were explored to enhance model performance through parameter tuning and feature selection.

However:
	•	Results were inconsistent across experiments
	•	High computational cost limited extensive experimentation
	•	Optimization methods were not included in the final model pipeline

⸻

Challenges Faced
	•	EEG data is highly noisy and complex
	•	High dimensionality increases risk of overfitting
	•	Class imbalance affects model performance
	•	Computational constraints limit optimization approaches

⸻

Future Scope
	•	Implementation of deep learning models for improved accuracy
	•	Advanced feature extraction techniques
	•	Use of larger and more diverse EEG datasets
	•	Real-time EEG signal classification systems
	•	Deployment as a web-based or API-driven application
