# Human Activity Detection Using Machine Learning

## Overview

This project focuses on Human Activity Detection using machine learning techniques applied to sensor data. The goal is to classify various human activities, such as walking, running, sitting, and standing, based on accelerometer and gyroscope readings. This proactive system has applications in health monitoring, fitness tracking, and smart devices.

## Dataset

The dataset used in this project contains sensor data from accelerometers and gyroscopes, recorded during different human activities. Ensure the dataset is available and correctly formatted before running the code.

## File Descriptions

- `train.csv`: Training dataset containing labeled sensor data.
- `test.csv`: Testing dataset for evaluating the trained models.

## Project Structure

- **Data Preprocessing:**
  - Load and explore the dataset.
  - Check for duplicates and missing values.
  - Visualize data distribution and patterns.

- **Feature Engineering:**
  - Extract relevant features from sensor data.
  - Normalize or standardize data if necessary.

- **Exploratory Data Analysis:**
  - Visualize activity distribution.
  - Explore correlations between features.

- **Model Training:**
  - Implement various machine learning models, including:
    - Logistic Regression
    - Decision Trees
    - Random Forest
    - Linear SVM
    - K-Nearest Neighbors (KNN)

- **Model Evaluation:**
  - Evaluate models using accuracy, precision, recall, and F1-score.
  - Visualize confusion matrices for performance assessment.

- **Hyperparameter Tuning:**
  - Use techniques like Randomized Search or Grid Search to find optimal hyperparameters.

- **Results and Analysis:**
  - Compare and analyze the performance of different models.
  - Discuss strengths and limitations.

## Requirements

- Python 
- NumPy
- pandas
- scikit-learn
- Matplotlib
- Seaborn
