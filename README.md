**Titanic Survival Prediction using Naive Bayes Algorithm
Overview**
This project aims to predict the survival of passengers on the Titanic using the Naive Bayes algorithm. 
The Titanic dataset provides various details about the passengers, such as age, gender, class, and more, which are used to determine the likelihood of survival.
The Naive Bayes algorithm, a probabilistic classifier based on Bayes' Theorem, is well-suited for this classification task, particularly when features are conditionally independent.
**Requirements**
To run this project, the following Python libraries are required:
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
**Feature Selection**
We will use the following features for prediction:
Pclass: Socio-economic class (1 = Upper, 2 = Middle, 3 = Lower)
Sex: Gender of the passenger (male, female)
Age: Age of the passenger
Fare: Ticket fare
**Algorithm**
The Naive Bayes classifier is used to model this classification problem.
It works under the assumption that the features are independent of each other given the outcome.
Specifically, the Gaussian Naive Bayes model is employed to handle continuous features like Age and Fare.

Steps:
Data Preprocessing: Handle missing values, encode categorical features, and scale numerical features.
Model Training: Train the Naive Bayes model on the processed data.
Model Testing: Evaluate the model on the test data.
Model Evaluation
The model is evaluated using the following metrics:

Accuracy: Proportion of correctly predicted outcomes.
**Contributing**
Contributions are welcome! Please feel free to open an issue or submit a pull request for improvements, suggestions, or bug fixes.
