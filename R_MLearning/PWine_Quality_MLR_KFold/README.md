# MACHINE LEARNING:Learning: Portugal Wine. Multiple Linear Regression to model Quality using R and K fold cross-validation

<br>

This project develops Multiple Linear Regression machine learning model to predict the quality of some Portugal wine. wine. The model performance was evaluated using R, K fold cross-validation, and Rsquared and RMSE metrics. 


![](http://arqmain.net/iris/WinesandSpitis.jpg)


I used the wine data set from the UCI Machine Learning data repository. The data can be found here [ http://archive.ics.uci.edu/ml/datasets/Wine+Quality ]. 

All wines are produced in a particular area of Portugal. Data are collected on 12 different properties of the wines one of which is Quality, based on sensory data. Quality is an ordinal variable with a possible ranking from 1 (worst) to 10 (best). Each variety of wine is tasted by three independent tasters and the final rank assigned is the median rank given by the tasters.

Even though the response variable -Quality- is ordinal, in this project it will be assumed to be a continuous variable which is possible to be predicted by the independent predictors, all of which are continuous.

I do not consider two variables that appear in the original base. They could generate a problem of multicollinearity in the process of classification. So, we got rid of them. At the same time, I keep all the register of the original database but replace the upper outliers by its corresponding Threshold value which is generated for each variable using the upper limit of its Box-plot. The application of this rule does not reduce the original data size because it does not eliminate any register. So, the data size is the same as the original dataset (6497).

<br>

### Table of Contents   (  [  Link to R codes notebook ]( https://github.com/arqmain/Machine_Learning/blob/master/R_MLearning/PWine_Quality_MLR_KFold/Project10_Portugal_WINE_MRegression.ipynb))

#### I Introduction

#### II Loading the Data Preprocessing

#### III Getting train and test datasets

#### IV Multiple Linear Regression Model (MLR)

##### 41 Find model equation

##### 42 Model Diagnostics

##### 43 Model Consolidation

#### V Making predictions

##### 51 Predictions mlr model on training dataset

##### 52 Predictions mlr model on testing dataset

##### 53 Predictions mlr model on new data

#### VI Conclusion


<hr>

><i>Hector Alvaro Rojas<br>
>Data Science, Data Analysis, Visualizations and Applied Statistics / November 17, 2017<br>
>Email: <arqmain2010@gmail.com> <br>
>Url: [http://www.arqmain.net]   /   GitHub: [https://github.com/arqmain]</i>
