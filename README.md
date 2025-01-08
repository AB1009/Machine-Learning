Overview

This project leverages machine learning to predict obesity risk in adults based on various lifestyle, dietary, and demographic factors. The aim is to build a predictive model that identifies individuals at risk of obesity, providing actionable insights for prevention and health improvement.
The project involves data preprocessing, exploratory data analysis, feature engineering, model development, hyperparameter tuning, and a GUI for user interaction.
Features

Data Preprocessing: Handling missing values, scaling, and encoding categorical features.
Exploratory Data Analysis: Visualizing correlations, distributions, and trends using matplotlib and seaborn.
Machine Learning Model: Using LightGBM (LGBMClassifier) for high-performance classification.
Hyperparameter Tuning: Implementing Randomized Search Cross-Validation to optimize model performance.
User-Friendly GUI: An interactive interface built with tkinter to predict obesity risk based on user inputs.
Key Technologies

Libraries

Data Analysis and Visualization: pandas, matplotlib, seaborn
Machine Learning: scikit-learn, lightgbm
Graphical User Interface: tkinter
Concepts
Data Preprocessing with StandardScaler and OneHotEncoder
Label encoding for categorical target variables
Training and validation using train_test_split
Model pipelines for streamlined preprocessing and prediction
Hyperparameter tuning with RandomizedSearchCV

Project Workflow

Data Import and Cleaning: Loading datasets from OpenML and handling inconsistencies.
Feature Engineering: Encoding categorical variables and scaling numerical features.
Exploratory Data Analysis: Gaining insights into feature relationships and distribution patterns.
Model Development:
Define and train a LightGBM model.
Optimize hyperparameters using Randomized Search.
Evaluation: Validate model performance on unseen data.
GUI Implementation:
Build an interactive interface for predictions using tkinter.
Allow users to input data and view obesity risk predictions in real-time.
