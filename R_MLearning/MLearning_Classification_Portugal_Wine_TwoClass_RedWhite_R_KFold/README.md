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


### Table of Contents


#### [  Module 1: Data Preprocessing and Exploratory Data Analysis (EDA) ]( http://nbviewer.jupyter.org/github/arqmain/Machine_Learning/blob/master/R_MLearning/MLearning_Classification_Portugal_Wine_TwoClass_RedWhite_R_KFold/Project4_Portugal_WINE_TwoClass_EDA.ipynb)

#### [  Module 2: Solving project with original dataset df ]( http://nbviewer.jupyter.org/github/arqmain/Machine_Learning/blob/master/R_MLearning/MLearning_Classification_Portugal_Wine_TwoClass_RedWhite_R_KFold/Project4_Portugal_WINE_TwoClass_Dataset20DF.ipynb)

#### [  Module 3: Solving project with original dataset dff ]( http://nbviewer.jupyter.org/github/arqmain/Machine_Learning/blob/master/R_MLearning/MLearning_Classification_Portugal_Wine_TwoClass_RedWhite_R_KFold/Project4_Portugal_WINE_TwoClass_DatasetDFF.ipynb)

#### Module 4: Solving project with original dataset dfffull

<hr>

><i>Hector Alvaro Rojas<br>
>Data Science, Data Analysis, Visualizations and Applied Statistics / October 12, 2017<br>
>Email: <arqmain2010@gmail.com> <br>
>Url: [http://www.arqmain.net]   /   GitHub: [https://github.com/arqmain]</i>
