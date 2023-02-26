# Hospitalization-days-prediction
Prevention of unnecessary hospitalization and prediction of days the patient is required to be hospitalized.
<h1 align="center"> Hospitalization-days-prediction</h1>

<div align= "center"><img src="https://github.com/stuti2403/Hospitalization-days-prediction/blob/main/logo.jpg"/>
  <h4>A system that predicts the duration of hospitalization required with an aim to prevent unnecessary hospitalizations, thereby saving expenditure on healthcare per capita.</h4>
</div>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;

## :innocent: Motivation
Amid the time of recession and increase in healthcare expenses after the pandemic, it has become of utmost importance to cut down expenditure on healthcare as well as minimizing the number of hospitalizations. This would not only promote less crowding in hospitals, bearing in mind precautionary measures in lieu of the pandemic, but also minimize the expenditure of people and government on healthcare.

## :warning: Framework used

- [Python](https://www.python.org/)
- [Data Science]
- [Machine Learning]

<!-- - [MobileNetV2](https://arxiv.org/abs/1801.04381) -->
<h1 align="center"> Relational Schema of the desired system</h1>
<div align= "center"><img src="https://github.com/stuti2403/Hospitalization-days-prediction/blob/main/Relational Schema.png"/></div>

## About Project
THE PROBLEM STATEMENT HAS BEEN SOLVED BY REGRESSION IN THIS PROJECT.
This project needs rigorous data preprocessing which was a required step as a result of the nature of given dataset. The provided database comprised of 13 files in csv format. As a team, we initially gathered our understanding of the given data and the required output, followed by the eventual design of the system.

Data Preprocessing and Feature Extraction: This was the most crucial part of the design as data was very haphazard. We initially found correlation coefficient between the output feature and all input features, followed by handling of missing and inconsistent data. We then found the most influential features through filter method, did one hot encoding for handling categorical features, proceeded with random forest classifier and then wrapping method. Having obtained ranking of every input feature, we selected 70 out of 102 input features.

Data Modelling: To create a prediction model, we used the approach of classification models for categorical data and regresssion models for numerical data. We found decision tree classifier to be most effective for classification part and Gradient boosting classifier to be most effective for regression problem. We the ensembled these two models for increasing the final performace of the ensembled model.

Prediction: The ensembled model was used to predict the final optimized hospitalization days of patients.


## PERFORMANCE

### Decision Tree Classifier
The classifier worked with an accuracy of 83% on the testing data

###Gradient Boosting Regression Model
The model worked with an accuracy of 


###Ensembled Model
The ensembled model had an accuracy of 85%



![image](output.png)

