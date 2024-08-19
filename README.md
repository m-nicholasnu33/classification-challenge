# classification-challenge
Module 13 Challenge Assignment

### This Challenge project utilizes the two different classification models to determine which is likely to be best at filtering e-mails, ultimately to determine which model is best at determining if email is legitimate or spam.  The classification models utilized are:
* Logistic Regression
* Random Forest

### The challenge employs the following tools for the purpose of generating the data for evaluation:
* Pandas for utilizing Pandas notebooks
* Train_Test_Split from Sklearn to create training and test data sets to evaluate each model's usefulness
* Accuracy_Score from Sklearn to evaluate the percentage of accuracy of the model predictions vs. the test data.
* StandardScaler() from Sklearn is used to scale the training data to ultimately transform the testing data set to determine it's predictive reliability (score) when utilizing either of the 2 aforementioned models being compared in this analysis.

### In the final analysis, the Random Forest Model performed better, generating an accuracy score on the test data of 96.7% compared to the Logistic Regression Model accuracy score of 92.8%.

### AI had some concern that the Random Forest Model may be overfitting due to it's Training Model score near 100% (at 99.97%).  However, one of the benefits of applying the Random Forest Model is that it mitigates the risk of overfitting (vs. the Decision Tree Model) by applying many, many small and simple decision trees (weak learners) to perform an Ensemble Learner methodology, leading to the model's greater prediction accuracy and reliability.  Thus I am comfortable with the conclusion that the Random Forest model is best. 

### Note that I completed all work in this challenge without requiring outside assistance...