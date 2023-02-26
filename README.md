# Hospitalization-days-prediction
Prevention of unnecessary hospitalization and prediction of days the patient is required to be hospitalized.
<h1 align="center"> Hospitalization-days-prediction</h1>

<div align= "center"><img src="https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.istockphoto.com%2Fvector%2Fhealth-care-logo-vector-design-element-gm958800720-261810734&psig=AOvVaw3wY-FVbDmwku7aOYzMdcJQ&ust=1677485864129000&source=images&cd=vfe&ved=0CBAQjRxqFwoTCPDIxq7gsv0CFQAAAAAdAAAAABAE"/>
  <h4>A system that predicts the duration of hospitalization required with an aim to prevent unnecessary hospitalizations, thereby saving expenditure on healthcare per capita.</h4>
</div>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;

## :innocent: Motivation
Amid the ongoing COVID-19 pandemic, there are no efficient face mask detection applications which are now in high demand for transportation means, densely populated areas, residential districts, large-scale manufacturers and other enterprises to ensure safety. The absence of large datasets of __‘with_mask’__ images has made this task cumbersome and challenging. 


## :warning: TechStack/framework used

- [OpenCV](https://opencv.org/)
- [Haar Cascade froontal face detector](https://docs.opencv.org/3.4/db/d28/tutorial_cascade_classifier.html)
- [Keras](https://keras.io/)
- [TensorFlow](https://www.tensorflow.org/)
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
