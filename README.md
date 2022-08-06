# Module_12

## Background 

Credit risk poses a classification problem that’s inherently imbalanced. The reason is that healthy loans easily outnumber risky loans. Therefore, this repository will be using various techniques to train and evaluate models with imbalanced classes. Then using a dataset of historical lending activity from a peer-to-peer lending services company, a model that can identify the creditworthiness of borrowers will be built.

## What is created?
Using the knowledge learnt from imbalanced-learn library and the logistic regression model, comparison of two dataset versions will be done. First, the original dataset. Second, resampling the data by using the RandomOverSampler module from the imbalanced-learn library. In doing so this will help find the target classes, training a logistic regression classifier, the calculation of the balanced accuracy score, a generation of a confusion matrix, and a classification report. 

## Steps:

- Split the Data into Training and Testing Sets
- Create a Logistic Regression Model with the Original Data
- Predict a Logistic Regression Model with Resampled Training Data
- Write a Credit Risk Analysis Report

# Risk Analysis Report

### Overview of the Analysis

The purpose of the Risk Analysis Report is to recount. compare and correlate the difference between two datatsets which may pose a classification problem due to the imbalances in the dataframes. Thus, this report will detail which type of loan has been fitted to the logisitics regression model. Therefore, gaining insight to whether or not a model can be created to identify and report the creditworthiness of borrowers. Furthermore, the financial information detiling the lending data, will be needed to predict both the high risk loans and healthy loans compatability with logisitcs regression model. The basic information that is needed to be extracted, however, include the value_counts. predict function, accuracy_score, confusion_matrix and classification report. In doing so, these variables will help in creating a justifyable argument as to why either loan is more worhtwhile. But without a proper structure to the stages of the machine learning process, it will be worthless. Therefore, a simple process was devised to be used as a part of the notebook and analysis. First the importation of modules, reading in the data, seperating the data (the X and y variables), importing the train_test_learn module which will then be used to split, assign and fit the data, to then be used to predict the accuracy, confusion_matrix and classification of the loans. Methods to collect the data, and information was also utilised with LogisticRegression, RandomOverSampler and train_test_split importations used in order to help refine the findings from the notebook.

### Results

* Machine Learning Model 1:
  
Model 1 provided evidence of it's precision through the presentation of the accuracy_score, confusion_matrix and classification_report which helps in describing the model's validity. Providing an accuracy of 0.9918489475856377 or 99.18% respectively, as well as precision of 1.00 and 0.85, and recall scores of 0.99 and 0.91. Therefore, providing evidence that Model 1's correctness is just and fair.

* Machine Learning Model 2:

Model 2 which used oversampled data provided an accuracy of 0.9938093272802311 or 99.38%, with precision of 1.00 and 0.84, and recall scores of 0.99 and 0.99. Thus, it is sensible to assume, Model 2 provides accuracy and precision.

### Summary

From the results and findings discovered from both the machine learning models, it would seem that both provide very accurate predictions and accuracy, with Model 2 only beating out Model 1 in accuracy by 0.2% and recall scores, whils't the first model's precision for the '1's is 0.01 larger than that of 
the second model. Therefore, it is reasonable to suggest that both models provide a great performance, however, in order to use the model that achieved greater scores, Model 2 will perform better. However, the performance depends solely on the problem that is trying to be solved. As said before, both Model 1 and Model 2 have variations in the predictions for the "1"'s and "0"'s, thus depending on which variable is more important, both model's can be used. Thus, i recommend both Models, as they both provide evidence to a dataset that is accurate, precise and correct, depending on which variable is most important. Healthy Loans however, seem to provide the best results for both models.
