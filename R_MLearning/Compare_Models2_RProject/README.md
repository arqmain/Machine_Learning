# MACHINE LEARNING: A general way to run and compare most common supervised learning algorithms with R-project

<br>


This project presents a general way to run and compare several supervised learning algorithms applied to the classification problem, evaluating and selecting the best of them according to a precision measurement (accuracy_score) and R. It is not used any specific library -like caret- to control the central procedure to get the modeling. 
The machine learning algoritms considered are:

* Logistic Regression (LR)
* Linear Discriminant Analysis (LDA)
* K-Nearest Neighbors (KNN)
* Classification and Regression Trees (CART)
* Random Forest Classifier (RF)
* Gaussian Naive Bayes (NB)
* Support Vector Machines (SVM)

The "accuracy score" of the models is measured using the "train/test split" method.

The project is based on the famous iris flowers dataset. The dataset contains 150 observations of iris flowers. There are four columns of measurements of the flowers in centimeters. This columns are the variables (features): SepalLength; SepalWidth; PetalLength; PetalWidth.

petal_sepal             
:-------------------------:
![](http://arqmain.net/iris/petal_sepal.png)

The fifth column is the species of the flower observed. All observed flowers belong to one of three species: Iris-setosa; Iris-versicolor; Iris-virginica.

iris_setosa             |  iris_versicolor	       |  iris_virginica
:-------------------------:|:-------------------------:|:-------------------------:
![](http://arqmain.net/iris/iris_setosa.png)  |  ![](http://arqmain.net/iris/iris_versicolor.png) |  ![](http://arqmain.net/iris/iris_virginica.png)

<br>

### Table of Contents   (  [  Link to R codes notebook ]( http://nbviewer.jupyter.org/github/arqmain/Machine_Learning/blob/master/R_MLearning/Compare_Models2_RProject/Compare_Models2_RProject.ipynb))

#### I Introduction

#### II Loading and Checking the Data

#### III Getting train and test datasets

#### IV Building models

###### 4.1  Logistic Regression  (LR)

###### 4.2  Linear Discriminant Analysis  (LDA)

###### 4.3  Support Vector Machine (SVM)

###### 4.4  k-Nearest Neighbors (KNN)

###### 4.5  Naive Bayes (NB)

###### 4.6  Classification and Regression Trees(CART)

###### 4.7  Random Forest (RF)

#### V Selecting best model

#### VI Making predictions

#### VII Conclusions

<hr>

><i>Hector Alvaro Rojas<br>
>Data Science, Data Analysis, Visualizations and Applied Statistics / September 2017<br>
>Email: <arqmain2010@gmail.com> <br>
>Url: [http://www.arqmain.net]   /   GitHub: [https://github.com/arqmain]</i>

