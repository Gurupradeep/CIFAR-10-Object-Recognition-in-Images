# CIFAR-10-Object-Recognition-in-Images
Implementing and comparing performance of various deep learning models on CIFAR-10 dataset

This repository contains the implementation of various famous deep learning models using Keras. Their performance has been compared on CIFAR-10 dataset, by using the same hyperparameters to make a fair comparison.

**Models compared**
1. Wide Residual Network
2. ResNet
3. VGG

**Papers referred**

1. [Very Deep Convolutional Networks For Large-Scale Image Recognition](https://github.com/Gurupradeep/CIFAR-10-Object-Recognition-in-Images/blob/master/Papers/VGG.pdf)
2. [Deep Residual Learning for Image Recognition](https://github.com/Gurupradeep/CIFAR-10-Object-Recognition-in-Images/blob/master/Papers/ResNet50.pdf)
3. [Wide Residual Networks](https://github.com/Gurupradeep/CIFAR-10-Object-Recognition-in-Images/blob/master/Papers/Wide_Residual_Networks.pdf)

## INSTALLATION OF REQUIRED TOOLS
#### 1. Tensorflow
Refer to the following link https://www.tensorflow.org/install/install_sources. Tensorflow is used as backend for Keras. The link contains installation instructions with and without gpu support

#### 2. Keras
Keras is a high-level neural networks API, written in Python and capable of running on top of TensorFlow, CNTK, or Theano. It was developed with a focus on enabling fast experimentation.

* To install Keras

    sudo pip install keras

#### 3. Matplotlib
Matplotlib is a Python 2D plotting library which produces publication quality figures in a variety of hardcopy formats and interactive environments across platforms.
* Refer to following link for installation instructions https://matplotlib.org/users/installing.html.
While installing it or tensorflow number of dependencies like Numpy will be installed.

#### 4.Skimage
Scikit-image is an image processing toolbox for SciPy. It is used for loading,saving and applying various transformations like color to gray and gray to color on images.

* Refer following link for installation instructions http://scikit-image.org/docs/dev/install.html

#### 5. graphviz
This package facilitates the creation and rendering of graph descriptions in the DOT language of the Graphviz graph drawing software from Python. It is required to plot the models in keras.
* To install graphviz

    sudo pip install graphviz
    
#### 6. Jupyter Notebook
The Jupyter Notebook is an open-source web application that allows you to create and share documents that contain live code, equations, visualizations and narrative text
* Refer following link for installation instructions https://www.digitalocean.com/community/tutorials/how-to-set-up-a-jupyter-notebook-to-run-ipython-on-ubuntu-16-04

# Quick start

Run the following commands in Terminal. 

    git clone https://github.com/Gurupradeep/CIFAR-10-Object-Recognition-in-Images.git
    cd CIFAR-10-Object-Recognition-in-Images
    cd Models
    jupyter notebook
It opens up all the notebooks which are there in the directory in the browser.
* ResNet.ipynb Contains the implementation code of ResNet
* VGG16.ipynb Contains the implementation code of VGG 
* Wide_Residual_Network.ipynb contains the implementaion of Wide residual Networks
* SimpleCNN.ipynb contains code of a simple CNN which gives more than 90 percent accuracy on cifar-10.

# Procedure followed 
* ResNet and Wide residual models have been trained from scratch
* VGG is trained with the help of transfer learning. Here the models weights are initialised with ones obtained from training on ImageNet
* All the hyperparameters are kept constant for all the models while training.

## TODO : Quick start, Procedure followed and Comparison of various models.
