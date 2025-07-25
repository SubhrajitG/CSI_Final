# German-credit-data-classifier

 The analyzer can analyze some data collected by a bank giving a loan. The dataset consists of 1000 datapoints of categorical and numerical dataas well as a good credit vs bad credit metric which has been assigned by bank employees.The code in this repository contains a randomforest models to try to predict the credit rating that a bank employee would assign given some datapoints.

# Dataset
The dataset consists of 1000 datatpoints each with 20 variables (dimensions) 7 are numerical and 13 are categorical. The categorical data is encoded according to terms which have meaning to the bankers such as current employment timeframe:

A71 : unemployed <br />
A72 : ... < 1 year <br />
A73 : 1 <= ... < 4 years <br />
A74 : 4 <= ... < 7 years <br />
A75 : .. >= 7 years <br />
Or what kind of housing the person has:

A151 : rent <br />
A152 : own<br />
A153 : for free<br />
Other data provided in the dataset contains numerical information such as:

Duration of the loan in months
Credit amount<br />
Age in years<br />
See the Description file attached to the repository for further details on the data. Source:https://archive.ics.uci.edu/ml/datasets/Statlog+%28German+Credit+Data%29

# classifier
Random forest is a type of supervised machine learning algorithm based on ensemble learning. Ensemble learning is a type of learning where you join different types of algorithms or same algorithm multiple times to form a more powerful prediction model. The random forest algorithm combines multiple algorithm of the same type i.e. multiple decision trees, resulting in a forest of trees, hence the name "Random Forest". The random forest algorithm can be used for both regression and classification tasks

# Steps for building the model

1.Import Libraries<br />
2.Importing Dataset<br />
3.Exploring dataset
   * assigning columns names to data <br />
   * making data exploration by pairplot<br />
   * creating dummy variables for the categorical features
   
4.Preparing Data For Training
   * spliting dataset
   
5.Training the Algorithm
   * building random forest classifer
   
6.Evaluating the Algorithm
   * confusion matrix<br />
   * ROC curve
     
