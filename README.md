
# Titanic Survival Prediction Project

This project uses machine learning techniques to predict the survival of passengers on the Titanic based on the famous Kaggle Titanic dataset.

## Project Overview

The main goal of this project is to apply various machine learning models to predict whether a passenger survived the Titanic disaster. The dataset includes information about passenger demographics, ticket details, and survival status.

## Features

The dataset includes the following features:
- **Pclass**: Passenger class
- **Sex**: Gender of the passenger
- **Age**: Age of the passenger
- **SibSp**: Number of siblings/spouses aboard
- **Parch**: Number of parents/children aboard
- **Fare**: Ticket fare
- **Embarked**: Port of embarkation
- **Survived**: Target variable (0 = No, 1 = Yes)

## Steps

1. **Data Loading and Exploration**:
   - Load the training and test datasets.
   - Display data summary and check for missing values.

2. **Data Visualization**:
   - Use heatmaps, histograms, and pie charts to explore data distributions and correlations.

3. **Data Preprocessing**:
   - Handle missing values by imputing or dropping.
   - Convert categorical data into numerical format (e.g., mapping genders).

4. **Feature Selection**:
   - Drop irrelevant features such as `Name`, `Ticket`, and `Cabin`.

5. **Model Training and Evaluation**:
   - Train several machine learning models:
     - Logistic Regression
     - Gradient Boosting Classifier
     - Random Forest Classifier
     - Decision Tree Classifier
     - K-Nearest Neighbors
     - Naive Bayes
     - Support Vector Machine
   - Evaluate models based on accuracy scores.

6. **Final Prediction**:
   - Use the Gradient Boosting Classifier (selected as the best-performing model) to predict survival on the test dataset.
   - Save the results in a CSV file for submission.

## Results

- The best-performing model was **Gradient Boosting Classifier** with an accuracy of approximately **82%**.

## Requirements

To run this project, install the following Python libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Files

- `train.csv`: Training dataset.
- `test.csv`: Test dataset.
- `submission.csv`: Final prediction results.
- `Titanic project.ipynb`: Jupyter Notebook containing the code and analysis.

## Usage

1. Open the Jupyter Notebook.
2. Execute each cell in sequence to load the data, preprocess it, train models, and generate predictions.

## Acknowledgments

The dataset is provided by [Kaggle Titanic Competition](https://www.kaggle.com/c/titanic).
