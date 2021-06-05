# Number_Plate_Recognition  <img src='https://cdn.hackernoon.com/images/h5cr3yss.gif' alt='github' height='50'>
In this repository,you can find out the number plate recognition madel using deep learning pre-trained model named: **easyOCR**

![Generic badge](https://img.shields.io/badge/Computer-Vision:-green.svg)                              ![Generic badge](https://img.shields.io/badge/Python-V3:-blue.svg)        ![Generic badge](https://img.shields.io/badge/Easy-OCR:-orange.svg)               ![Generic badge](https://img.shields.io/badge/Numpy-v1:-green.svg)                  ![Generic badge](https://img.shields.io/badge/C:Imutils:-white.svg)               ![Generic badge](https://img.shields.io/badge/Matplotlib-pyplot:-blue.svg)             ![Generic badge](https://img.shields.io/badge/CV2-V1:-orange.svg)



![Generic badge](https://img.shields.io/badge/Problem_Statement-:-blue.svg)  
**Identify the number plate of Vehicles (in this model i used for Car)**
Train a simple Optical Character Recogniser(OCR) model to identify the text from an image.
Train an ML model to detect text from an uploaded image. Find below-attached sample images. Other
images/data can be scraped from the internet.
  
![Generic badge](https://img.shields.io/badge/Optional-:-orange.svg)  
Create a simple web server that hosts a page where a user can upload the image to do an OCR. The web-page
should work such that if a user uploads an image, the model trained in Step 1 should inference it. Inference results
should be shown in a simple manner as text output. In case you are familiar with TensorFlow-lite, you can also use
Android-app to demonstrate the model instead of a web server


![Generic badge](https://img.shields.io/badge/Limitations-:-red.svg) 

You can use reusable models/tools for image classification.

For the web application, use any language of your choice **(OPTIONAL)**


![Generic badge](https://img.shields.io/badge/Datasets-Link-green.svg) 

Click Here : https://drive.google.com/drive/folders/1buf4b3FXInPFr4RbCOPx_LSN4Zj9Yb14?usp=sharing



![Generic badge](https://img.shields.io/badge/Proposed-Solution:-orange.svg) 

I'm using image recognition techniques to separate the coins, classify them on their own.
I am doing this with datasets since it makes the algorithm more flexible, mostly it seems that the segmentation part is fine with minor error rates and that most of the issues with the multi-coin task can be explained as statistical error if we consider 97% accuracy for classification (just a regular classifier) and an average of 7-8 coins in the image

I have been trying to solved this problem using  **Machine Learning**/**Deel Learning** algorthms known as **Convolutional Newral Network(CNN)** for better accuracy. I wants to use data augmentation technique but we have sufficient data sets which's give use 80%+ accuracy that why i'm skip it.


**Reference :** https://keras.io/api/models/model_training_apis/#compile-method


**Activation Function:**  "relu"

**Activation Function for last layer:**  "softmax"

**Accuracy Rate:**  92.2 %
