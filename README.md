# Logistic Regression on Titanic Dataset

## Overview

This project involves performing logistic regression analysis to predict the survival of passengers on the Titanic. The analysis is based on features such as age, sex, passenger class, and other relevant attributes. Logistic regression is used to model the probability of a passenger's survival, providing insights into the factors that influenced survival rates.

## Features

- **Logistic Regression Model**: Utilized logistic regression to predict the binary outcome of survival (yes/no).
- **Feature Engineering**: Incorporated features like age, sex, passenger class, fare, and embarked location.
- **Model Evaluation**: Assessed model performance using metrics such as accuracy, precision, recall, and F1 score.

## Steps

1. **Load Data**: Import the Titanic dataset and explore its structure.
2. **Data Preprocessing**:
   - Handle missing values.
   - Encode categorical variables.
   - Feature scaling (if necessary).
3. **Feature Selection**: Identify relevant features for the logistic regression model.
4. **Model Building**:
   - Split the data into training and testing sets.
   - Train the logistic regression model using the training data.
5. **Model Evaluation**:
   - Evaluate the model using the test set.
   - Calculate performance metrics such as accuracy, precision, recall, and F1 score.
6. **Results Analysis**: Interpret the results to understand the impact of various features on passenger survival.

## Prerequisites

- **Python 3.x**
- **Libraries**: 
  - pandas
  - numpy
  - scikit-learn
  - matplotlib
  - seaborn

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/titanic-logistic-regression.git
   ```
2. Navigate to the project directory:
   ```bash
   cd titanic-logistic-regression
   ```
3. Install the necessary libraries:
   ```bash
   pip install -r requirements.txt
   ```
4. Open and run the `Logistic_Regression_Titanic.ipynb` notebook in Jupyter Notebook or Google Colab.

## Results

The logistic regression model was able to predict the survival of Titanic passengers with a [insert accuracy/precision/recall/F1 score] score. The analysis provided insights into the significance of features such as age and sex in determining survival likelihood.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
