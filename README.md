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


## About Project
This project uses a Deep Neural Network, more specifically a Convolutional Neural Network (CNN), to differentiate between images of people with and without masks. The CNN manages to get 
an accuracy of **96.8% on the test set**. Then the stored weights of the created model are used to classify as mask or no mask, in real time, using OpenCV.
With the webcam capturing the video, the frames are preprocessed and fed to the model to accomplish this task. The model works efficiently with no apparent lag time between
wearing/removing mask and display of prediction.

#### The model is capable of predicting multiple faces with or without masks at the same time

## Working 

### Without Mask

![image](output.png)

## Dataset

The data used can be downloaded through this [link](https://www.kaggle.com/datasets/aneerbanchakraborty/face-mask-detection-data)There are 1915 images with mask and 1918 images without mask comprosing a total of 3833 images.
