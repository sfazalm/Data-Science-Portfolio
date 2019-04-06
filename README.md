# Data-Science-Portfolio
A portfolio of all the data science projects completed as a part of academics or as independent projects.

(__Note:__ All the required datasets are placed in the data folder and should be moved to the same directory as the notebook at the time of use.)

## Machine Learning Projects

__1. `DNN_MNIST`:__ This project is a compilation of different kinds of neural networks (deep, shallow, and covolutional). We train on the MNIST dataset and compare metrics from all the models.

__2. `CreditRisk_Classification`:__ This project is a binary (good/bad) classification probelm and involves the use of Decision Tree Classifier, Random Forest Classifier and a Deep Neural Network. The first two classifiers were written using the `scikit-learn` libraries while the last one was written using the `keras` library in `tensorflow`. A maximum accuracy of 74.8% was achieved by the Random Forest Classifier which is significant as the maximum accuracy listed on openml.org for this dataset is roughly 78%. This project gives a good insight in the building and training process of the classifiers and compares the accuracy between them.

__2. ```Forecasting_Diabetes_SVM```:__ This project is binary classification/forecasting problem. We use a dataset of 768 cases where patients were tested positive or negative. Based on the 8 features provided, we predict the oset of diabetes mellitus using a Support Vector Machine classifier. The highest accuracy achived was 80.36% with a precision of 80.85%, which is impressive compared to the best result on openml.org, which are 78.78% (accuracy) and 78.09% (precision).

## Data Visualization Project

__1. `California_Wildfire_Visualization`:__ This is purely a data visualization project with some degree of data cleaning involved. The major libraries used in this project are matplotlib and pandas. In this project, I have visualized the trend of wildfires (in terms of frequency and area covered) betwwen the year 1920-2017. The graphs are easy to read and intuitive.

## Tensorflow Tutorials

__1. `Regression`:__ A tutorial on how to perform linear and logistic regression using TensorFlow.

__2. `CNN_MNIST`:__ A tutorial on how to construct and train a Convolutional Neural Network on MNIST dataset using TensorFlow.
