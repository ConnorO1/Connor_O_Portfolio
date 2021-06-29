# Project List

## [Project 1: Student_Performance Analysis](https://github.com/ConnorO1/Student_Performance)
#### Looking at factors that influence test performance
+ Data retrieved from: https://www.kaggle.com/spscientist/students-performance-in-exams.
+ Initial EDA performed with SQL looking at summary statistics/ influence of various factors on test scores.
+ Data visualisaiton with matplotlib and seaborn.
+ Simple linear regression model built (MSE = 10 on test set)
#### Potential improvements:   
  - Categorical feature variables don't provide enough info to make accurate prediction
  - One test score could be included in model as a feature
  - SVM (regressor), NN or Decision tree regressor(and variants) could also be tested and compared

<p align="center">
  <img src="https://github.com/ConnorO1/Student_Performance/blob/main/images/image_combined.png">
</p>

## [Project 2: Titanic_Model](https://github.com/ConnorO1/Titanic_Model)

#### Developing a model to predict survival onboard the Titanic

+ This is a project based on the competition from kaggle here: https://www.kaggle.com/c/titanic.
+ Data was provided by kaggle, description of data can be found in the link above.
+ Data visualisation with seaborn and Data Cleaning (Imputing, OneHotEncoding, Scaling) with sklearn.
+ 4 models built and 2 optimised using GridSearchCv.
+ Best classification model found was a optimised logistic regression model (app. 81% acc on validation set).

<p align="center">
  <img src="https://github.com/ConnorO1/Connor_O_Portfolio/blob/main/images/output2.png">
</p>

