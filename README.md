# MNIST
 Identifying Handwritten Digits

 Here the test.csv, train.csv and sample_submission.csv has been downloaded from Kaggle [[Digit Recognizer](https://www.kaggle.com/c/3004/download-all)].
 
 I have implemented three models to identify the digits:-

i) a N-Hidden Layer model in which the user can specify any number of hidden layers and number of hidden units in each layer, with sigmoid as the activation function. It is implemented fully using only Numpy and Pandas.

ii) a 1-Hidden Layer model in which the activation function used is Leaky-Relu. It is also fully implemented using only Numpy and Pandas.

iii) a CNN model implemented using Keras with Tensorflow as the backend. Image Augmentation has been done using Keras ImageDataGenerator.

Each of the three models have their corresponding Output csv files.
