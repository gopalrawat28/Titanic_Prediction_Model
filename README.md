Problem Statement:

The sinking of the RMS Titanic is one of the most infamous shipwrecks in history. On April 15, 1912, during her maiden voyage, the Titanic sank after colliding with an iceberg, resulting in the deaths of a large number of passengers and crew. Despite the tragedy, there were some passengers who survived due to various factors such as their location on the ship, age, gender, and other socio-economic factors.

In this challenge, your task is to analyze the Titanic passenger data (including features such as age, sex, ticket class, etc.) and build a predictive model that accurately predicts whether a passenger survived or not. You are provided with a training dataset containing information about a subset of the passengers (including whether they survived or not) and a test dataset where you need to predict the survival outcomes for a different set of passengers.

The goal of this challenge is to develop a machine learning model that can effectively classify passengers as survivors or non-survivors based on the available data. This is a binary classification problem, where the target variable is whether a passenger survived (1) or not (0).

Data Description:

The dataset provided contains the following features:
- PassengerId: A unique identifier for each passenger
- Survived: Whether the passenger survived (1) or not (0) - This is the target variable
- Pclass: Ticket class (1st, 2nd, or 3rd)
- Name: Passenger's name
- Sex: Passenger's gender
- Age: Passenger's age in years
- SibSp: Number of siblings/spouses aboard the Titanic
- Parch: Number of parents/children aboard the Titanic
- Ticket: Ticket number
- Fare: Passenger fare
- Cabin: Cabin number
- Embarked: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

Evaluation Metric:

The evaluation metric for this challenge is accuracy, which is the proportion of correctly predicted outcomes to the total number of predictions. Your submission will be evaluated based on the accuracy of your predictions on the test dataset.
