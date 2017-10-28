# MACHINE LEARNING: Portugal Wine under Two Class approach for Quality classification with Logistic Regression using R and K fold cross-validation

<br>

This project develops Logistic Regression algorithm of machine learning to classify the quality -"Good" or "Bad"- of some Portugal wine. The model was developed selecting the variables included by using the stepwise backward elimination method based on AIC selection criterion. The model performance was evaluated using R, K fold cross-validation, and the ROC metric.

TI used the wine data set from the UCI Machine Learning data repository. The data can be found here [ http://archive.ics.uci.edu/ml/datasets/Wine+Quality]. The goal is to predict wine quality which has 7 integer values from 3 to 9.

The original data is separated into white and red datasets. I combined them and created one additional variable: "Class" indicating "white" or "red" wine. After that, I re-coded the "quality" variable to indicate scores greater than or equal to 6 (denoted as "Good") or to indicate scores smaller than 6(denoted as "Bad").

I decided to use two datasets to develop the project: df; dfffull. Dataset "df" keep all registers. The other one, "dfffull", consider all registers but replace outliers by a "threshold" value which is generated for each variable using the upper limit of its Box-plot.

The ROC metric is a metric that can be used to evaluate models based on unbalaced datasets. You can get more information about it in this publication by [ Shir Meir Lador: What metrics should be used for evaluating a model on an imbalanced data set? ](https://medium.com/towards-data-science/what-metrics-should-we-use-on-imbalanced-data-set-precision-recall-roc-e2e79252aeba)

The project develops Logistic Regression algorithm of machine learning to classify the quality of the wine "Good" or "Bad" according to the 12 variables that characterize the wine subject to classification.

### Table of Contents


#### [ Module 1: Data Preprocessing and Exploratory Data Analysis (EDA) ]( http://nbviewer.jupyter.org/github/arqmain/Machine_Learning/blob/master/R_MLearning/MLearning_Classification_Portugal_Wine_Quality_GoodBad_R_KFold/Project6_Portugal_WINE_TwoClass_EDA.ipynb)

#### [ Module 2: Solving project with original dataset df ]( http://nbviewer.jupyter.org/github/arqmain/Machine_Learning/blob/master/R_MLearning/MLearning_Classification_Portugal_Wine_Quality_GoodBad_R_KFold/Project6_Portugal_WINE_TwoClass_DatasetDF.ipynb)

#### [ Module 3: Solving project with original dataset dfffull ]( http://nbviewer.jupyter.org/github/arqmain/Machine_Learning/blob/master/R_MLearning/MLearning_Classification_Portugal_Wine_Quality_GoodBad_R_KFold/Project6_Portugal_WINE_TwoClass_DatasetDFFFULL.ipynb)

#### [ Module 4: Conclusion ]( http://nbviewer.jupyter.org/github/arqmain/Machine_Learning/blob/master/R_MLearning/MLearning_Classification_Portugal_Wine_Quality_GoodBad_R_KFold/Project6_Portugal_WINE_TwoClass_CONCLUSIONS.ipynb)
<hr>

><i>Hector Alvaro Rojas<br>
>Data Science, Data Analysis, Visualizations and Applied Statistics / October 25, 2017<br>
>Email: <arqmain2010@gmail.com> <br>
>Url: [http://www.arqmain.net]   /   GitHub: [https://github.com/arqmain]</i>
