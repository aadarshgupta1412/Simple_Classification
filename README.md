# Simple_Classification

AUTHOR : Aadarsh Gupta

# Introduction

The software aims to predict the category of animal (cat/dog) using Simple Classification model trained on Convolutional Neural Networks (CNN). The software is trained as a simple binary Classification model on 25k annotated image dataset of animals (cat/dog), with 24k of the data points taken for training data and rest 1k of data points as validation data. The given dataset also consists of 12.5k image data (annotations separately available here as [sampleSubmissions.csv](https://github.com/aadarshgupta1412/Simple_Classification/blob/main/sampleSubmission.csv)) for testing purposes. The model derived, in no way, refers to the most accurate solution possible and has been constructed with computational resources in hand.

# Packages Used
The following packages have been used while training of the model and visualization puposes :
- numpy : for linear algebra operations
- pandas : for data processing operations I/O in CSV file
- keras (from tensorflow) : to implement CNN
- OpenCV : to handle image operations such as reading, resizing & reshaping
- ImageDataGenerator : for image data augmentation
- ZipFile : to access contents of a zip folder
-  math : for exponential function 

# Requirements 
- Download the dataset from [here](https://www.kaggle.com/c/dogs-vs-cats/data)
- Download this dataset, extract and store it in localdisk

# Available components
- [model.json](https://github.com/aadarshgupta1412/Simple_Classification/blob/main/model.json) : trained model for classification (saved)
- [model.h5](https://github.com/aadarshgupta1412/Simple_Classification/blob/main/model.h5) : stored weights of the trained model
