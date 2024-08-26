# ML_Assignment
# B.Tech CSE AI and DS (3rd Semester) - Assignment Solutions

This repository contains the solutions for the B.Tech CSE AI and DS (3rd Semester) assignment. The tasks involve basic operations on datasets, including exploration, data splitting, and linear regression modeling.

## Table of Contents
- [Dataset Exploration](#dataset-exploration)
- [Data Splitting](#data-splitting)
- [Linear Regression](#linear-regression)
- [How to Run](#how-to-run)
- [Dependencies](#dependencies)

## Dataset Exploration

### Task:
- Load the Iris dataset from `sklearn.datasets`.
- Display the first five rows of the dataset.
- Display the shape of the dataset.
- Provide summary statistics (mean, standard deviation, min, max) for each feature.

### Code Overview:
The script loads the Iris dataset, converts it into a Pandas DataFrame, and performs basic exploratory data analysis (EDA) to understand the dataset's structure and characteristics.

## Data Splitting

### Task:
- Split the Iris dataset into training and testing sets using an 80-20 split.
- Print the number of samples in both the training and testing sets.

### Code Overview:
The script uses `train_test_split` from `sklearn.model_selection` to divide the dataset into training and testing sets, ensuring that 80% of the data is used for training and 20% for testing. The script then prints out the number of samples in each set.

## Linear Regression

### Task:
- Use a dataset with the features `YearsExperience` and `Salary`.
- Fit a linear regression model to predict `Salary` based on `YearsExperience`.
- Evaluate the model's performance using Mean Squared Error (MSE) on the test set.

### Code Overview:
The script creates a small dataset with `YearsExperience` and `Salary` features, splits it into training and testing sets, and fits a linear regression model. It then evaluates the model's performance by calculating the Mean Squared Error (MSE) on the test set and prints the slope and intercept of the regression line.

## How to Run

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/OmDwivedi12/ML_Assignment.git
cd ML_Assignment

## Dependencies 

Ensure you have the following Python libraries installed:
-> scikit-learn
-> pandas
You can install them using pip:
((pip install scikit-learn pandas))
