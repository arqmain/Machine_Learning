# Machine Learning: A comparison of supervised learning algorithms applied to the classification problem with caret R-project library

<br>


This project presents an application of several supervised learning algorithms to the classification problem, evaluating and selecting the best of them according to a precision measurement (accuracy_score) and the caret R-project library.


The machine learning algoritms considered are:



* Logistic Regression (LR)

* Linear Discriminant Analysis (LDA)

* K-Nearest Neighbors (KNN)

* Classification and Regression Trees (CART)

* Random Forest Classifier (RF)

* Gaussian Naive Bayes (NB)

* Support Vector Machines (SVM)

The estimation of the accuracy is based on the 10-fold cross validation method. 

The project is based on the famous iris flowers dataset. The dataset contains 150 observations of iris flowers. There are four columns of measurements of the flowers in centimeters. This columns are the variables (features): SepalLength; SepalWidth; PetalLength; PetalWidth.

petal_sepal             
:-------------------------:
![](http://arqmain.net/iris/petal_sepal.png)

The fifth column is the species of the flower observed. All observed flowers belong to one of three species: Iris-setosa; Iris-versicolor; Iris-virginica.

iris_setosa             |  iris_versicolor	       |  iris_virginica
:-------------------------:|:-------------------------:|:-------------------------:
![](http://arqmain.net/iris/iris_setosa.png)  |  ![](http://arqmain.net/iris/iris_versicolor.png) |  ![](http://arqmain.net/iris/iris_virginica.png)

<br>

### Table of Contents   (  [  Link to R codes notebook ](http://nbviewer.jupyter.org/github/arqmain/Machine_Learning/blob/master/R_MLearning/MLearning_Classification_Comparison_R_Caret/MLearning_Classification_Comparison_R_Caret.ipynb))

#### I Introduction

#### II Import R libraries

#### III Loading and Checking the Data

#### IV Checking the data

###### How about missing values?

#### V Summarize the dataset

#### VI Data Visualization

###### 6.1 Univariate plots to better understand each attribute

###### 6.2 Multivariate plots to better understand the relationships between attributes

#### VII Machine Learning Models

###### 7.1 Train Dataset, Validation Dataset and Test Harness

###### 7.2 Build Models

###### 7.3 Select Best Model

###### 7.4 Make Predictions

#### VIII Conclusion

<hr>

><i>Hector Alvaro Rojas<br>
>Data Science, Data Analysis, Visualizations and Applied Statistics / August 2017<br>
>Email: <arqmain2010@gmail.com> <br>
>Url: [http://www.arqmain.net]   /   GitHub: [https://github.com/arqmain]</i>

