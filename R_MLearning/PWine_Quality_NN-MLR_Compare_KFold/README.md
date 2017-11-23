# MACHINE LEARNING: Portugal Wine. Neural Network and MLR Regression Comparison to model Quality using R, Caret, and K fold cross-validation


<br>

This project develops Neural Network and Multiple Linear Regression machine learning models to compare both to predict the quality of the wine according to 12 variables that characterize the wine and its quality (score between 1 and 10).


![](http://arqmain.net/iris/NN_MLR.png)


I used the wine data set from the UCI Machine Learning data repository. The data can be found here [ http://archive.ics.uci.edu/ml/datasets/Wine+Quality ]. 

The original data is separated into white and red datasets. I combined them and created one additional variable: "type" indicating "white" or "red" wine. 

Even though the response variable -Quality- is ordinal, in this project it will be assumed to be a continuous variable which is possible to be predicted by the independent predictors, all of which are continuous.

The models are developing using Caret library and R, meantime its performances are evaluated using K fold cross-validation, Rsquared and RMSE metrics. I consider 70% and 30% original dataset splitting for the training and testing datasets respectively.

<br>

### Table of Contents   (  [  Link to R codes notebook ]( https://github.com/arqmain/Machine_Learning/blob/master/R_MLearning/PWine_Quality_NN-MLR_Compare_KFold/Project11_Portugal_WINE_MRegression_NN_NNET.ipynb))

#### I Introduction

#### II Loading the Data

#### III Getting train and test datasets

#### IV Modeling

##### 41 Neural Network Model

##### 42 Multiple Linear Regression (MLR) Model

#### V Model's Comparison

#### VI Conclusion


<hr>

><i>Hector Alvaro Rojas<br>
>Data Science, Data Analysis, Visualizations and Applied Statistics / November 22, 2017<br>
>Email: <arqmain2010@gmail.com> <br>
>Url: [http://www.arqmain.net]   /   GitHub: [https://github.com/arqmain]</i>
