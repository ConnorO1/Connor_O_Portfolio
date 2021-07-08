# Project List

# Predict_Absenteeism
ML project to predict Absenteeism from work

## [Project 1: Predicting Absenteeism from work](https://github.com/ConnorO1/Predict_Absenteeism-)
#### Determining features that indicate increased likelihood of extended absence from work
+ Data cleaning and feature engineering in python.
+ Extended absenteeism if no. of hours absent > median value of test data set
+ Logistic regression model optimised with grid search.
+ Module built to process and predict new entries.
+ New data visualised on tableau: [Tableau Public Viz](https://public.tableau.com/app/profile/connor5319/viz/AbsenteeismViz_16256837194020/Sheet1) 

![](/images/Sheet%203.png) 

## [Project 2: Student Performance Analysis](https://github.com/ConnorO1/Student_Performance)
#### Looking at factors that influence test performance
+ Data retrieved from: https://www.kaggle.com/spscientist/students-performance-in-exams.
+ Initial EDA performed with SQL looking at summary statistics/ influence of various factors on test scores.
+ Data visualisaiton with matplotlib and seaborn.
+ Simple linear regression model built (MSE = 10 on test set)
#### Potential improvements:   
  - Categorical feature variables not descriptive enough to make accurate prediction
  - One test score could be included in model as a feature
  - SVM (regressor), NN or Decision tree regressor(and variants) could also be tested and compared

![](/images/image_combined.png)


## [Project 3: Titanic Model](https://github.com/ConnorO1/Titanic_Model)

#### Developing a model to predict survival onboard the Titanic

+ Data was provided by kaggle, description of data can be found here: https://www.kaggle.com/c/titanic.
+ Initial EDA/Data visualisation and Data Cleaning with common python libraries (seaborn, sklearn).
+ Binary classification task: 4 models built and best performers optimised using GridSearchCv.
+ Best classification model found was an optimised logistic regression model.
+ Model and parameter search was not exhaustive. Improvements to be made.


![](/images/output2.png)


