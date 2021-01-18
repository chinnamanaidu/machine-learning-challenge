# Machine Learning Homework - Exoplanet Exploration

![exoplanets.jpg](Images/exoplanets.jpg)

### Before You Begin

1. Three models are chosen  , in the first model : x_train, x_test is from the csv file, based on that scaller files are using minmax scaller  and GridSearchCV API used to generate the predictions. LogisticRegression is used
grid.fit(X_train, y_train.ravel())  took almost 2 hours to complete 45 fits.

2. Second model,  the KNeighborsClassifier is used to get the score same as model one but the grid.fit uses X_train_minmax scaller object is used in 
grid.fit(X_train_minmax, y_train.ravel())

3. The third model SVC is used to get the kernel linear and based on training the model using X_train and y_train, the score for test is evaluated it came close to 0.765 as good model, the classification report is also prepared