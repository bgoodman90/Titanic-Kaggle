# Titanic-Kaggle
Working on the Titanic Kaggle Competition

I will update this with files I'm working on for the competition.

So far I have written code to implement the following models on the Titanic Dataset:
-Logistic Regression
-Support Vector Machines
-Random Forest
-AdaBoost on Tree Stumps
-Unpruned Categorization Trees with and without Bagging
-K-Nearest Neighbours with PCA (to help with the curse of dimensionality)
-Majority Voting of Classifiers (Hard and Soft (or Probability Voting)

For a few of the models I have implemented a Grid Search (with Cross Validation) to determine the best hyper-parameters.
I have analyzed the error using K-fold Cross Validation with 10 splits.

So far, the best models I have determined are the Majority Voters which both have a mean accuracy of approximately 82.5%.  Apparently based on the rankings for this Kaggle competition that is a decent accuracy, but I am going to work more to see if I can find something better.
