# Titanic-Machine-Learning-Analysis

## Project Title
**Titanic Survival Analysis with Machine Learning**

## Description
This project applies various machine learning models to predict the survival rates of passengers aboard the Titanic. The analysis explores the relationships between survival and different passenger characteristics, such as age, sex, and class.

## Dataset
The dataset used in this project contains detailed information about the passengers aboard the Titanic and is organized into several columns as follows:

- **PassengerId**: A unique identifier for each passenger.
- **Survived**: Indicates if a passenger survived the disaster (1) or did not (0).
- **Pclass**: The class of the ticket the passenger purchased (1st, 2nd, or 3rd class).
- **Name**: The name of the passenger.
- **Sex**: The passenger's gender.
- **Age**: The age of the passenger.
- **SibSp**: The number of siblings or spouses the passenger had aboard.
- **Parch**: The number of parents or children the passenger had aboard.
- **Ticket**: The ticket number.
- **Fare**: The amount of money paid for the ticket.
- **Cabin**: The cabin number where the passenger stayed.
- **Embarked**: The port where the passenger boarded the Titanic (C = Cherbourg; Q = Queenstown; S = Southampton).

## Models
We trained multiple models to predict survival:
- Logistic Regression
- K-Nearest Neighbors
- Decision Trees
- Random Forests
- Support Vector Machines

The Random Forest model achieved the highest accuracy and is the focus of further evaluations and tuning.

## Results
The analysis revealed that features like passenger class, sex, and age significantly influenced survival probabilities. The best-performing model, Random Forest, had an accuracy of over 92%, as evaluated using K-Fold cross-validation and ROC AUC scores.
