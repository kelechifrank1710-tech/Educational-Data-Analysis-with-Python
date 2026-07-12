# Educational-Data-Analysis-with-Python

##Overview

This project demonstrates an end-to-end educational data analysis and machine learning workflow using Python. It covers the complete data science pipeline—from loading and cleaning data to exploratory data analysis (EDA), feature engineering, predictive modeling, and model evaluation.

The project uses a student depression dataset to identify patterns and build a machine learning model capable of predicting student depression status based on various educational and personal factors.

##Objectives

Load and inspect educational data
Clean missing values and inconsistent records
Perform Exploratory Data Analysis (EDA)
Engineer useful features for machine learning
Train a Decision Tree Classification model
Evaluate model performance using multiple metrics
Visualize important insights

##Repository Structure

Educational-Data-Analysis-with-Python/
│
├── datasets/
│   ├── Education_Student_Depression.csv
│   └── Education_Student_Depression_Cleaned.csv
│
├── notebooks/
│   ├── 01_Data_Loading.ipynb
│   ├── 02_Data_Cleaning.ipynb
│   ├── 03_Exploratory_Data_Analysis_(EDA).ipynb
│   ├── 04_Feature_Engineering.ipynb
│   ├── 05_Machine_Learning_Model.ipynb
│   └── 06_Model_Evaluation.ipynb
│
└── README.md

##Project Workflow

📌 Notebook 1 — Data Loading
Loaded the dataset using Pandas
Examined dataset structure
Displayed dataset information
Identified data types

📌 Notebook 2 — Data Cleaning
Performed data preprocessing by:
Removing duplicates
Handling missing values
Correcting data types
Saving the cleaned dataset

📌 Notebook 3 — Exploratory Data Analysis (EDA)
Explored the cleaned dataset using:
Summary statistics
Histograms
Boxplots
Count plots
Correlation heatmaps
Distribution analysis

This stage helped identify important patterns and relationships within the dataset.

📌 Notebook 4 — Feature Engineering
Prepared the dataset for machine learning by:
Selecting useful variables
Encoding categorical features
Splitting features and target variable
Preparing training and testing datasets

📌 Notebook 5 — Machine Learning Model
Built a Decision Tree Classifier using Scikit-learn.
Steps included:
Importing the classifier
Training the model
Making predictions
Preparing for evaluation

📌 Notebook 6 — Model Evaluation
Evaluated model performance using:
Accuracy Score
Classification Report
Confusion Matrix
Model Performance
Metric	Score
Accuracy	75.68%
Precision	76%
Recall	76%
F1 Score	76%

The confusion matrix showed that the model correctly classified the majority of student cases while maintaining balanced performance across both classes.

##Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Jupyter Notebook

##Machine Learning Pipeline
Raw Dataset
      │
      ▼
Data Cleaning
      │
      ▼
Exploratory Data Analysis
      │
      ▼
Feature Engineering
      │
      ▼
Train/Test Split
      │
      ▼
Decision Tree Classifier
      │
      ▼
Model Evaluation

##Key Learning Outcomes

This project demonstrates practical experience with:
Data preprocessing
Data visualization
Feature engineering
Supervised machine learning
Classification models
Model evaluation
Python for data science

##Future Improvements

Compare multiple machine learning algorithms
Hyperparameter tuning
Feature selection optimization
Cross-validation
Model deployment using Streamlit or Flask

##Author

Kelechi Frank

AI & Machine Learning Enthusiast
Science Educator | Educational Data Analyst | Aspiring Educational Data Scientist

GitHub:
https://github.com/kelechifrank1710-tech

License:
This project is for educational and portfolio purposes.
