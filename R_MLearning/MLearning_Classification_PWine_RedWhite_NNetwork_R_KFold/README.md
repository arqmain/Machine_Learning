# MACHINE LEARNING: Portugal Wine. Two Class approach for Red and White classification with with Neural Network using R

<br>


This project presents a general way to run and compare several supervised learning algorithms applied to the classification problem, evaluating and selecting the best of them according to their performance by using the R library MLR and seven usual metrics: Acc, Kappa, F1, AUC, Sensitivity, and Specificity.

The entire structure of MLR library relies on this premise:

<i>- Create a Task</i>.<br> 
<i>- Make a Learner</i>. <br> 
<i>- Train Them</i>.<br> 

Creating a task means loading data in the package. Making a learner means choosing an algorithm ( learner)
which learns from task (or data). Finally, train them. Here you can learn more about MLR library [  Machine Learning in R: mlr Tutorial  ](https://mlr-org.github.io/mlr-tutorial/devel/html/).

The supervised learning algorithms to be considered here are:

Logistic Regression (LR)
Linear Discriminant Analysis (LDA)
K-Nearest Neighbors (KNN)
Classification and Regression Trees (CART)
Random Forest Classifier (RF)
Gaussian Naive Bayes (NB)
Support Vector Machines (SVM)


The dataset contains 5000 registers of clients who asked for a loan. There are six columns of measurements (fields) of the clients. These columns are the variables (features): MontoCredito; IngresoNeto; CoefCreditoAvaluo; MontoCuota; GradoAcademico.

The sixth column is the response variable "Tclient" which has two categories: Bad and Good. The dataset can be gotten from [  here ](http://www.arqmain.net/MLearning/Datasets/Loan2016last.csv).

The performance metrics are evaluated by using the "K fold cross validation" method.  I consider 70% and 30% original dataset splitting for the training and testing datasets respectively. 

The dataset used here is unbalanced in a proportion of 70.02% for "Good Clients" and 29.98% for "Bad clients". I use stratified sampling to get the train and test dataset, then I secure the original proportional representation for the categories of the response variable.

### Table of Contents   (  [  Link to R codes notebook ]( http://nbviewer.jupyter.org/github/arqmain/Machine_Learning/blob/master/R_MLearning/MLearning_Classification_PWine_RedWhite_NNetwork_R_KFold/Project7_Portugal_WINE_TwoClass_RedWhite_NNetwork.ipynb))

#### I Introduction

#### II Loading, EDA and Data Preprocessing

##### 21 Loading the data

##### 22 Exploratory Data Analysis (EDA) and Data Preprocessing

##### How about missing values?

#### III Getting train and test datasets

#### IV Neural Network

##### 41 Building Machine Learning Model

##### 42 Plotting the Neural Network selected model

#### V Making predictions

#### VI Conclusion


<hr>

><i>Hector Alvaro Rojas<br>
>Data Science, Data Analysis, Visualizations and Applied Statistics / November 02, 2017<br>
>Email: <arqmain2010@gmail.com> <br>
>Url: [http://www.arqmain.net]   /   GitHub: [https://github.com/arqmain]</i>

