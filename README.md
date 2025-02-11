# Image Classification Project

This project focuses on solving an **Image Classification** problem using two different approaches: **Artificial Neural Networks (ANN)** and **Convolutional Neural Networks (CNN)**. The dataset used for this project is **CIFAR-10**, which consists of 60,000 32x32 color images in 10 different classes, with 6,000 images per class.

## Dataset

The dataset used for this project is **CIFAR-10**, a well-known dataset in the field of machine learning and computer vision. It contains 10 different classes, each with 6,000 images, for a total of 60,000 images. The classes are:

- Airplane
- Automobile
- Bird
- Cat
- Deer
- Dog
- Frog
- Horse
- Ship
- Truck

These images are of size 32x32 pixels and are labeled with the corresponding class.

## Problem Statement

The goal of this project is to classify images into one of the 10 categories based on the given dataset. We approached the problem using two different deep learning models:

1. **Artificial Neural Network (ANN)**: A traditional deep learning model consisting of fully connected layers to classify the images.
2. **Convolutional Neural Network (CNN)**: A more specialized model for image processing, utilizing convolutional layers to extract features and pooling layers to reduce spatial dimensions.

## Approach

### 1. Artificial Neural Network (ANN)

- **Model Architecture**: The ANN model consists of an input layer, two hidden layers, and an output layer.
- **Activation Function**: ReLU (Rectified Linear Unit) activation function is used for the hidden layers, and softmax activation is used for the output layer to predict the probability distribution of the 10 classes.
- **Optimizer**: Adam optimizer is used for training the model.
  
#### Test Set Accuracy: 45.48%

### 2. Convolutional Neural Network (CNN)

- **Model Architecture**: The CNN model consists of convolutional layers, followed by max-pooling layers, and finally, dense layers for classification.
- **Convolutional Layers**: Filters are applied to extract essential features from the images.
- **Pooling Layers**: Max-pooling is used to downsample the image and reduce the complexity of the model.
- **Fully Connected Layers**: Dense layers for classification, similar to ANN.
  
#### Test Set Accuracy: 68.40%

## Results

- **ANN Test Accuracy**: 45.48%
- **CNN Test Accuracy**: 68.40%

As observed, the Convolutional Neural Network (CNN) outperforms the Artificial Neural Network (ANN) by a significant margin in terms of accuracy, demonstrating the effectiveness of CNNs for image classification tasks.

## Conclusion

This project demonstrates the power of Convolutional Neural Networks in solving image classification problems, especially when working with datasets like CIFAR-10. CNNs are well-suited for image recognition tasks because they can automatically learn and extract important features from the images, whereas traditional ANNs may struggle with such tasks due to their fully connected nature.
