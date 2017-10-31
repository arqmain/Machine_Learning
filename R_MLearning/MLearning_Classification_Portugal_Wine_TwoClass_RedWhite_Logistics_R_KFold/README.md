# MACHINE LEARNING: Portugal Wine under Two Class approach for Red and White classification with Logistic Regression using R and K fold cross-validation

<br>

This project develops Logistic Regression algorithm of machine learning to classify the class -"white" or "red"- of some wine. The model was developed selecting the variables included by using the stepwise backward elimination method based on AIC and BIC selection criterion. 

I used the wine data set from the UCI Machine Learning data repository. The data can be found here [ http://archive.ics.uci.edu/ml/datasets/Wine+Quality]. 

The original data is separated into white and red datasets. I combined them and created one additional variable: "Class" indicating "white" or "red" wine. After that, I re-coded the "quality" variable to indicate scores greater than or equal to 6 (denoted as "Good") or to indicate scores smaller than 6(denoted as "Bad").

I decided to use two datasets to develop the project: df; dfffull. Dataset "df" keep all registers. The other one, "dfffull", consider all registers but replace outliers by a "threshold" value which is generated for each variable using the upper limit of its Box-plot.

The ROC metric is a metric that can be used to evaluate models based on unbalanced datasets. You can get more information about it in this publication by [ Shir Meir Lador: What metrics should be used for evaluating a model on an imbalanced data set? ](https://medium.com/towards-data-science/what-metrics-should-we-use-on-imbalanced-data-set-precision-recall-roc-e2e79252aeba)

The model performance was evaluated using R, K fold cross-validation, and the ROC metric. I considered 70% and 30% original dataset splitting for the training and testing datasets respectively.


### Table of Contents


#### [ Module 1: Introduction with Data Preprocessing and Exploratory Data Analysis (EDA) ]( http://nbviewer.jupyter.org/github/arqmain/Machine_Learning/blob/master/R_MLearning/MLearning_Classification_Portugal_Wine_TwoClass_RedWhite_Logistics_R_KFold/Project5_Portugal_WINE_TwoClass_RedWhite_EDA.ipynb)

#### [ Module 2: Solving Project with Original Dataset df ]( http://nbviewer.jupyter.org/github/arqmain/Machine_Learning/blob/master/R_MLearning/MLearning_Classification_Portugal_Wine_TwoClass_RedWhite_Logistics_R_KFold/Project5_Portugal_WINE_TwoClass_RedWhite_DatasetDF.ipynb)

#### [ Module 3: Solving project with dataset dffful ]( http://nbviewer.jupyter.org/github/arqmain/Machine_Learning/blob/master/R_MLearning/MLearning_Classification_Portugal_Wine_TwoClass_RedWhite_Logistics_R_KFold/Project5_Portugal_WINE_TwoClass_RedWhite_DatasetDFFFULL.ipynb)

#### [ Module 4: Conclusion ]( http://nbviewer.jupyter.org/github/arqmain/Machine_Learning/blob/master/R_MLearning/MLearning_Classification_Portugal_Wine_TwoClass_RedWhite_Logistics_R_KFold/Project5_Portugal_WINE_TwoClass_RedWhite_CONCLUSIONS.ipynb)
<hr>

><i>Hector Alvaro Rojas<br>
>Data Science, Data Analysis, Visualizations and Applied Statistics / October 30, 2017<br>
>Email: <arqmain2010@gmail.com> <br>
>Url: [http://www.arqmain.net]   /   GitHub: [https://github.com/arqmain]</i>
