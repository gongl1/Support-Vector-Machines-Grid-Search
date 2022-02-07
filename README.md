# Support-Vector-Machines-Grid-Search

# DataFrames

![1-Logo](Images/SVM-cancer.png)

Train Test Split

Train the Support Vector Classifier

Predictions and Evaluations

Gridsearch

Finding the right parameters (like what C or gamma values to use) is a tricky task! But luckily, we can be a little lazy and just try a bunch of combinations and see what works best! This idea of creating a 'grid' of parameters and just trying out all the possible combinations is called a Gridsearch, this method is common enough that Scikit-learn has this functionality built in with GridSearchCV! The CV stands for cross-validation which is the GridSearchCV takes a dictionary that describes the parameters that should be tried and a model to train. The grid of parameters is defined as a dictionary, where the keys are the parameters and the values are the settings to be tested.


![2-Logo](Images/SVM-iris.png)

EDA:

sns.pairplot(iris,hue='species',palette='Dark2')

sns.kdeplot( setosa['sepal_width'], setosa['sepal_length'], cmap="plasma", shade=True, shade_lowest=False)

Train Test Split

Call the SVC() model from sklearn and fit the model to the training data.

Get predictions from the model and create a confusion matrix and a classification report.

Gridsearch
