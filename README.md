# GAN for MNIST and CIFAR-10 Datasets
GAN implementation with Fully Connected Layers and Convolutional Neural Networks on MNIST and CIFAR-10 datasets.

## General Information
This is a GAN implementation project that contains one program of GAN with Fully Connected Layers and two programs of GAN with Convolutional Neural Networks written on Jupyter Notebook. The GAN with Fully Connected Layers is implemented on the MNIST dataset with 28 x 28 numerical figure images, and the GAN with Convolutional Neural Network is implemented on both the MNIST dataset with 28 x 28 numerical figure images and the CIFAR-10 dataset with 32 x 32 various images.

There are 3 program files in this project:
1. **1_GAN_MNIST_28x28_Linear_200ep.ipynb**: GAN with Fully Connected Layers on MNIST dataset for 200 epochs.

* **MNIST Linear Scores**

<img title="MNIST Linear Scores" src="https://github.com/firatkorkmaz/GAN-MNIST-CIFAR10/blob/main/images/MNIST_Linear_Scores.png">

* **MNIST Linear Images**

<img title="MNIST Linear Images" src="https://github.com/firatkorkmaz/GAN-MNIST-CIFAR10/blob/main/images/MNIST_Linear_Images.png">

2. **2_GAN_MNIST_28x28_Conv_70ep.ipynb**: GAN with Convolutional Neural Networks on MNIST dataset for 70 epochs.

* **MNIST Convolutional Scores**

<img title="MNIST Convolutional Scores" src="https://github.com/firatkorkmaz/GAN-MNIST-CIFAR10/blob/main/images/MNIST_Conv_Scores.png">

* **MNIST Convolutional Images**

<img title="MNIST Convolutional Images" src="https://github.com/firatkorkmaz/GAN-MNIST-CIFAR10/blob/main/images/MNIST_Conv_Images.png">

3. **3_GAN_CIFAR10_32x32_Conv_70ep.ipynb**: GAN with Convolutional Neural Networks on CIFAR-10 dataset for 70 epochs.

* **CIFAR-10 Convolutional Scores**

<img title="CIFAR-10 Convolutional Scores" src="https://github.com/firatkorkmaz/GAN-MNIST-CIFAR10/blob/main/images/CIFAR10_Conv_Scores.png">

* **CIFAR-10 Convolutional Images**

<img title="CIFAR-10 Convolutional Images" src="https://github.com/firatkorkmaz/GAN-MNIST-CIFAR10/blob/main/images/CIFAR10_Conv_Images.png">

## Setup & Run
* Install the necessary libraries for the programs:
```
pip install -r requirements.txt
```
* Run Jupyter Notebook and open the Notebook files with it:
```
jupyter notebook
```
