# Breast Cancer Prediction using SVM classification(SVC)
Breast cancer dataset is one among the popular dataset that is available, finding out whether the patient has Breast cancer or not is the problem. <br/>
Here, I have used GridSearchCV for finding the best parameters for SVC and predicted the test data with the best model.<br/>
## Importing necessary libraries
Import basic libabries for python and Data Visualization, libraries required for data preprocessing, Model Building and Evaluation Metrics.
## Data Analysis and Preprocessing
1. Loading data that is available in csv and study it, analysing categorical and numerical columns present in the data.<br/>
2. Checking for any null values or other characters present in the data with pandas functions.<br/>
3. Plotting the numerical columns to see the distribution and checking the correlation between the features.<br/>
4. Splitting features(X) and target(y)<br/>
5. Further splitting the X and y into X_train,X_test and y_train,y_test.<br/>
6. Applying Standard scaling for numerical columns present in X_train and X_test.<br/>
## Model Building
1. Using Hyper parameter tuning with CV to find the parameters for SVC.<br/>
2. GridSearchCV will give us the best_params_ to be used for model bulding.<br/>
3. Using the resultant best model, building the model for X_train and y_train and further predicting y_pred with X_test data.<br/>
## Evaluation Metrics
1. Evaluating the model with Accuracy, confusion matrix, precision, recall and AUC ROC Score.
2. Got good score and the score for train and test data are comparable and we could see the model is the right fit.
