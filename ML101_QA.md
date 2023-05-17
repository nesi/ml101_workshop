# Welcome to ML101 on NeSI

[DATE]

## Resources
- Workshop material:
    - Tutorial https://github.com/nesi/sklearn_tutorial
    - Scikit-Learn documentation https://scikit-learn.org/stable/
- Additional content:
    - Jupyter shortcuts: https://towardsdatascience.com/jypyter-notebook-shortcuts-bf0101a98330
    - Info on hyperparameter tuning:
https://scikit-learn.org/stable/modules/grid_search.html
    - Python data science handbook (by Jake VanderPlas)
https://jakevdp.github.io/PythonDataScienceHandbook/
- Got questions? You can email us at support@nesi.org.nz
- Want to get notified about other training events? Sign up to receive the NeSI newsletter and/or training notifications by clicking here: http://eepurl.com/grV9if

## Sign in

Please place your name, pronouns, and institutional affiliation(s) below

-
-
-
-
-
-
-
-
-
-
-
-
-
-
-
-
-
-
-
-

## 02.1-Machine-Learning-Intro.ipynb

### What is Machine Learning?

What does machine learning evoke for you? What comes to your mind?

-
-
-
-
-
-
-
-
-
-

### A Simple Example: the Iris Dataset

**Question:** If we want to design an algorithm to recognize iris species, what might the data be?

What would `n_samples` refer to?

-
-
-
-
-
-
-
-
-
-

What would `n_features` refer to?

-
-
-
-
-
-
-
-
-
-

**Exercise:** Change `x_index` and `y_index` in the above script and find a combination of two parameters which maximally separate the three classes. Which good combinations have you found?

-
-
-
-
-
-
-
-
-
-

**Audience questions:** Use the space below to share any questions or comments.

-
-
-
-
-

### Bonus questions

**Question:** If your job is to classify 1000 grey pictures of size 10x10, what is the number of features?

A: 10
B: 100
C: 1000


## 02.2-Basic-Principles.ipynb

### The Scikit-learn Estimator Object

**Question:** Can you name other parameters of `LinearRegression`? Use the official documentation to find them.

-
-
-
-
-
-
-
-
-
-

**Audience questions:** Use the space below to share any questions or comments.

-
-
-
-
-

### Supervised Learning: Classification

**Exercise (breakout rooms, 5+5 min):** Use a different estimator on the same problem, `sklearn.svm.SVC`

Does this exercise trigger some questions or comments? Use this space below to share your thoughts :-).

-
-
-
-
-
-
-
-
-
-

**Audience questions:** Use the space below to share any questions or comments.

-
-
-
-
-

### Supervised Learning: Regression

**Question:** Explore the RandomForestRegressor object. What arguments are available to `RandomForestRegressor`?

-
-
-
-
-
-
-
-
-
-

**Audience questions:** Use the space below to share any questions or comments.

-
-
-
-
-

### Flow Chart: How to Choose your Estimator

**Question:** If you want to predict a the daily consumption of beer in Wellington using the average daily rainfall, temperature and solar radiation over the past 10 years, which estimators would you try first?

-
-
-
-
-
-
-
-
-
-

### Quick Application: Optical Character Recognition

**Exercise (breakout rooms, 5 min):** fit the `clf` model to the training dataset.

**Audience questions:** Use the space below to share any questions or comments.

-
-
-
-
-

### Bonus questions

**Question:** what do you think the effect of `normalize=True` is in creating the linear regression model?

A: It rescales the data to be within (0, 1), which suits many machine learning algorithms.
B: It tells the algorithm that the data follow a normal distribution.
C: It helps the algorithm detect outliers.

## 03.2-Regression-Forests.ipynb

### Motivating Random Forests: Decision Trees

**Question:** Do you see any problems when we change the depth of the decision tree?

-
-
-
-
-
-
-
-
-
-

**Audience questions:** Use the space below to share any questions or comments.

-
-
-
-
-

### Example: Random Forest for Classifying Digits

**Exercise (breakout rooms, 5+5 min):** Repeat this classification task with `sklearn.ensemble.RandomForestClassifier`.  How does the `max_depth`, `max_features`, and `n_estimators` affect the results? What's the best performance you obtained?

-
-
-
-
-
-
-
-
-
-

**Audience questions:** Use the space below to share any questions or comments.

-
-
-
-
-

## 05-Validation.ipynb

### Validating Models

**Question:** What's wrong with the K-neighbors classifier performance?

-
-
-
-
-
-
-
-
-
-

**Audience questions:** Use the space below to share any questions or comments.

-
-
-
-
-

### Cross-Validation

**Question:** If you were dealing with time series data, would you implement it differently? You may find some ideas in the official Scikit-Learn documentation.

-
-
-
-
-
-
-
-
-
-

**Audience questions:** Use the space below to share any questions or comments.

-
-
-
-
-

### Overfitting, Underfitting and Model Selection

**Question:** Which polynomial degree gives the most stable estimate when changing the input data, while keeping a high score?

-
-
-
-
-
-
-
-
-
-

**Audience questions:** Use the space below to share any questions or comments.

-
-
-
-
-

### Bonus questions

**Question:** What does overfitting refer to?

A: Your model is too flexible given the amount of data you have.
B: Your model fits well on training data and predicts well on validation data.
C: Your model fits well on training data and predicts poorly on validation data.
D: Your model will have good performances on future data.
E: You need to collect more training data.

## 06.1-Practice-Penguins.ipynb

### Loading and visualizing the dataset

**Exercise (breakout rooms, 15 min):** Use the space below to share any questions or comments.

-
-
-
-
-

### Fit a baseline model: logistic regression

**Exercise (breakout rooms, 15 min):** Use the space below to share any questions or comments.

-
-
-
-
-

### Fit a random forest model

**Exercise (breakout rooms, 10 min):** Use the space below to share any questions or comments.

-
-
-
-
-

## 06.2-Practice-Abalone.ipynb

Use the space below to share any questions or comments.

-
-
-
-
-
