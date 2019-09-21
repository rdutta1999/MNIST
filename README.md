# MNIST
 Identifying Handwritten Digits

 The Dataset has been downloaded from [Digit Recognizer](https://www.kaggle.com/c/3004/download-all) on Kaggle. The **Train** and **Test** csv files are then placed in the **same directory** where the IPYNB files reside.
 
 Here, we have implemented **three models** to perform the Digit Classification task:-

1. a **N-Hidden Layer model**,where the user has to specify the **number of hidden layers** to be used and the **number of hidden units** in each layer. The activation function is **sigmoid**. It is implemented fully using only **Numpy and Pandas**.

2. a **1-Hidden Layer** model in which the activation function used is **Leaky-Relu**. It is also fully implemented using only **Numpy and Pandas**.

3. a **CNN model** implemented using **Keras** with **Tensorflow** as the backend. Image Augmentation has been done using **Keras ImageDataGenerator**.

Each of the three models have their corresponding Output csv files.
