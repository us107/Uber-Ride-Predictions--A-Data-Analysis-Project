# Uber Ride Prediction - Model Comparison

This project aims to predict various aspects of Uber rides using **Logistic Regression** and **Random Forest** models. The main objective is to compare the performance of these models using both **test accuracy** and **cross-validation accuracy**.

## Project Overview

In this project, two machine learning models (Logistic Regression and Random Forest) are applied to a dataset that contains information about Uber rides, including features such as:

- **Start Location**
- **End Location**
- **Start Time**
- **End Time**
- **Distance traveled**
- **Purpose of the ride**

The models are evaluated to predict various ride categories (e.g., **commute**, **meal/entertainment**, **customer visit**) and determine the probability of **high demand (surge pricing)**.

The key comparison metrics include:
- **Test Accuracy**: The accuracy of the models on unseen data (test set).
- **Cross-Validation Accuracy**: The accuracy achieved by the models on multiple folds of the dataset (cross-validation).

## Features

- **Logistic Regression**: A linear model used for binary classification.
- **Random Forest**: An ensemble learning method used for both classification and regression tasks.

## Dataset

The dataset used in this project contains the following columns:
- **START_DATE**: The date the ride started.
- **END_DATE**: The date the ride ended.
- **START_LOCATION**: The starting point of the ride.
- **END_LOCATION**: The destination point of the ride.
- **MILES**: The distance traveled during the ride.
- **PURPOSE**: The purpose of the ride (e.g., meeting, commute, etc.).
- **CATEGORY**: The category of the ride (e.g., personal, business, etc.).
- **START_TIME**: The starting hour and minute of the ride.
- **END_TIME**: The ending hour and minute of the ride.

## Project Workflow

1. **Data Preprocessing**:
   - Handle missing values.
   - Encode categorical features (e.g., day of the week, start and end locations).
   - Feature engineering for time-based features such as start and end hours, weekdays, and weekends.

2. **Model Training**:
   - Train **Logistic Regression** and **Random Forest** models using the training data.
   - Perform **cross-validation** to evaluate model performance.
   - Calculate **test accuracy** by evaluating the models on the test set.

3. **Model Comparison**:
   - Compare the accuracy of **Logistic Regression** and **Random Forest** based on:
     - Test Accuracy
     - Cross-Validation Accuracy

4. **Visualization**:
   - Create a **bar chart** comparing the test and cross-validation accuracy of both models for easy comparison.

## Requirements

- Python 3.x
- Libraries:
  - **NumPy**
  - **Pandas**
  - **Matplotlib**
  - **Scikit-learn**

Install the necessary libraries using `pip`:

```bash
pip install numpy pandas matplotlib scikit-learn


---

This Markdown format includes all relevant project details, instructions, and usage guidelines. You can copy and paste this directly into your `README.md` file for your project. Let me know if you need any further adjustments!
