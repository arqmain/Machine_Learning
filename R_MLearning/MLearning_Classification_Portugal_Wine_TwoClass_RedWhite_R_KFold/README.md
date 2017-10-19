# MACHINE LEARNING: Portugal Wine under Two Class approach for red and white classification using R and K fold cross-validation

<br>


This project presents a general way to run and compare several supervised learning algorithms applied to the classification problem, evaluating and selecting the best of them according to their performance by using R. 

The ROC metric was used to select the models.  The performance metrics are evaluated by using the "K fold cross validation" method. I consider 70% and 30% original dataset splitting for the training and testing datasets respectively.
 
The supervised learning algorithms to be considered here are:


* Classification and Regression Trees (CART)
* Boosted Tree C5.0 (C5)
* Support Vector Machines (SVM)
* K-Nearest Neighbors (KNN)
* Random Forest Classifier (RF)

We will use the famous Portugal wine dataset.  Two datasets are available of which one dataset is about red wine and have 1599 different varieties and the other is on white wine and have 4898 varieties. I have combined them into one dataset named "wine" and created one additional variable "Class" with its categories "white" and "red".

The original data along with detailed description can be found here [ http://archive.ics.uci.edu/ml/datasets/Wine+Quality].

The dataset used here is unbalanced in a proportion of 75.4% for "White wine" and 24.6% for "Red wine". I use stratified sampling to get the train and test dataset, then I secure the original proportional representation for the categories of the response variable. 

The ROC metric used to select the models are the one usually used for this kind of unbalanced dataset.  You can get more information about it in this publication by [ Shir Meir Lador: What metrics should be used for evaluating a model on an imbalanced data set? ](https://medium.com/towards-data-science/what-metrics-should-we-use-on-imbalanced-data-set-precision-recall-roc-e2e79252aeba)






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

<u>Variables Overview</u>

<table align="left">
      <tbody>
  <tr>
    <td><p aling="left"><b>MontoCredito</b> (Credit Amount)<br>

1 Very Low<br>
2 Low<br>
3 Medium<br>
4 High<br></p>
</td>
        <td><p aling="left"><b>MontoCuota</b> (AmountFee)<br>
1 Very Low<br>
2 Low<br>
3 Medium<br>
4 High<br></p>
</td>

  </tr>
  <tr>
    <td><p aling="left"><b>IngresoNeto</b> (Net Income)<br>

1 Very Low<br>
2 Low<br>
3 Medium<br>
4 High<br></p>
</td>
        <td><p aling="left"><b>GradoAcademico</b> (AcademicDegree)<br>
1 Bachelor<br>
2 Graduate<br>
3 Master<br>
4 Doctorate<br></p>
</td>

  </tr>
  <tr>
    <td><p aling="left"><b>CoeficienteCreditoAvaluo</b> (CoefficientCreditValuation)<br>
<br>Score from 1 to 12. The bigger the better.<br>
</p>
</td>
        <td><p aling="left"><b>Tclient</b> (Typeclient)<br>
1 Bad<br>
2 Good</p>
</td>

  </tr>  
   </tbody>
</table>

The performance metrics are evaluated by using the "K fold cross validation" method.  I consider 70% and 30% original dataset splitting for the training and testing datasets respectively. 

The dataset used here is unbalanced in a proportion of 70.02% for "Good Clients" and 29.98% for "Bad clients". I use stratified sampling to get the train and test dataset, then I secure the original proportional representation for the categories of the response variable.

### Table of Contents   (  [  Link to R codes notebook ]( http://nbviewer.jupyter.org/github/arqmain/Machine_Learning/blob/master/R_MLearning/MLearning_Classification_Comparison_R_MLR_KFold/Project3_RProject_MLR_CVKFold.ipynb))


#### I Introduction

#### II Loading and checking the data

##### 21 Loading the data

##### 22 Checking the data

##### How about missing values?

#### III Getting train and test datasets

#### IV Building models

#### V Selecting best model

#### VI Making predictions

#### VII Conclusion


<hr>

><i>Hector Alvaro Rojas<br>
>Data Science, Data Analysis, Visualizations and Applied Statistics / October 12, 2017<br>
>Email: <arqmain2010@gmail.com> <br>
>Url: [http://www.arqmain.net]   /   GitHub: [https://github.com/arqmain]</i>
