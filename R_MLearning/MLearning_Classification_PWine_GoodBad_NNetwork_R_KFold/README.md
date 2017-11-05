# MACHINE LEARNING: Portugal Wine. Two Class approach for Quality classification with Neural Network using R

<br>

This project develops neural Network algorithm of machine learning to classifythe quality of the wine "Good" or "Bad" according to 12 variables that characterize the wine subject to classification. I use nnet R library with a linout default option to get a logistic output.

![](http://arqmain.net/iris/nnet-RedWhite-plot.png)


I used the wine data set from the UCI Machine Learning data repository. The data can be found here [ http://archive.ics.uci.edu/ml/datasets/Wine+Quality ]. 

The original data is separated into white and red datasets. I combined them and created one additional variable: "Class" indicating "white" or "red" wine. After that, I re-coded the "quality" variable to indicate scores greater than or equal to 6 (denoted as "Good") or to indicate scores smaller than 6(denoted as "Bad").

I used "dfffull" dataset that considers all registers but replaces outliers by a "threshold" value which is generated for each variable using the upper limit of its Box-plot.

The model performance is evaluated using R, K fold cross-validation, and the ROC metric. I consider 70% and 30% original dataset splitting for the training and testing datasets respectively.
<br>

### Table of Contents   (  [  Link to R codes notebook ]( http://nbviewer.jupyter.org/github/arqmain/Machine_Learning/blob/master/R_MLearning/MLearning_Classification_PWine_GoodBad_NNetwork_R_KFold/Project8_Portugal_WINE_TwoClass_GoodBad_NNetwork.ipynb))

#### I Introduction

#### II Loading, EDA and Data Preprocessing

##### 21 Loading the data

##### 22 Exploratory Data Analysis (EDA) and Data Preprocessing

#### III Getting train and test datasets

#### IV Neural Network

##### 41 Building Machine Learning Model

##### 42 Plotting the Neural Network selected model

#### V Making predictions

#### VI Conclusion


<hr>

><i>Hector Alvaro Rojas<br>
>Data Science, Data Analysis, Visualizations and Applied Statistics / November 04, 2017<br>
>Email: <arqmain2010@gmail.com> <br>
>Url: [http://www.arqmain.net]   /   GitHub: [https://github.com/arqmain]</i>
