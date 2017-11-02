# MACHINE LEARNING: Portugal Wine. Two Class approach for Red and White classification with Neural Network using R

<br>

This project develops neural Network algorithm of machine learning to classify wine "white" or "red" according to 12 variables that characterize the wine subject to classification. The model performance was evaluated using R, K fold cross-validation, and the ROC metric.

I used the wine data set from the UCI Machine Learning data repository. The data can be found here [ http://archive.ics.uci.edu/ml/datasets/Wine+Quality ]. 

The original data is separated into white and red datasets. I combined them and created one additional variable: "Class" indicating "white" or "red" wine. Our original dataset is an imbalance one. There are 6497 registers but only 1599 (24.6%) are of the red class of wine. So, I decided using the ROC metric to compare the model's performance.

I used "dfffull" dataset that considers all registers but replaces outliers by a "threshold" value which is generated for each variable using the upper limit of its Box-plot.

The ROC metric is a metric that can be used to evaluate models based on unbalanced datasets. You can get more information about it in this publication by [ Shir Meir Lador: What metrics should be used for evaluating a model on an imbalanced data set? ](https://medium.com/towards-data-science/what-metrics-should-we-use-on-imbalanced-data-set-precision-recall-roc-e2e79252aeba)

Finally, whenever I work in some modeling project I try always to remember what the late brilliant George Box one time stated: " ... remember that all models are wrong; the practical question is how wrong do they have to be to not be useful?".

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

