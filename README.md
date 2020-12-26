# Eigen Faces Algorithm  
This is an algorithm that uses PCA to detect faces.  


## Table of contents  
  - Introduction
  - Technologies
  - Launch and Setup

### Introduction  
Costs of training Artificial Neural Network (ANN) for face detection with large datasets could be represented in time and hardware resources. This is a summary that you have to do with ANN for face detection:
  - First, you need to represent every image in pixels, for example 10M images. 
  - Second, you need to train you model with large data that could take soo much time because you have to chose correct parameters like optimizer, neourons in each layer, activation function to get a good model that detect face of new people.  

All this summary in ANN could take soo much time because your data set like in this case is too big (in numbers and dimensionality). This is the reason why  PCA is excelent for face detection, because use dimension reduction of images making less time to train the model and get a good detection of faces in new images. 
I did this implementation as a homework for Data Minning Course of Universidad San Francisco de Quito. 

## Technologies 

To make this I used some libraries:  
  - PIL - Convert image to pixels matrix
  - PCA - Sklearn library to make PCA
  - Matplotlib - Show images and other graphs
  - Spacy - Meassure distance between two points
  - Numpy - Make operations between 2 matrix

## Launch and Setup

This project was implemented in Google Colab. You could find [data set](https://drive.google.com/drive/folders/1ptGp-PaNS6w3m60l7QAb5D3bkUUi-nXP?usp=sharing) with some faces to train your model. You also could split data to train and test. 


