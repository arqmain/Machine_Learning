# MACHINE LEARNING: Portugal Wine. Two Class approach for Quality classification with XGBoost using R


<br>

This project develops the XGBoost algorithm of machine learning to classify the quality of the wine “Good” or “Bad” according to 12 variables that characterize the wine subject to classification.

I use the famous Portugal wine dataset. Two datasets are available for which one dataset is about red wine and have 1599 different varieties and the other is on white wine and have 4898 varieties. I have combined them into one dataset named “wine” and created one additional variable “type” with its categories “white” and “red”. After that, I re-coded the “quality” variable to indicate scores greater than or equal to 6 (denoted as “Good”) or to indicate scores smaller than 6(denoted as “Bad”).

I used the wine data set from the UCI Machine Learning data repository. The data can be found here [ http://archive.ics.uci.edu/ml/datasets/Wine+Quality ]. 

The modeling is developing using R, “train/test split” and “K fold cross-validation” methods. I consider 70% and 30% original dataset splitting for the training and testing datasets respectively.

XGBoost is a library for developing fast and high-performance gradient boosting tree models. Parallel computation is what makes it this fast. XGBoost is one of the more popular machine learning algorithm these days, and most of its popularity is due to its versatility, scalability, and efficiency. Regardless of the data type (regression or classification), it is well known to provide better solutions than other ML algorithms so far.

<br>

### Table of Contents 

#### [ I Introduction ]( http://www.arqmain.net/GITHUBE/RProject/MLearning/XGBoost/PWine_Classification/XGBoost_Introduction_Logistic.html)

#### [ II Two Class approach for Quality classification with XGBoost considering the “Train/Test split” method ]( http://www.arqmain.net/GITHUBE/RProject/MLearning/XGBoost/PWine_Classification/XGBoost_TrainTest_Logistic.html)

#### [ III Two Class approach for Quality classification with XGBoost considering “KFold cross-validation” method ]( http://www.arqmain.net/GITHUBE/RProject/MLearning/XGBoost/PWine_Classification/XGBoost_KFold_Logistic.html)

#### [ IV Conclusion ]( http://www.arqmain.net/GITHUBE/RProject/MLearning/XGBoost/PWine_Classification/XGBoost_Conclusion_Logistic.html)



<hr>

><i>Hector Alvaro Rojas<br>
>Data Science, Data Analysis, Visualizations and Applied Statistics / December 06, 2017<br>
>Email: <arqmain2010@gmail.com> <br>
>Url: [http://www.arqmain.net]   /   GitHub: [https://github.com/arqmain]</i>
