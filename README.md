# Project List

## [Project 1: Student Performance Analysis](https://github.com/ConnorO1/Student_Performance)
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


## [Project 2: Titanic Model](https://github.com/ConnorO1/Titanic_Model)

#### Developing a model to predict survival onboard the Titanic

+ Data was provided by kaggle, description of data can be found here: https://www.kaggle.com/c/titanic.
+ Initial EDA/Data visualisation and Data Cleaning with common python libraries (seaborn, sklearn).
+ Binary classification task: 4 models built and best performers optimised using GridSearchCv.
+ Best classification model found was an optimised logistic regression model.
+ Model and parameter search was not exhaustive. Improvements to be made.


![](/images/output2.png)


