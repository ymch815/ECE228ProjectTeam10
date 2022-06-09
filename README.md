# Machine Learning Applications on Breast Cancer Diagnosis -- ECE 228 2022 Spring, Team 10

This is the Github project for machine learning applications on breast cancer diagnosis, created by team 10 of ECE 228, 2022 spring.  

People:   
Haodong Qin: qhaodong@ucsd.edu  
Mingchen Yao: miyao@ucsd.edu  
Min Zhong: mizhong@ucsd.edu  


## Introduction

There are four folders within this project: Diagnostic_data, Self_constructed_CNN, Pre_trained_model and SHAP, which corresponds to the four parts of the project.   

Diagnostic_data -- ML methods applied on the diagnostic (tabular) dataset.  
Self_constructed_CNN -- VGG-16-like CNN applied on the image dataset.  
Pre_trained_model -- Several pretrained CNN models applied on the image dataset. 
SHAP -- SHAP analysis on both diagnostic data NN and image data NN. 


## Run the Code

There are mainly jupyter notebooks for all the three methods, should be easy to run. Make sure you have Pytorch and Scikit-learn installed and the corresponding dataset downloaded.  

Also, it would be better to use GPU for the CNN training with the image dataset.  

### Diagnostic_data
The dataset needed for the analysis is already included in the same directory as DiagnosticData.ipynb. It is part of the Wisconsin Breast Cancer (Diagnostic) Dataset: https://archive.ics.uci.edu/ml/datasets/breast+cancer+wisconsin+(diagnostic)

### Self_constructed_CNN
This is a self-constructed CNN. 
Please make sure that this directory contains the image data.
image data can be downloaded from https://www.kaggle.com/code/mohitgora/cancer-detection-cnn/data. 
Code is run in jupyter notebook. 

### SHAP
Please make sure you have Shap installed. The SHAP analysis itself may take several minutes to complete. Besides, before each analysis, the network need to be trained, which takes ~minutes for diagnostic data and ~ 1 hour for image data. It would be better to use GPU for the CNN training with the image dataset. 

