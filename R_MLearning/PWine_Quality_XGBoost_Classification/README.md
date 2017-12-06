# MACHINE LEARNING: Portugal Wine. Two Class approach for Quality classification with XGBoost using R


<br>

This project develops Neural Network algorithm of machine learning to classify the class of wine -"white" or "red"- according to 12 variables that characterize the wine subject to classification. I use Neuralnet R library.

Neuralnet is built to train multi-layer perceptrons in the context of regression analyses, i.e. to approximate functional relationships between covariates and response variables.

I used the wine data set from the UCI Machine Learning data repository. The data can be found here [ http://archive.ics.uci.edu/ml/datasets/Wine+Quality ]. 

The original data is separated into white and red datasets. I combined them and created one additional variable: "type" indicating "white" or "red" wine. Our original dataset is an imbalance one. There are 6497 registers but only 1599 (24.6%) are of the red class of wine. The model performance was evaluated using R, K fold cross-validation and the metrics Accuracy, Specificity, Recall, Precision, F1.

I do not consider two variables that appear in the original base. They could generate a problem of multicollinearity in the process of classification. So, we got rid of them. At the same time, I keep all the register of the original database but replace the upper outliers by its corresponding Threshold value which is generated for each variable using the upper limit of its Box-plot. The application of this rule does not reduce the original data size because it does not eliminate any register. So, the data size is the same as the original dataset (6497).

<br>

### Table of Contents 

#### I Introduction

#### II Two Class approach for Quality classification with XGBoost considering the “Train/Test split” method

#### III Two Class approach for Quality classification with XGBoost considering “KFold cross-validation” method

#### IV Conclusion



<hr>

><i>Hector Alvaro Rojas<br>
>Data Science, Data Analysis, Visualizations and Applied Statistics / December 06, 2017<br>
>Email: <arqmain2010@gmail.com> <br>
>Url: [http://www.arqmain.net]   /   GitHub: [https://github.com/arqmain]</i>
