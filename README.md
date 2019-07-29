# Introduction
This repository provides the code for our classification of hand preference using machine learning analyses of the accelerometer recordings. Unsupervised learning analyses (kmeans and hierarchical clustering) was implemented to classify accelerometer recordings from 14 self-described right handers and 15 self-described left handers. The classification was compared to paper and pen questionnaires. A maximum accuracy of 96% during writing and maximum accuracy of 74% in free living was achieved. To test whether this truly reflects hand preference, supervised learning analyses (support vector machine, extreme learning machine and logistic regression) were implemented and accuracy of 96% during writing and accuracuy of 76% during free living was achieved.  

# Code
The code provides a machine learning analysis of accelerometer data to classify handedness.

# # Dependencies
To be able to run this code, the following need to be installed:
* Python
* sklearn
* scipy
* matplotlib
* numpy
* h5py

# How to run?
Save accelerometer data in Data.mat using MATLAB. Enter paper and pen collected handedness measures. Run the code in a Python environment.
