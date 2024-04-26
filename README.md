Titanic Survival Prediction
Overview
This project aims to predict the survival of passengers aboard the Titanic using machine learning techniques. The sinking of the Titanic is one of the most infamous shipwrecks in history. On April 15, 1912, during her maiden voyage, the Titanic sank after colliding with an iceberg, resulting in the deaths of a large number of passengers and crew. One of the reasons for the high casualties was the lack of lifeboats for all passengers and crew.

In this project, we analyze the Titanic dataset, which contains demographics and passenger information from 891 of the 2224 passengers and crew aboard the Titanic. We explore the data, preprocess it, engineer features, and train several machine learning models to predict whether a passenger survived or not.

Dataset
The dataset used in this project is the famous Titanic dataset, which is publicly available on Kaggle. It contains the following features:

PassengerId: Unique identifier for each passenger
Survived: Survival (0 = No, 1 = Yes)
Pclass: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)
Name: Passenger's name
Sex: Passenger's sex
Age: Passenger's age in years
SibSp: Number of siblings/spouses aboard the Titanic
Parch: Number of parents/children aboard the Titanic
Ticket: Ticket number
Fare: Passenger fare
Cabin: Cabin number
Embarked: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)
Files
Titanic_dataset.ipynb: Jupyter Notebook containing the data analysis, preprocessing, feature engineering, model training, and evaluation.
Titanic-dataset.csv: CSV file containing the Titanic dataset.
Dependencies
Python 3.x
NumPy
Pandas
Matplotlib
Seaborn
Scikit-learn


Results
I achieved an accuracy of 80% on the test set using the best performing model. Further details about the model performance, feature importance, and evaluation metrics are provided in the Jupyter Notebook.

Conclusion
In this project, I successfully built machine learning models to predict the survival of passengers aboard the Titanic based on various features. Our analysis provides insights into the factors that influenced survival rates during the Titanic disaster.
